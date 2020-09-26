# pdf-continuous-scroll-mode.el
A minor mode for Emacs that implements a two-buffer hack to provide continuous scrolling in pdf-tools

Probably this minor-mode will get updated a few times over the next days, so keep your eyes on it. This mode works only from Emacs 27 (see previous commment). It includes keybindings to just work also on Spacemacs.

https://github.com/dalanicolai/pdf-continuous-scroll-mode.el

Just load the file and pdf-tools will start up in continuous scroll mode. You can then just toggle the mode on and of using `M-x pdf-continuous-scroll-mode`. If you don't want to start pdf-tools with the minor mode activated then comment out the hook at the start of `pdf-continuous-scroll-mode.el`.

Of course any feedback is welcome (possibly by opening an issue in the repo).
