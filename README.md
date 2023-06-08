# Ship Post Studios: Website Source Code

_Crafting dogwater experiences since April 2069._

<br>

## Workflow Config

### VSCode Extensions

-   [Prettier Formatter for Visual Studio Code](vscode:extension/esbenp.prettier-vscode)

<br>

### .vscode/settings.json

-   Prettier formats on save, using the VSCode Extension
    [Prettier Formatter for Visual Studio Code](vscode:extension/esbenp.prettier-vscode)

<br>

### .prettierrc.json

-   Only files with a pragma (comment containing `@format`) are formatted on save
-   Absence of a pragma is used to manually format some files
