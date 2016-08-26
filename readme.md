# Kirby Boiler Readme

![Version](https://img.shields.io/badge/version-1.0.0-green.svg) ![License](https://img.shields.io/badge/license-MIT-green.svg) ![Kirby Version](https://img.shields.io/badge/Kirby-2.0%2B-red.svg)

*Version 1.0.0*

Write a short description of what the plugin is about. If you can, add an animated gif or screenshot. It will probably make more people use your plugin.

![Screenshot](https://placeholdit.imgix.net/~text?txtsize=38&txt=Screenshot&w=888&h=150&txttrack=0)

## Installation

Use one of the alternatives below.

### 1. Kirby CLI

If you are using the [Kirby CLI](https://github.com/getkirby/cli) you can install this plugin by running the following commands in your shell:

```
$ cd path/to/kirby
$ kirby plugin:install username/plugin-name
```

### 2. Clone or download

1. [Clone](https://github.com/username/plugin-name.git) or [download](https://github.com/username/plugin-name/archive/master.zip)  this repository.
2. Unzip the archive if needed and rename the folder to `plugin-name`.

**Make sure that the plugin folder structure looks like this:**

```
site/plugins/plugin-name/
```

### 3. Git Submodule

If you know your way around Git, you can download this plugin as a submodule:

```
$ cd path/to/kirby
$ git submodule add https://github.com/username/plugin-name site/plugins/plugin-name
```

## Setup

### 1. Blueprint

To make it work as expected, add the following code to your blueprint:

```
fields:
  yourfield:
    title: Your Field
    type: yourfield
```

### 2. Add JS to your footer

Add the following code to your `footer.php` snippet:

```php
echo js('assets/plugins/plugin-name/js/script.js');
```

## Usage

Describe how to use this plugin. Text, images, videos etc is good here.

## Options

### A plugin option

Describe the option and always set the second argument as the default value.

```
c::set('plugin.your.plugin.option', 'Default value');
```

## Changelog

**1.0.0**

- Fixed the `readme.md` file 

**0.5.1**

- Some important change
- Initial release

## Todo

- [ ] An uncompleted task
- [x] ~~A completed task~~

## Requirements

- [**Kirby**](https://getkirby.com/) 2.0+

## Disclaimer

This plugin is provided "as is" with no guarantee. Use it at your own risk and always test it yourself before using it in a production environment. If you find any issues, please [create a new issue](https://github.com/username/plugin-name/issues/new).

## License

[MIT](https://opensource.org/licenses/MIT)

## Credits

- [Jens Törnell](https://github.com/jenstornell)
- [Mathieu Etienne](https://github.com/Thiousi/)
- [Flo Kosiol](https://github.com/flokosiol)