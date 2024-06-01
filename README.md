My tmux configuration files.

#### Install tmux

```shell
sudo apt update
sudo apt install tmux
```

#### Install TPM

```shell
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

#### Clone the repository

```shell
git clone https://github.com/givensuman/tmuxrc
```

#### And pull out what you need

```shell
cp tmuxrc/.tmux.conf ~/.tmux.con
```

#### Refresh your shell

```
# You will need to install any plugins with <Prefix>I
# which after sourcing below will be Ctrl+Space followed by Shift+i
tmux source ~/.tmux.conf
```

![tmux](https://github.com/givensuman/tmuxrc/assets/16063606/a59e3b95-25cb-4ea1-9131-e0913c64c0d0)
