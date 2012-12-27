# How to use

## Install Sublime Text 2
* [Stable](http://www.sublimetext.com/2)
* [Dev](http://www.sublimetext.com/dev)
* [Nightly](http://www.sublimetext.com/nightly)

## Install [Package Control](http://wbond.net/sublime_packages/package_control/installation)

## Install [Node.js](http://nodejs.org/download/)
For [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter).

## Git Clone SublimeText2UserSettings

## Make symblolic link
* Windows

  Run Command Prompt as Administrator

  ```
> cd PATH\TO\PACKAGES
> rd /s /q User
> mklink /d User PATH\TO\SublimeText2UserSettings
  ```

* Mac/Linux

  ```
$ cd PATH/TO/PACKAGES
$ rm -rf User
$ ln -s PATH/TO/SublimeText2UserSettings User
  ```

## Edit Preferences.sublime-settings
Uncomment machine specific settings.
