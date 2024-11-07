[![Melpa Status](http://melpa.org/packages/ivy-smex-badge.svg)](http://melpa.org/#/ivy-smex)
[![Melpa Stable Status](http://stable.melpa.org/packages/ivy-smex-badge.svg)](http://stable.melpa.org/#/ivy-smex)

# Use Ivy completion with Smex command matching

*NOTE: This package is redundant, given `counsel-M-x`, but I'm leaving it here anyway.*

[Smex](https://github.com/nonsequitur/smex) has really nice handling
of command histories, favouring commands which have been executed most
frequently in the past. This package provides an
[Ivy](https://github.com/abo-abo/swiper) interface to those internals
via the `ivy-smex` command, which is meant as a replacement for
`execute-extended-command` or `smex`:

This package was inspired by - and based in part on -
[helm-smex](https://github.com/ptrv/helm-smex).

## Installation

### Manual

Ensure `ivy-smex.el` is in a directory on your load-path, and
add the following to your `~/.emacs` or `~/.emacs.d/init.el`:

```elisp
(require 'ivy-smex)
(global-set-key (kbd "M-x") 'ivy-smex)
```

### MELPA

If you're an Emacs 24 user or you have a recent version of
`package.el` you can install `ivy-smex` from the
[MELPA](http://melpa.org) repository. The version of
`ivy-smex` there will always be up-to-date.

To make `ivy-smex` your default `M-x` command, add the following to
your `~/.emacs` or `~/.emacs.d/init.el`:

```elisp
(global-set-key (kbd "M-x") 'ivy-smex)
```

## About

Author: Steve Purcell <steve at sanityinc dot com>

Homepage: https://github.com/purcell/ivy-smex

This little library was extracted from the author's
[full Emacs configuration](https://github.com/purcell/emacs.d), which
readers might find of interest.

<hr>

[💝 Support this project and my other Open Source work](https://www.patreon.com/sanityinc)

[💼 LinkedIn profile](https://uk.linkedin.com/in/stevepurcell)

[✍ sanityinc.com](http://www.sanityinc.com/)
