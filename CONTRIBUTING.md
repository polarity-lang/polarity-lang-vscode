# VSCode extension

## Install via the prebuilt plugin

To install the prebuilt `.vsix` extension in your local VSCode environment, download the most recent version of the `polarity-x.x.x.x.vsix` from the `Releases` tab on the homepage of this repository.

The `*.vsix` extension can be installed either from within VSCode, or by invoking the following command on the command line:

```sh
code --install-extension polarity-0.0.1.vsix
```

## Requirements

* [VSCode](https://code.visualstudio.com/Download)
* [Node.js](https://nodejs.org/en/download) and [npm](https://www.npmjs.com/package/npm)
* [vsce](https://www.npmjs.com/package/vsce)

To install `vsce` via `npm`, run:

```sh
npm install -g @vscode/vsce
```

## Develop

Open this folder in VSCode:

```sh
code .
```

Open the "Run and Debug" tab (`Ctrl+Shift+D`).
Select the "Extension" run configuration.

Press `F5` or the "Start Debugging" button in VSCode.

## Package

To package the extension, run:

```sh
vsce package
```

This should create a file named `polarity-0.0.1.vsix`.

## Install

To install the extension in your local VSCode environment, run:

```sh
code --install-extension polarity-0.0.1.vsix
```