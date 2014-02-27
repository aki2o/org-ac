[Japanese](https://github.com/aki2o/org-ac/blob/master/README-ja.md)

# What's this?

This is a extension of Emacs that provide auto-complete sources for org-mode.  
You'll be able to use auto-complete as substitute for pcomplete which is bound to M-TAB.  

# Demo

[demo](image/demo.gif)

# Install

### If use package.el

2014/02/27 Now application

### If use el-get.el

2014/02/27 Now application

### If use auto-install.el

```lisp
(auto-install-from-url "https://raw.github.com/aki2o/org-ac/master/org-ac.el")
```
-   In this case, you need to install each of the following dependency.

### Manually

Download org-ac.el and put it on your load-path.  
-   In this case, you need to install each of the following dependency.

### Dependency

-   [auto-complete-pcmp.el](https://github.com/aki2o/auto-complete-pcmp/master/auto-complete-pcmp)
-   [log4e.el](https://github.com/aki2o/log4e)
-   [yaxception.el](https://github.com/aki2o/yaxception)

# Configuration

```lisp
(require 'org-ac)

;; Make config suit for you. About the config item, eval the following sexp.
;; (customize-group "org-ac")

(org-ac/config-default)
```

# Tested On

-   Emacs &#x2026; GNU Emacs 24.3.1 (i686-pc-linux-gnu, GTK+ Version 3.4.2) of 2013-08-22 on chindi02, modified by Debian
-   auto-complete-pcmp.el &#x2026; 0.0.1
-   log4e.el &#x2026; 0.2.0
-   yaxception.el &#x2026; 0.1

**Enjoy!!!**
