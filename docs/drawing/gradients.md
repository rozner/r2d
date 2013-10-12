---
layout: main
---

# <a href="/docs/#warning"><span class="warning"></span></a> Gradients

Gradients can be created for [squares and rectangles](#squares_and_rectangles), [quadrilaterals](#quadrilaterals), [triangles](#triangles), and [lines](#lines).

## Parameters

All gradient methods take a Hash where keys refer to the corners of the shape and values represent the color.

```ruby
{ :corner => color }
```

`:corner` is specific to each shape (described below). `color` is either a string...

```ruby
"red", "blue", "yellow", etc
```
...or an array containing red, green, blue, alpha values 0 or 1 (`Integer`) or 0.0..1.0 (`Float`):

```ruby
[r, g, b, a]

# examples
[1, 0, 0.8, 0.5]
```

<a name="squares_and_rectangles"></a>
## Squares and Rectangles

`:corners` can be these groupings:

```ruby
# vertical
:top, :bottom

# horizontal
:left, :right

# all corners
:top_left, :top_right, :bottom_left, :bottom_right
```

Examples:

```ruby
r.gradient = {
  top: "red",
  bottom: "blue"
}

r.gradient({
  left: [1, 0.8, 0.5, 0.2],
  right: "blue"
}

r.gradient = {
  top_left: "red",
  top_right: "blue",
  bottom_left: "green",
  bottom_right: "yellow"
}
```

<a name="quadrilaterals"></a>
## Quadrilaterals

<!-- TODO: Are these clockwise? -->

```ruby
:first, :second, :third, :fourth
```

Examples:

```ruby
q.gradient = {
  first: "red",
  second: "blue",
  third: [0, 0.8, 1, 1],
  fourth: "yellow"
}
```

<a name="triangles"></a>
## Triangles

The triangle gradient method takes a Hash containing keys (symbols) referring to the first, second, and third points of the triangle.

`:corners` are:

<!-- TODO: Are these clockwise? -->

```ruby
:first, :second, :third
```

Examples:

```ruby
t.gradient = {
  first: "red",
  second: "blue",
  third: [0, 0.8, 1, 1]
}
```

<a name="lines"></a>
## Lines

The line gradient method takes a Hash containing keys (symbols) referring to the start and ends.

`:corners` are:

<!-- TODO: Explain :start == x1, y1 and so on -->

```ruby
:first, :last
```

Examples:

```ruby
l.gradient = {
  first: "red",
  last: "blue"
}
```
