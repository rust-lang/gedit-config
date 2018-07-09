# Rust for GEdit

Add syntax highlighting for Mozilla Rust in GtkSourceView (used by GEdit).

__This has been upstreamed into GtkSourceView and is now included in applications like GEdit and GNOME Builder__

If you require a manual installation please follow the directions below.

__Instructions for Ubuntu Linux 12.04+__

1. Close all instances of GEdit

2. Copy the included "share" folder into "~/.local/"

3. Open a shell in "~/.local/share/" and run "update-mime-database mime"

__Instructions for other GNU/Linux distributions__

1. Close all instances of GEdit

2. Obtain super-user access

3. Copy the rust.lang file and place it in /usr/share/gtksourceview-3.0/language-specs/

Example (after extracting the gedit-config-master.zip to the ~/Downloads directory):

> sudo mv /Downloads/gedit-config/share/gtksourceview-3.0/language-specs/rust.lang /usr/share/gtksourceview-3.0/language-specs/

## License

Rust is primarily distributed under the terms of both the MIT license
and the Apache License (Version 2.0), with portions covered by various
BSD-like licenses.

See [LICENSE-APACHE](LICENSE-APACHE), and [LICENSE-MIT](LICENSE-MIT) for details.
