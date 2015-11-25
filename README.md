# Sublime Text Preferences

_All settings are the **User** version, as the **Default** version gets overridden when updating._

__Keyboard Shortcuts: [Default (Linux).sublime-keymap][1]__

* Keyboard shortcut to reveal the current file in the sidebar

__Package Control Settings: [Package Control.sublime-settings][3]__

* A list of the packages installed through [Package Control](http://wbond.net/sublime_packages/package_control)

__User Preferences: [Preferences.sublime-settings][4]__

* An example of a project setup, inluding what to ignore

## Install (Linux)

```sh
mkdir -p ~/.config/sublime-text-3/Packages;
mkdir -p ~/.config/sublime-text-3/Installed\ Packages;

git clone --recursive https://github.com/matthieusieben/Sublime-Text-Preferences.git ~/.config/sublime-text-3/Packages/User;
wget https://packagecontrol.io/Package%20Control.sublime-package -O ~/.config/sublime-text-3/Installed\ Packages/Package\ Control.sublime-package;
```

[1]: https://github.com/matthieusieben/Sublime-Text-Preferences/blob/master/Default%20(Linux).sublime-keymap
[2]: https://github.com/matthieusieben/Sublime-Text-Preferences/blob/master/Fetch.sublime-settings
[3]: https://github.com/matthieusieben/Sublime-Text-Preferences/blob/master/Package%20Control.sublime-settings
[4]: https://github.com/matthieusieben/Sublime-Text-Preferences/blob/master/Preferences.sublime-settings
