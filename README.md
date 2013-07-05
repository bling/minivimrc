# minivimrc

super tiny vimrc with very few settings set, and with some profiling mappings to make it easier to troubleshoot plugins

# install

create a tiny shim as your `~/.vimrc`

```
set rtp+=~/path/to/minivimrc
source ~/path/to/minivimrc/vimrc
```

# profiling

pathogen is already included in the `autoload` folder, so you just need to add the relevant plugins you want to profile
into the `bundle` folder.

to start profiling, execute `<leader>DD`.
to finish profiling, exit vim, and write to a `profile.log` file, use `<leader>DQ`.
