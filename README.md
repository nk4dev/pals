# PALS

PowerShell Alias Manager
## Requirements
- PowerShell 7+
- Node.js 14+
- Git

## Usage
```bash
Usage: pals [options] [command]

PowerShell Alias Manager (Advanced)

Options:
  -V, --version                 output the version number
  -h, --help                    display help for command

Commands:
  add <aliasName> <command...>  Create a new alias (e.g., pals add touch New-Item)
  remove|rm <aliasName>         Remove an alias
  list|ls                       List aliases
  template                      Template utilities
  config                        Displays the current settings and destination path
  path                          Display command to add the directory to PowerShell PATH
  help [command]                display help for command
```

default save directory is `$HOME/.ps-aliases`

## Installation
pals is not yet published npm package. You can install it from source by cloning the repository and running `npm install` in the root directory.

```bash
git clone https://github.com/yourusername/pals.git
cd pals
npm install
npm link
```

## Using Libraries
commander

## Author
[@nk4dev](https://github.com/nk4dev)
