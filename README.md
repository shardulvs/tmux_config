# tmux config

## Reloading the config

After editing `tmux.conf`, reload it without restarting tmux.

From inside tmux, open the command prompt with `prefix` + `:` and run:

```
source-file ~/.config/tmux/tmux.conf
```

From a shell:

```
tmux source-file ~/.config/tmux/tmux.conf
```
