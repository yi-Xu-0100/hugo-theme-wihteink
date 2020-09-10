## Hugo-Theme-WhiteInk

[![workflows status](https://github.com/yi-Xu-0100/hugo-theme-whiteink/workflows/Demo/badge.svg)](https://github.com/yi-Xu-0100/hugo-theme-whiteink/actions?query=workflow%3ADemo)
[![GitHub last commit](https://img.shields.io/github/last-commit/yi-Xu-0100/hugo-theme-whiteink)](https://github.yixuju.cn/hugo-theme-whiteink/)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/yi-Xu-0100/hugo-theme-whiteink)](https://github.com/yi-Xu-0100/hugo-theme-whiteink/releases)
[![LICENSE](https://img.shields.io/github/license/yi-Xu-0100/hugo-theme-whiteink)](./LICENSE)

[逸絮居](https://www.yixuju.cn/)的主题, 样式灵感来自 [hexo-theme-Aath](https://github.com/lewis-geek/hexo-theme-Aath).

内容来自[逸絮居](https://www.yixuju.cn/)

示例站点：<https://github.yixuju.cn/hugo-theme-whiteink>

## 特点

### 标头

+ 根据设置显示菜单选项。
+ 适配移动端，给出菜单按钮。

### 框架布局

+ 包含两个部分，左侧为主体内容部分，右侧为个人信息部分。
+ 左侧主要展示文章内容或者文件列表结构。
+ 右侧包含一个搜索框，个人头像，个人简介，和目录。

### 脚标

+ 包含版权信息和备案信息。

## 待开发

+ 标头菜单有多级菜单。
+ 脚标添加 `rss` 和社交图标。
+ 修复 #11 （更新 updated_at 为官方的 lastmod）
+ 完成 #10 （脚本修改时区问题）
+ 完成 #8 （修改归档标签带有角标）
+ 修复 #7 （修复没有下一页 bug）
+ 修复 #6 （修复首页显示文章顺序为最新发布为最先）

## 个人测试

``` bash
git clone --depth=1 https://github.com/yi-Xu-0100/hugo-theme-whiteink.git
cd exampleSite/
hugo server --watch
```

测试站点访问：<http://localhost:1313/hugo-theme-whiteink>

## License

+ [MIT](./LICENSE)

## 更新日志

### v0.0.7

+ 更新主分支名为 main
+ 修复 action 版本和分支
+ 修复 #9 （修改首页日期为最新更新日期）

<details>
<summary>展开查看</summary>

### v0.0.6

+ 完成 #5 （增加自动发布release）

### v0.0.5

+ 更改搜索框样式
+ 更改头像抖动
+ 修复移动端置顶显示问题
+ 压缩 `.js`，`.css` 文件

### v0.0.4

+ 更新备案信息链接地址为：<https://beian.miit.gov.cn/>

### v0.0.3

+ 再次修复 `404` 页面图片链接错误
+ 修复 `code` 颜色

### v0.0.2

+ 修复 `404` 页面图片链接错误
+ 更新最新修改时间默认值

### v0.0.1

+ 基本功能发布
+ 修复 `License` 拼写错误
+ 迁移 `meta` 去 `head` 模板中
+ 修复 `readme` 和 `config` 文件内容

</details>
