SublimeLinter-rst
=================

**This package will stop working in SublimeLinter 4.**

Read more about it [here](https://github.com/SublimeLinter/SublimeLinter3/issues/728). If you want to do something about that please get in touch at the [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter3) repo. 


-----


[![Build Status](https://travis-ci.org/SublimeLinter/SublimeLinter-rst.svg?branch=master)](https://travis-ci.org/SublimeLinter/SublimeLinter-rst)

This linter plugin for [SublimeLinter](http://sublimelinter.com) provides an interface to the [docutils' reStructuredText parser](http://docutils.sourceforge.net/docs/dev/hacking.html#id3) built into Sublime Text. It will be used with files that have the “reStructuredText” syntax.

## Installation
SublimeLinter 3 must be installed in order to use this plugin. If SublimeLinter 3 is not installed, please follow the instructions [here](http://sublimelinter.com/en/latest/installation.html).

### Linter installation
Before installing this plugin, you must ensure that `docutils` is installed on your system. To install `docutils`, do the following:

1. Install [Python 3](http://python.org) and [pip](http://www.pip-installer.org/en/latest/installing.html).

1. Install `docutils` by typing the following in a terminal, replacing ‘x’ with the minor version installed on your system: `[sudo] pip-3.x install docutils`

### Plugin installation
Please use [Package Control](https://sublime.wbond.net/installation) to install the linter plugin. This will ensure that the plugin will be updated when new versions are available. If you want to install from source so you can modify the source code, you probably know what you are doing so we won’t cover that here.

To install via Package Control, do the following:

1. Within Sublime Text, bring up the [Command Palette](http://docs.sublimetext.info/en/sublime-text-3/extensibility/command_palette.html) and type `install`. Among the commands you should see `Package Control: Install Package`. If that command is not highlighted, use the keyboard or mouse to select it. There will be a pause of a few seconds while Package Control fetches the list of available plugins.

1. When the plugin list appears, type `rst`. Among the entries you should see `SublimeLinter-rst`. If that entry is not highlighted, use the keyboard or mouse to select it.

## Settings
For general information on how SublimeLinter works with settings, please see [Settings](http://sublimelinter.com/en/latest/settings.html). For information on generic linter settings, please see [Linter Settings](http://sublimelinter.com/en/latest/linter_settings.html).

## Contributing
If you would like to contribute enhancements or fixes, please do the following:

1. Fork the plugin repository.
1. Hack on a separate topic branch created from the latest `master`.
1. Commit and push the topic branch.
1. Make a pull request.
1. Be patient.  ;-)

Please note that modications should follow these coding guidelines:

- Indent is 4 spaces.
- Code should pass flake8 and pep257 linters.
- Vertical whitespace helps readability, don’t be afraid to use it.

Thank you for helping out!
