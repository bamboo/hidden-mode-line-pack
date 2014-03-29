## hidden-mode-line-mode

A minor Emacs mode for hiding the mode-line by [Bastien Guerry](http://bzg.fr/emacs-hide-mode-line.html).

## Installation

git clone into your ~/.live-packs directory and add
```lisp
(live-add-packs '(~/.live-packs/hidden-mode-line-pack))
;; If you want to hide the mode-line in every buffer by default
;; (add-hook 'after-change-major-mode-hook 'hidden-mode-line-mode)
```
to your ~/.emacs-live.el
