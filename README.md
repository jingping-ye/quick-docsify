# quick-docsify

> 基于 docsify 的快速文档系统构建框架

## 第一步：安装 docsify

```bash
# 安装docsify-cli
npm install docsify-cli -g

# 启动本地服务
docsify serve
```

## 第二步：删除不必要文件

1. 首先认识一下当前框架的目录结构

```text
|-- article 示例文件，[可删除]
|-- _coverpage.md 封面内容
|-- _navbar.md 顶部导航导航栏配置内容
|-- _sidebar.md 左侧侧边导航栏配置内容
|-- .nojekyll 防止github page 忽略下划线文件
|-- 快速上手.md 示例文档 [可删除]
|-- index.html 入口文件
|-- README.md 示例文档 [可删除]
```

2. 酌情删除或修改

## 第三步：配置相关内容

包括以下几个文件:`_coverpage.md`、`_sidebar.md`、`_navbar.md`

更多配置请查看`index.html`文件，所有的配置几乎都集中在 index.html 文件中。

## 更多关于 docsify 请参考以下链接:

- [docsify 中文文档](https://jingping-ye.github.io/docsify-docs-zh/#/)
- [docsify 官方文档](https://docsify.js.org/)
