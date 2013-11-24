---
layout: new
breadcrumbs: docs › input › keyboard
---

# Keyboard Input

To capture a single key press where `key` is any valid keyboard character `a..z`, `A..Z`, `0..9`, and strings representing arrows, alt, control, shift, etc. See all available [character strings](#character_strings).

In these examples, `window = R2D::Window.new`.

```ruby
window.on_key "#{key}" do
  #...
end
```

Example:

```ruby
window.on_key 'a' do
  # letter 'a' pressed
end
```

Do something repeatedly as a key is held down.

```ruby
window.key_down "#{key}" do
  #...
end
```

Example:

```ruby
window.key_down 's' do
  # letter 's' held down
end
```

<a name="character_strings"></a>
## Character Strings

The available character strings are:

```
('a'..'z') || ('A'..'Z') || ('0'..'9')
'up'
'down'
'left'
'right'
'left_alt'
'right_alt'
'left_control'
'right_control'
'left_shift'
'right_shift'
'backspace'
'delete'
'space'
'tab'
'return'
```
