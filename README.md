# gtk-theme-breath

GTK theme forked from [breeze-gtk](https://quickgit.kde.org/?p=breeze-gtk.git) to match the colors of Plasma 5 maia theme

GTK2 theme made by [scionicspectre](https://github.com/scionicspectre/BreezyGTK), and colors changed too.

The dark theme is not ported. And won't be installed.

# Requirements

- GTK+ 3.16
- Pixmap/Pixbuf theme engine for GTK 2

# Install instructions
If your distribution doesn't provide a package, you can install the theme system-wide by copying it to the appropriate directory, usually "/usr/share/themes".
```
find Breath-gtk -type f -exec install -Dm644 '{}' "$pkgdir/usr/share/themes/{}" \;
```

To install only for the current user, copy the files to "~/.themes".

To set the theme in Plasma 5, install kde-gtk-config and use System Settings > Application Style > GNOME Application Style.
Also make sure to disable "apply colors to non-Qt applications" in System Settings > Colors > Options.
