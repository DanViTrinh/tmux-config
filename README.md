# Tmux-config

My simple tmux config

## Inspired by  

Dreams of code: <https://www.youtube.com/watch?v=DzNmUNvnB04&t=613s>

## Requirements

You need to tell tmux to use unicode by running tmux -u. This can be aliased  
in you zshrc or bashrc with. This is to get nerdfont etc working.

```bash
alias tmux='tmux -u'
```

clone tpm
```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

Then install plugins with:
Press prefix + I (capital i, as in Install) to fetch the plugin. 
