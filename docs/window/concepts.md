---
layout: main
---

# The Window

R2D will create and manage window instances for you. Windows are created using `window = R2D::Window.new`.

## Window Attributes

Attributes change the appearance and behavior of the window. These are applied before drawing is done.

```ruby
                     # Defaults:
title: "My App"      #  "R2D"
width: 400           #  640
height: 300          #  480
cursor: false        #  `true`
background: "white"  #  "black"
```

Example:

```ruby
window = R2D::Window.new(title: "My App", width: 300, height: 200, cursor: false)
```

## <a href="/docs/#warning"><span class="warning"></span></a> Clearing the Window

To remove all objects from the window, use:

```ruby
window.clear
```

Note this does not delete the objects themselves – references remain intact. This is equivalent to calling `window.remove(object)`.

# <a href="/docs/#warning"><span class="warning"></span></a> The Update Loop

Do something each time the graphic environment is updated (60 times / second).

```ruby
window.update do
  # do something
end
```

Examples:

```ruby
window.update do
  if key_down? <key_string>
    # do something
  end
end
```
