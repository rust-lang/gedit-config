#Rust for GEdit

Add syntax highlighting for Mozilla Rust in GtkSourceView (used by GEdit).

__Instructions for Ubuntu Linux 12.04+__

1. Close all instances of GEdit

2. Copy the included "share" folder into "~/.local/"

3. Open a shell in "~/.local/share/" and run "update-mime-database mime"

__Instructions for other GNU/Linux distributions__

1. Close all instances of GEdit

2. Obtain super-user access

3. Copy the rust.lang file and place it in /usr/share/gtksourceview-3.0/language-specs/

Example:

> sudo mv /Downloads/gedit-config/share/gtksourceview-3.0/language-specs/rust.lang /usr/share/gtksourceview-3.0/language-specs/
