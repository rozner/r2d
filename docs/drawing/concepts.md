---
layout: main
---

# Drawing Concepts

R2D supports a number of basic graphics primitives like triangles, squares, and rectanges. Every object that can be drawn has a set of **common parameters**:

```
x = an 'x'  coordinate (Integer)
y = an 'y'  coordinate (Integer)
s = the size    (Integer)
w = the width   (Integer)
h = the height  (Integer)

c = the color  (String)
or...
c = [r, g, b, a] (Array)
  where values are 0 or 1 (Integer) or 0.0..1.0 (Float)
    r = red
    g = green
    b = blue
    a = alpha
```

Objects also have **common instance methods**:

```ruby
# Toggle the visibility of the object
object.hide
object.show
```
