# Ubuntu安装与卸载命令及Vim常用命令

安装

```
sudo apt install ..
```

安装.deb文件

```shell
sudo dpkg -i *.deb
```

卸载

```sh
sudo apt-get --purge remove <package>	
```

Vim常用命令

- `i`:编辑模式
- `:q`:不保存退出
- `:wq`:保存退出
- `:!q`:强制退出
- `:!wq`:强制保存退出
- `esc`:退回到命令模式