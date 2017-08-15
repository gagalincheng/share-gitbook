##使用
gitbook 的基本用法非常简单，基本上就只有两步：
>* 使用 `gitbook init` 初始化书籍目录
>* 使用 `gitbook build` 编译书籍

### gitbook init
执行完产生以下目录

```bash
$ tree share-gitls book/
book
├── README.md
└── SUMMARY.md

0 directories, 2 files
```

`README.md`是对书籍的介绍，`SUMMARY.md`是目录结构。

```
# Summary

* [Introduction](README.md)

```
### gitbook build
在书籍目录创建好之后，执行`gitbook build`会将`SUMMARY.md`里的结构编译成html文件
