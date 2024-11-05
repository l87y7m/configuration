# Configuration

## Overview

Preferences for:

- Azure Data Studio
- Git
- Visual Studio Code

## Usage

### Complete values

1. Clone and open this repository with [Visual Studio Code](https://code.visualstudio.com/).
1. Install the recommended extensions coming from .\\.vscode\extensions.json
1. Edit gitconfig.txt with your personal Git config values.
   1. Set the user name
   1. Set the user email.
1. _If on Windows, uncomment the difftool and mergetool lines in gitconfig.txt._

### Place files

1. Create symbolic link for Git settings and ignore.

   - Windows Command Prompt

   ```cmd
   mklink /H %HOMEPATH%\.gitconfig .\gitconfig.txt
   mklink /H %HOMEPATH%\.gitignore .\gitignore.txt
   ```

1. Create symbolic link for Visual Studio Code settings and keyboard shortcuts.

   - Windows Command Prompt

   ```cmd
   mklink /H %HOMEPATH%\AppData\Roaming\Code\User\settings.json .\vscode-settings.json
   mklink /H %HOMEPATH%\AppData\Roaming\Code\User\keybindings.json .\vscode-keybindings.json
   ```

1. Create symbolic link for Azure Data Studio settings and keyboard shortcuts.

   - Windows Command Prompt

   ```cmd
   mklink /H %HOMEPATH%\AppData\Roaming\azuredatastudio\User\settings.json .\ads-settings.json
   ```
