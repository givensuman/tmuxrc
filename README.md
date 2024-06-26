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
cp tmuxrc/.tmux.conf ~/.tmux.conf
```

#### Refresh your shell

```
# You will need to install any plugins with <Prefix>I
# which after sourcing below will be Ctrl+a followed by Shift+i
tmux source ~/.tmux.conf
```

![Screenshot from 2024-06-04 08-09-13](https://github.com/givensuman/tmuxrc/assets/16063606/c1e5ec9e-d6ce-4dbd-b401-411a4741fc39)

