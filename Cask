(package "terminal-here" "0.1" "Run an external terminal in current directory")

(files "terminal-here.el")

;; Tell Cask to add package information to this file (so that we can have a
;; single file package).
(package-file "terminal-here.el")

(source gnu)

(development
 (depends-on "ert-runner")
 (depends-on "el-mock")

 ;; For testing defcustom types
 (depends-on "validate"))
