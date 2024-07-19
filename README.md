# autovenv

This plugin adds `autovenv` functionality to oh-my-zsh.
It will automatically activate a virtualenv if it finds one in the current working directory.
If not found, it will look in its parent directories all the way to the root (excluding the root).

To use, add `autovenv` to the list of plugins in your .zshrc file:

```
plugins=(... autovenv)
```

## Configuration

By default `autovenv` will look for a `.venv` in the each directory.
If you want to change this behavior, you can set the `AUTOVENV` variable in your .zshrc file:

```
AUTOVENV=.env
```
