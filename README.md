# Admin Themes

## 分支

- [default](../../tree/default)

## 用法

> 说明：下文中的 `default` 与上一小节中的*分支名*对应

**第一步**

命令行到指定目录

```bash
$ cd path/to/theme/default
```

**第二步**

初始化 git 仓库

```bash
$ git init
```

**第三步**

设置 git 仓库远程地址

```bash
$ git remote add origin https://github.com/ndfront/admin-theme.git
```

**第四步**

拉取远程数据到本地，其中 `default` 为分支名

```bash
$ git pull origin default
```

**第五步**

编辑 path/to/theme/default/scss/index.scss

在 path/to/theme/default/scss/app 中放置其它以“_”开头的业务 scss 文件
