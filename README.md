ExtEdit
=======

ExtEdit is a Thunderbird/Icedove extension to allow editing an email in an
external editor, such as Vim or Emacs.

It is based on
[Alexandre Feblot's External Editor extension](http://globs.org/articles.php?lng=en&pg=2)
and updated by [Brian M. Carlson](https://github.com/bk2204/extedit).

To build, simply type `make`.

Installation
------------

Either download the XPI from the
[releases](https://github.com/ianw/extedit/releases) or make it from
source.

In thunderbird, go `Tools -> Add-Ons -> Extensions` and select the
gear to install.  Restart as required.  You can update preferences
here, such as the path to the editor.

When editing an email, you will have `Tools -> Edit in External
Editor`.  You can also right-click on the toolbar and `Customize` to
add a button, or use the `ctrl-E` shortcut.

Development
-----------

To use a development version, clone the git tree, then place a file
called `{ca8dd6ef-b3ce-4175-94fd-0eca45382519}` in your profile
extension directory (`~/.thunderbird/xxxxxxxx.default/extensions`)
that contains just the path to the extension directory.

`Tools -> Developer Tools -> Error Console` can then be helpful for
diagnosing issues.

License
-------

ExtEdit is licensed under your choice of the Mozilla Public License, version 1.1
or the GNU General Public License, version 2 or later.

Contributing
------------

Pull requests are welcome.  The standard is to use hard tabs, aligned at four
spaces.  The current codebase is moving in that direction, even if it isn't
there yet.

If you're submitting code, please sign off your work in compliance with the
Developer's Certificate of Origin, version 1.1.
