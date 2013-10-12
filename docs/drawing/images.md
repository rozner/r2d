---
layout: main
---

# <a href="/docs/#warning"><span class="warning"></span></a> Images

Formats supported: BMP, PNG, JPG.

Parameters:

```
x, y, "path_to_image", visible=true
```

Instance methods:

```
x/=, y/=, width/=, height/=
```

Examples:

```ruby
img = R2D::Image.new(x, y, "ruby.png")
img = R2D::Image.new(x, y, "media/ruby.png", false)

img.x = 10
img.y = 20
img.width = 125
img.height  # returns height
```
