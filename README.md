# atom-tic80

<big>Make and run [TIC-80](https://tic80.com/) games in [Atom](https://atom.io/)</big>

----

* Allows you to run and make games within Atom
* Prints TIC's console output in Atom's terminal
* Provides autocomplete and snippets for TIC's API

![Showcase](https://user-images.githubusercontent.com/51688199/91285388-96dee980-e7a6-11ea-840f-44fee158a08a.gif)

## Important information
* Supported TIC-80 versions: >=0.90.0
* In order to get benefit from most of the package features, you need to have [TIC-80 Pro Version](https://github.com/nesbox/TIC-80#pro-version)

## Installation

Either run command:<br/>
* `apm install atom-tic80`

Or:
1. Go to Atom > Settings > Install
2. Search for `atom-tic80`
3. Click "Install"

## Usage

All commands can be ran via [Command Palette](https://flight-manual.atom.io/getting-started/sections/atom-basics/#command-palette). If you open it by pressing `Ctrl+Shift+P` and type `tic80`, you will see all the available commands.

### Run

`Tic80: Run` command simply runs TIC-80. Although, it's not that simple because Atom needs to know how to run it.

Try out the command: if it fails, go to the package settings and set proper path to your TIC-80 executable file.

### Run file

#### Running raw code files

Using `Tic80: Run File` you can make your games right in Atom! Write some code, save it as .lua file (or .js or whatever TIC-80 supports) and press `Ctrl+R` (the command has a handy keybinding!).

After running the command, the essential [cartridge metadata](https://github.com/nesbox/TIC-80/wiki/the-code#cartridge-metadata) will be added at the top of your file if it's not already present.

#### Running .tic files

The same command can also run `.tic` files. However, it's not recommended to edit them using Atom (or any other external text editor) because chances are this action will corrupt the files.

### Project

As an additional feature, with `Tic80: Create Project` command you can pick a folder, choose a language and create a cart in it. The created file will be opened in a new window.

### Terminal

The package can print TIC-80 console output to a terminal within Atom. You can tweak its behavior and properties in the package settings.

![Terminal](https://user-images.githubusercontent.com/51688199/91285403-9b0b0700-e7a6-11ea-9533-67eecaf708c2.png)


### Autocomplete and snippets

The package also includes autocomplete feature for TIC's API and some handy snippets.

![Autocomplete](https://user-images.githubusercontent.com/51688199/91285376-95152600-e7a6-11ea-930d-e2aabddad208.png)

## Changelog

Changelog can be found in the [CHANGELOG](CHANGELOG.md) file.

## License

This project is licensed under the terms of MIT license, See the [LICENSE](LICENSE.md) file for more info.
