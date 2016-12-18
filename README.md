# Sulu
## Hackable file manager on Linux, Windows and OS X

## Prototype at development! Here is a lot of work todo!
https://discord.gg/rX7hu3D discord chat.


[![Dependency Status](https://david-dm.org/sulu-one/sulu.svg)](https://david-dm.org/sulu-one/sulu) 
[![devDependency Status](https://david-dm.org/sulu-one/sulu/dev-status.svg)](https://david-dm.org/sulu-one/sulu#info=devDependencies)  

[![Codacy Badge](https://www.codacy.com/project/badge/e5ce84ae276649d5ab61f4f1b264e5e0)](https://www.codacy.com/app/stephanahlf/sulu)  

## Screenshot
![Screenshot](/demo.gif)  

## Short cuts

(so far) check console (F12) to get a list full list

- press "tab" to "toggleActiveFileSystemView"
- press "down" to "makeNextRowActive"
- press "up" to "makePreviousRowActive"
- press "enter" to "enterActiveRow"
- press "backspace" to "navigateBackToParentFolder"
- press "space" to "selectActiveRow"
- press "esc" to "unselectAllRows"
- press "ctrl+a" to "selectAll"
- press "ctrl+shift+a" to "invertSelection"
- press "ctrl+s" to "selectByFileExtension"
- press "ctrl+b" to "toggleBookmark"
- press "f5" to "copy"
- press "f12" to "toggleDevTools"
- press "ctrl+alt+left" to "historyJumpBackward"
- press "ctrl+alt+right" to "historyJumpForward"
- press "right" to "changeDirectory"
- press "f7" to "createFolder"
- press "del" to "moveToTrash"
- press "ctrl+r" to "reload"
- press "f5" to "reload"
- press "ctrl+f5" to "reloadHard"
- press "ctrl+e" to "showItemInFolder"
- press "ctrl+enter" to "openShell"

## [Contributing](/CONTRIBUTING.md)

```bash


# installation 

git clone https://github.com/sulu-one/sulu.git;
cd sulu;
npm link .;
npm install;
cd app;
npm install;
bower install;

# run

sulu; 

```

## [API](./api.md)

## [License](/LICENSE.md)
Copyright (c) 2015-2017 Stephan Ahlf <stephan.ahlf@gmail.com>  
This software is licensed under MIT.  

[<img src="https://s-a.github.io/license/img/mit.svg" />](/LICENSE.md#mit "Massachusetts Institute of Technology (MIT)")