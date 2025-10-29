# stree-windows

Windows command to open SourceTree from the command line.

## Installation

Download and run the latest MSI installer from the [Releases](../../releases) page.

After installation, you can use the `stree` command from any command prompt or PowerShell window.

## Usage

```cmd
stree [directory]
```

- If no directory is specified, opens the current directory in SourceTree
- If a directory is specified, opens that directory in SourceTree
- If a file is specified, opens the containing directory in SourceTree

## Credits

Thanks to the article by [arlol](https://arlol.github.io/articles/2016-01-28-windows-cmd-open-sourcetree-current-directory.html) for the original implementation.

## Requirements

- SourceTree must be installed on your system
- Git must be installed and available in PATH
