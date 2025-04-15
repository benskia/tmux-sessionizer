# TMUX Sessionizer

A fork of ThePrimeagen's tmux-sessionizer script. Provides a selection of dirs
in which to start a tmux session.

## Usage

```bash
tmux-sessionizer [<partial name of session>]
```

if you execute tmux-sessionizer without any parameters it will assume FZF and
try to fuzzy find over a set of directories.

TODO: waiting on that directory list to be dynamic :) (go a head make pr if you want)
