<!-- toc -->

# cmd使用教程

## window下递归删除指定文件和文件夹

```cmd
//删除文件
del *.后缀 /s
//删除文件夹
for /r 目录 %a in (文件夹名\) do @if exist "%a" rd /s/q "%a"
```

## tree命令

```cmd
tree
```

