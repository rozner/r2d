---
layout: main
---

# <a href="/docs/#warning"><span class="warning"></span></a> Playing Audio

Formats include: MP3, AAC, and WAV.

<!-- TODO: How does audio work? What C libraries are used. -->

## Sounds

Sounds are audio that can be played.

Parameters:

```
"path_to_sound", volume=10
```

Instance methods:

```
play, playing?, pause, paused?, stop, loop
```

Examples:

```ruby
s = R2D::Sound.new("media/snare.mp3")
s = R2D::Sound.new("media/snare.mp3", 5)

s.play
s.playing?  # returns `true`

s.pause
s.paused?   # returns `true`

s.stop
s.play_loop
```
