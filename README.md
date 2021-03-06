# homework

This project is using [README Driven Development](http://tom.preston-werner.com/2010/08/23/readme-driven-development.html) to document the requirements of the application. The functionality will match the documentation at version 1.0.0. Until then, consider the documentation unreliable.

**Note** when you run `homework init`, you will see `[conflict]` appear in the console. There is no conflict, but is due to a plugin and will be fixed before 1.0.

## Description

homework is a tool for managing homework assignments for a primarily code-based curriculum. It was developed for and is used by the courses at [The Iron Yard](http://theironyard.com).

Run `homework help` to get a list of available commands.

## Installation

The primary way to install `homework` is using npm:

```sh
$ npm install -g theironyard/homework
```

For alternative installation methods, see [INSTALL.md](INSTALL.md)

## Configuration

homework is configurable via command line switches, environment variables, user config files, or a global config file.

See [homework-config](doc/guides/config.md) for more details.

## Autocompletion
Add `homework setup` to your shell to enable autocompletion.

```sh
$ echo 'eval "$(homework setup -)"' >> ~/.bash_profile
```

**Ubuntu Desktop note**: Modify your `~/.bashrc` instead of `~/.bash_profile`.

**Zsh note**: Modify your `~/.zshrc` file instead of `~/.bash_profile`.

## Credits

homework is significantly inspired by [npm](https://github.com/npm/npm).
