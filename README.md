Library_Services
================

Some workflows making Finder, Terminal and text handling better on OSX.

Enable these by copying them to ~/Library/Services and restart the
related apps. Enable/Disable them or create keyboard shortcuts for them in
`System Preferences > Keyboard > Keyboard Shortcuts > Services`.

Most of these create new entries in the Right-click (contextual) menu of
an application. They are editable using Automator.

### Copy Path To Clipboard.workflow

Takes files/folders in Finder and copies the POSIX path to the clipboard
for pasting into Terminal, etc.

### Markdown Preview.workflow

Takes selected text (Markdown formatted) in any application, and displays
it in a web browser.
[Markdown.pl](http://daringfireball.net/projects/markdown/) included.

### Markdown Selected.workflow

Takes selected text (Markdown formatted) in any application and replaces
it with the HTML equivalent.

### New File.workflow

Right click a folder in Finder to create a new file ( _Untitled.txt ).
I've always found it odd that Finder let's you create a new
folder, but not a new file...

### Open In Terminal.workflow

Right click a folder in Finder to open that folder (cd into it) in a new
Terminal window.

### Word Count.workflow

Perform a word count of selected text.

Contributing
============

Feel free to fork and submit pull requests, or simply create a
[new issue here](https://github.com/Andyvanee/Library_Services/issues)
