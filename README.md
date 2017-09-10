![tool](images/logo.png)![plus](images/plus.png)![react](images/react.png) 
# react-typescript-toolbox

Extension to create TypeScript React Components from Visual Studio Code explorer menu.

## Features

Create a React Component with a Test and a Less file from the Visual Studio Code Explorer Contextmenu.

![tool](images/showcase.gif)

> Tip: Rightclick in Visual Studio Code Explorer and > Generate Component.

> Tip: Use the settings.json to disable test generation or changing the stylesheet type.

## Requirements

This extension has no dependencies to other extensions. Maybe node.js installed ist required!

## Extension Settings

Available Settings since 0.6:

* `reactTypeScriptToolbox.stylesheet`: `('none' | 'less' | 'css' | 'sass')`
* `reactTypeScriptToolbox.test`: `(true | false)`

## Known Issues

I currently don't know why my Default Settings are not writting in the user/settings.json file on install. But they work if you add them to any setting.json file (Workspace or User). Working on this, or if you can help me, feel free to write a mail!

## Release Notes

### 0.6.0

Add configuration for stylesheet and test.

### 0.5.0

Create a TypeScript React Component with Test and Less file from Contextmenu.

-----------------------------------------------------------------------

## Upcoming! Features

- Use UserConfiguration to:
  - use tabs or spaces for indentation
  - choose if folder and file are lowercase

### For more information

* [Github](https://github.com/Sly321/react-typescript-toolbox)
* Any ideas? Mail me: liebigs@gmail.com