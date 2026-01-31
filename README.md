# 个人tmux配置

[参考配置链接](https://think.leftshadow.com/docs/tmux/config/)

## 配置方式

1. 使用`git clone --recurse-submodules https://github.com/Shenliuran/tmux.git`项目克隆到`~/.config`下
2. 执行`ln -s ~/.config/tmux/.tmux.conf ~/.tmux.conf`创建link
3. 使用`git submodule update --remote`更新`tpm`包管理器
4. 执行 `bash ~/.tmux/plugins/tpm/bin/install_plugins`
5. 安装`xsel`工具: `sudo apt install xsel`
