# U盘写保护

用win32烧录Ubuntu镜像时，显示U盘具有写保护。

`win+R`输入cmd，进入dos界面

依次输入以下命令

```shell
diskpart
list disk
select disk 1
clean
create partition primary
```