# dotfiles-local

John's dotfiles for vim, tmux, git and anything else. Also includes an extension
of [thoughtbot/laptop](https://github.com/thoughtbot/laptop) to make this a
quick way to setup a laptop from scratch.

First time you run, there's a few extra steps needed:

```
curl --remote-name https://raw.githubusercontent.com/thoughtbot/laptop/master/mac
git clone https://github.com/thoughtbot/dotfiles.git ~/dotfiles
git clone https://github.com/jdbann/dotfiles-local.git ~/dotfiles-local
sh mac 2>&1 | tee ~/laptop.log
env RCRC=$HOME/dotfiles/rcrc rcup
laptop
```

After that, you can just run:

```
laptop
```
