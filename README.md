# Docsify

> An awesome project.

## 概述
Docsify 可以快速帮你生成文档网站。不同于 GitBook、Hexo 的地方是它不会生成静态的 `.html` 文件，所有转换工作都是在运行时。如果你想要开始使用它，只需要创建一个 `index.html` 就可以开始编写文档并直接部署在 GitHub Pages。

查看 [官方文档][docsify] 了解详情。

[docsify]: https://docsify.js.org/#/zh-cn/ "Docsify 官方在线文档"

## 快速开始

### 初始化项目
!> 本仓库不需要该步骤

如果想在项目的 `./docs` 目录里写文档，直接通过 `init` 初始化项目。

```bash
docsify init ./docs
```

### 开始写文档

初始化成功后，可以看到 `./docs` 目录下创建的几个文件

- `index.html` 入口文件
- `README.md` 会做为主页内容渲染
- `.nojekyll` 用于阻止 GitHub Pages 忽略掉下划线开头的文件

直接编辑 `docs/README.md` 就能更新文档内容，当然也可以[添加更多页面](https://docsify.js.org/#/zh-cn/more-pages)。

### 本地预览

通过运行 `docsify serve` 启动一个本地服务器，可以方便地实时预览效果。默认访问地址 `http://localhost:3000` 。

```bash
docsify serve docs
```

## 优秀教程
1. [docsify 安装与配置](https://juejin.cn/post/7236694100216381499 "稀土掘金")
2. [docsify的配置+全插件列表](https://xhhdd.cc/index.php/archives/80/ "腾讯开发者社区：https://cloud.tencent.com/developer/article/2177009")