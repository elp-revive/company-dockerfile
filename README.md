[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![JCS-ELPA](https://raw.githubusercontent.com/jcs-emacs/badges/master/elpa/v/company-dockerfile.svg)](https://jcs-emacs.github.io/jcs-elpa/#/company-dockerfile)

# company-dockerfile

[![CI](https://github.com/elp-revive/company-dockerfile/actions/workflows/test.yml/badge.svg)](https://github.com/elp-revive/company-dockerfile/actions/workflows/test.yml)

Add dockerfile keywords to company-mode keywords alist.

## Config

```emacs-lisp
(add-hook 'dockerfile-mode-hook
          (lambda ()
            (setq company-minimum-prefix-length 2)
            (add-to-list 'company-backends #'company-dockerfile))
```
