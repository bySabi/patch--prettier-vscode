# patch--prettier-vscode

A shell script for patch [prettier-vscode][prettier-vscode] Visual Studio Code extension in order of integrate [prettier-eslint][prettier-eslint] with [Standard][standard] and [Semistandard][semistandard]

## Usage
1- clone this repo

2- install requested tools

3- patch *std* or *semi*

4- create package or publish it


## CLI Options

```bash
$ ./patch
Usage: ./patch COMMAND
Easy patch prettier-vscode extension

Commands
 std      Patch for "standard"
 semi     Patch for "semistandard"
 publish  Publish extension
 package  Generate VSIX extension

```

## Published extensions using this tool
* [prettier-vscode-standard][prettier-vscode-standard] - prettier OR prettier + standard --fix
* [prettier-vscode-semistandard][prettier-vscode-semistandard] - prettier OR prettier + semistandard --fix

## License

[MIT][mit-license]

[mit-license]:./LICENSE

[prettier-eslint]: https://github.com/prettier/prettier-eslint
[semistandard]: https://github.com/Flet/semistandard
[standard]: https://github.com/standard/standard
[prettier-vscode]: https://github.com/esbenp/prettier-vscode
[prettier-vscode-standard]: https://marketplace.visualstudio.com/items?itemName=bysabi.prettier-vscode-standard
[prettier-vscode-semistandard]: https://marketplace.visualstudio.com/items?itemName=bysabi.prettier-vscode-semistandard
