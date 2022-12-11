## tja-syntax-kate
TJA language syntax for Taiko no Tatsujin charts. To be used with editors supporting KSyntaxHighlighting like [Kate](https://kate-editor.org/), KWrite, KDevelop, etc.

![](https://github.com/KatieFrogs/tja-syntax-kate/raw/main/screenshot.png)

### Install
Save the file [tja.xml](https://github.com/KatieFrogs/tja-syntax-kate/raw/main/tja.xml) to the custom syntax directory appropriate for your platform.

Platform | Syntax directory
-------- | ----------------
Windows  | `%USERPROFILE%\AppData\Local\org.kde.syntax-highlighting\syntax\`
Linux    | `$HOME/.local/share/org.kde.syntax-highlighting/syntax/`
Flatpak  | `$HOME/.var/app/org.kde.kate/data/org.kde.syntax-highlighting/syntax/`
Snap     | `$HOME/snap/kate/current/.local/share/org.kde.syntax-highlighting/syntax/`
macOS    | `$HOME/Library/Application Support/org.kde.syntax-highlighting/syntax/`

If the directories do not exist, create them. Restart the editor and the syntax highlighting will be available when you open a TJA file or by selecting it in the status bar.
