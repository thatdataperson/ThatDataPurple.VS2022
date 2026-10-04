# ThatDataPurple.VS2022
A purple theme for Visual Studio 2022, Visual Studio 2026 and SQL Server Management Studio 22 in the That Data Person brand colours, by That Data Person Limited.

## Screenshot
![Screenshot of ThatDataPurple theme applied to Visual Studio 2026](https://github.com/thatdataperson/ThatDataPurple.VS2022/blob/main/images/ThatDataPurple.preview.png?raw=true)

## 2026 refresh
The theme now follows the That Data Person branding: a deep brand-dark (`#0D0629`) workbench, brand purple (`#4320CC`) for the status bar, selections and buttons, and light purple (`#9580E6`) for focus and accents.

Every text colour meets WCAG 2.2 AA (at least 4.5:1) against the editor background, the current-line highlight and the selection, and focus indicators meet 3:1. Syntax colours are separated by hue *and* lightness, and comments, parameters and control-flow keywords are also italic, so they don't rely on colour alone. The colours are generated from the shared palette in [ThatDataPurple](https://github.com/thatdataperson/ThatDataPurple/tree/main/palette); see its contrast report for the numbers.

## Supported Versions
- Visual Studio 2022
- Visual Studio 2026
- SQL Server Management Studio 22 (and 21)
- The same extension installs on all of these
- Visual Studio 2019 is supported in [ThatDataPurple.VS2019](https://github.com/thatdataperson/ThatDataPurple.VS2019)
- Visual Studio Code is supported in [ThatDataPurple.VSCode](https://github.com/thatdataperson/ThatDataPurple.VSCode)

## Install
- Download the version you need from the Visual Studio Marketplace
- Run the installer
- Apply the theme
  - Tools > Options > Environment > General > Color Theme > ThatDataPurple.VS2022
  - In Visual Studio 2026 and SSMS 22: Tools > Theme > ThatDataPurple.VS2022

### SQL Server Management Studio
Close SSMS (including any background MSBuild processes it leaves running), then double-click the downloaded `.vsix` and pick SQL Server Management Studio in the installer.

The query window's status bar colour is an SSMS setting rather than part of the theme, so it stays yellow by default. To match it, search Tools > Options for "status bar" and set the connection colours to brand purple (`#4320CC`).

## Uninstall
- Extensions > Manage Extensions > Installed > ThatDataPurple.VS2022 > Uninstall

## Download
[ThatDataPurple.VS2022](https://marketplace.visualstudio.com/items?itemName=ThatDataPerson.themeThatDataPurpleVS2022) is published on Visual Studio Marketplace.
