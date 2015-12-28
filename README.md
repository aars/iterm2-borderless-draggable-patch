iterm2-borderless-padding
-------------------------

### Inspired by https://github.com/jaredculp/iterm2-borderless-padding

This repo contains the patch file used to remove borders from iTerm2. Since this
leaves us with an undraggable window, this patch enables dragging on the tab bar.
Which has the downside of not being able to rearrange tabs with the mouse, but I 
can live with that.

This patch *does* *not* contain the padding that Jared's patch adds.

The makefile will clone the iTerm2 repo if it doesn't exist already. After compiling 
your new binary will be located at `iTerm2/build/Development/iTerm2.app`.
