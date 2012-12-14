pastefire-client
================

A Windows client of pastefire using AutoHotkey as a backend, and a simple linux
client. Pastefire is an iPhone/iPad app for copying text from your computer to
your iDevice.

Windows version
---------------

Tested on Windows XP with AutoHotkey v1.1.02.01

### Requirements

- You need the `pastefire.ahk`-file from above.
- You need to install [AutoHotkey](http://www.autohotkey.com).
- Make AutoHotey the default program for `ahk`-files (AutoHotkey should
  ask for that on installation)

### Preparations

 1. Open `pastefire.ahk` in a text editor (e.g. Notepad)
 2. Replace `my@email.adress` with your email adress
 3. Replace `myPassword` with your Pastefire password
 4. Save the file.
 5. (Optional) Make a link to the file in `Autostart` in the "Start"-menu to
    make the program start automatically.

### Usage

To start the program simply double click `pastefire.ahk`. There should be an
AutoHotkey icon in the task bar.

This will create the shortcut `Ctrl-Alt-C` for copying to pastefire.
