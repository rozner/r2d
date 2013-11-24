---
layout: new
breadcrumbs: docs › drawing › shapes
---

# Shapes

R2D provides several geometric primitives like [squares](#squares), [rectangles](#rectangles), [quadrilaterals](#quadrilaterals), and [triangles](#triangles).

<a name="squares"></a>
## Squares

Parameters:

```
x, y, size, color="white"
```

Instance methods:

```
x/=, y/=, size/=, color/=
```

Examples:

```ruby
s = R2D::Square.new(x, y, size)
s = R2D::Square.new(x, y, size, color)

s.x = 10
s.y = 20
s.size = 25
s.color = "red"
s.color = [1.0, 0, 0, 0.2]
```

<a name="rectangles"></a>
## Rectangles

Parameters:

```
x, y, width, height, color="white"
```

Instance methods:

```
x/=, y/=, width/=, height/=, color/=
```

Examples:

```ruby
r = R2D::Rectangle.new(x, y, width, height)
r = R2D::Rectangle.new(x, y, width, height, color)

r.x = 10
r.y = 20
r.width = 200
r.height = 50
r.color = "blue"
r.color = [255, 0, 255, 255]
```

<a name="quadrilaterals"></a>
## Quadrilaterals

Parameters:

```
x1, y1, x2, y2, x3, y3, x4, y4, color="white"
```

Instance methods:

```
x1/=, y1/=, x2/=, y2/=, x3/=, y3/=, x4/=, y4/=, color/=
```

Examples:

```ruby
q = R2D::Quad.new(x1, y1, x2, y2, x3, y3, x4, y4)
q = R2D::Quad.new(x1, y1, x2, y2, x3, y3, x4, y4, color)

q.x1 = 10
q.y1 = 20
q.color = "blue"
q.color = [0.0, 0.0, 1.0, 0.5]
```

<a name="triangles"></a>
## Triangles

Parameters:

```
x1, y1, x2, y2, x3, y3, color="white"
```

Instance methods:

```
x1/=, y1/=, x2/=, y2/=, x3/=, y3/=, color/=
```

Examples:

```ruby
t = R2D::Triangle.new(x1, y1, x2, y2, x3, y3)
t = R2D::Triangle.new(x1, y1, x2, y2, x3, y3, color)

t.x1 = 10
t.y1 = 20
t.color = "red"
t.color = [0, 0, 200, 100]
```

<!--
<a name="lines"></a>
## <a href="/docs/#warning"><span class="warning"></span></a> Lines

Parameters:

```
x1, y1, x2, y2, color="white"
```

Examples:

```ruby
l = R2D::Line.new(x1, y1, x2, y2, w)
l = R2D::Line.new(x1, y1, x2, y2, w, color)

l.x1 = 10
l.y1 = 20
l.color = "red"
l.color = [0, 0, 1, 1]
```
-->
