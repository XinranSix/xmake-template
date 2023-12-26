# xmake-template

[xmake](https://xmake.io/#/) 的一个模板，整合了常用了的库并兼容多平台，可以从本项目派生新项目

## 使用

使用命令：

```bash
git clone https://github.com/XinranSix/xmake-template.git
```

将项目克隆下来，libs 目录下存放的是项目依赖的外部库，使用 git 子模块进行维护，将项目克隆下来后要先初始化这些子模块。

## 库列表

项目中大部分库使用 xmake 提供的包管理工具进行维护，少部分库由于不在 xmake 的包管理工具中或 xmake 包管理工具的的库存在问题，采用本地包的方式进行管理，存放在 libs 文件夹中。


