# Automatic Package Reloader

Sublime Text package developers may find themselves have to close and re-open
ST multiple times when developing a package since ST doesn't reload all the
submodules of a package when the files are edited. This tiny package helps in
reloading the package without the need of reopening ST. The reloading order
of the modules is in the exact same order as if they are loaded by Sublime
Text.

### Installation

[Package Control](https://packagecontrol.io/) please.

### Usage

To reload the package in the current window, use `Automatic Package Reloader: Reload Current Project`.

To activate reload on saving a `*py` file, use `Automatic Package Reloader: Toggle Reload On Save`.
Package Reloader will guess the package name from the file path in order to reload the submodules
and to reload the package.

The console panel will be shown when reloading fails, this behavior can be modified by
the settings.

![](shot.png)


### Credits
This is derived from the [code](https://github.com/divmain/GitSavvy/blob/599ba3cdb539875568a96a53fafb033b01708a67/common/util/reload.py) of Eldar Abusalimov.
