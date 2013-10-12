---
layout: main
---

# Welcome to R2D

This documentation describes how R2D works and can be used to create 2D applications in Ruby.

<a name="warning"></a>
## <span class="warning"></span> WARNING! Under Development!

This gem in still under construction. Where there is an <span class="warning"></span> icon, this feature has not yet been implemented.

## Common Notation

Instance methods with `method/=` means both `method` and `method=` are available to get and set attributes.

## Getting Started

To write a simple R2D application, first `require` the `r2d` gem:

```ruby
require 'r2d'
```

Next, create a new window instance using the [Window](/docs/window/concepts.html) class.

```ruby
window = R2D::Window.new
```

Then, create and add shapes, images, and text to the window.

```ruby
r = R2D::Rectangle.new(0, 0, 100, 100, "blue")

window.add(r)
```

When ready to show the window, call the `show` method.

```ruby
window.show
```
