#### ./a

**当前目录**下的 a 文件夹，或执行当前目录下的 a 文件。

#### ls ../a/b

打印**上级目录**下的 a 文件夹下的 b 文件夹的内容。

#### cd ~

进入 home 目录。

#### chmod 777 /tmp/a.py

将根目录下的 tmp 文件夹中的 a.py 文件的权限更改为 “所有用户可读可写可执行” 。

#### sudo rm -rf /

以最高权限删除系统的**所有**文件。

#### cat ~/*/info.txt

打印用户 home 目录下的 所有下一级文件夹 中的 info.txt 文件的内容。

#### cat 1.txt | grep good

打印当前目录下的 1.txt 文件中所有包含 good 的行。

#### mkdir find . -type d | tail -n 12

创建一个名称为 “当前目录下最后一个文件夹 加上一个2” 的文件夹  
比如当前目录下最后一个文件夹是 a ，那么此命令会创建一个名称为 a2 的文件夹，再次运行会创建一个 a22 文件夹。

#### cat 1.txt 2>/dev/null || touch 2

尝试打印 1.txt 的内容，如果失败（比如文件不存在或者权限不足），那么不显示错误信息，但是创建一个名称为 2 的文件。
