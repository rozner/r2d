---
layout: new
---

# Welcome to R2D!

R2D is a gem for creating 2D graphics applications in Ruby. Read the [documentation](/docs), or view the project on [GitHub](https://github.com/blacktm/r2d).

<span class="warning"></span> Warning: This gem is under some seriously heavy development and subject to change, a lot.

The gem is only available locally until a public release is made.
[View the local installation instructions ››](https://github.com/blacktm/r2d#installing)

## A Simple R2D Application

```ruby
require 'r2d'

# Create a new window instance
window = R2D::Window.new

# Create a new shape
s = R2D::Square.new(0, 0, 100, "red")

# Add the shape to the window
window.add(s)

# Show the window
window.show
```

<!--
Aenean lacinia bibendum nulla sed consectetur. Nulla vitae elit libero, a pharetra augue. Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Cras mattis consectetur purus sit amet fermentum. Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum.

![Challenges](http://learnruby.s3.amazonaws.com/3_final.png)

Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit.

![Snake Project](http://learnruby.s3.amazonaws.com/4_final.png)

Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor.

![Fishes Project](http://learnruby.s3.amazonaws.com/5_final.png)

Nullam id dolor id nibh ultricies vehicula ut id elit.

![Side-Scroller Project](http://learnruby.s3.amazonaws.com/6_final.png)

Maecenas faucibus mollis interdum.

# Parturient Tristique Egestas

Donec ullamcorper nulla non metus auctor fringilla. Etiam porta sem malesuada magna mollis euismod. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Maecenas sed diam eget risus varius blandit sit amet non magna. Lorem ipsum dolor sit amet, consectetur adipiscing elit.

<a name="faq"></a>
# FAQ

_Have a question? Contact me above!_

No questions yet.
-->


<!--
<a href="javascript:toggle('1');"></a>

<div id="1" style="display:none">
  <p></p>
</div>
-->
