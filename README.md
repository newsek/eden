# This is a forked/updated version of flyingmachine/emacs-for-clojure
Supports Clojure & Common Lisp development

## Installing

1. Close Emacs.
2. Delete `~/.emacs.d/*` if they exist
3. Copy the contents of eden to `~/.emacs.d/*`
4. Edit `~/.emacs.d/init.el` to change the Common Lisp compiler installation path (eg. `/usr/local/bin/sbcl`)
5. Create the file `~/.lein/profiles.clj` and add this
   line to it:

```clojure
{:user {:plugins [[cider/cider-nrepl "0.15.0"]]}} 
```

Then open Emacs.
Enjoy!

