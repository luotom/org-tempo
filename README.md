## Description

This plugin reimplements completions of org tempo, could custom the
template of keyword prefix.  the original org tempo only use '<' as
keywords prefix.

## Use

``` elisp
(use-package org-tempo
  :load-path "~/.emacs.d/site-lisp/org"
  :config (setq org-tempo-keywords-prefix "#"))
```

## Ref

[org-tempo](https://github.com/emacs-mirror/emacs/blob/3af9e84ff59811734dcbb5d55e04e1fdb7051e77/lisp/org/org-tempo.el)

