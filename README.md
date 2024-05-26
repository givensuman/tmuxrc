My tmux configuration files.

#### Install tmux

```shell
sudo apt update
sudo apt install tmux
```

#### Clone the repository

```shell
git clone https://github.com/givensuman/tmuxrc
```

#### And pull out what you need

```shell
cat tmuxrc/.tmux.conf >> ~/.tmux.conf
cp tmuxrc/.tmux/plugins/* ~/.tmux/plugins
```

#### Refresh your shell

```
tmux source ~/.tmux.conf
```

![tmux](https://github.com/givensuman/tmuxrc/assets/16063606/a59e3b95-25cb-4ea1-9131-e0913c64c0d0)
