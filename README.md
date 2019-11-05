[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Marketplace Version](https://vsmarketplacebadge.apphb.com/version/meshredded.robusta.svg "Current Release")](https://marketplace.visualstudio.com/items?itemName=meshredded.robusta)
[![Marketplace Version](https://vsmarketplacebadge.apphb.com/installs/meshredded.robusta.svg "Installs")](https://marketplace.visualstudio.com/items?itemName=meshredded.robusta)
[![CircleCI](https://circleci.com/gh/Meshredded/vscode-robusta/tree/master.svg?style=svg)](https://circleci.com/gh/Meshredded/vscode-robusta/tree/master)
# Robusta for Visual Studio Code
This extension provides full robusta language support for vscode (Code colorization, Formatting, Code execution, Theme, Snippets ...).


# FEATURES
## 1 - Robusta Code Execution :
The extension provides the compile command on right click on .jvs files and run command on clicking on .jar archives.

![](https://user-images.githubusercontent.com/10856604/67438849-e556b100-f5f4-11e9-9364-210ec8e58ccf.png)
![](https://user-images.githubusercontent.com/10856604/67439264-0ff53980-f5f6-11e9-9974-98e51bbefa65.png)

## 2 - Problem Matcher :
The extension provides a problem matcher to detect compilation errors and display them directly on the editor.

![](https://user-images.githubusercontent.com/10856604/67441703-2901e880-f5fe-11e9-912c-ab7046c0a759.png)

## 3 - Code Formatting / Colorization :
The extension provides the robusta language configuration that makes code colorizing possible on vscode and a strong code formatter based on typescript formatter.

![](https://user-images.githubusercontent.com/10856604/67442191-21434380-f600-11e9-82ea-ddd80a693807.gif)

## 4 - File Icon Theme :
The extension provides a set of file icons based on the famous Seti file icon theme.

![](https://user-images.githubusercontent.com/10856604/67438724-8bee8200-f5f4-11e9-94df-dff3d06a3877.png)



## Extension Settings
```json
{
    "robusta.path": "path/to/robusta.jar",
    "robusta.formatOnSave": true,
    "robusta.compileOnSave": false
}
```
> Find out about robusta.jar [here.](https://github.com/Meshredded/robusta)

## License
This software is released under the terms of the MIT license.