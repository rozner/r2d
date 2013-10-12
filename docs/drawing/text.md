---
layout: main
---

# <a href="/docs/#warning"><span class="warning"></span></a> Text

Parameters:

```
x, y, h, "content", c="white", visible=true
```

Instance methods:

```
x/=, y/=, content/=, color/=
```

Examples:

```ruby
t = R2D::Text.new(x, y, 20, "hello world")
t = R2D::Text.new(x, y, 20, "hello world", "blue", false)

t.x = 10
t.y = 20
```
