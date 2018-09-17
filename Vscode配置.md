# Vscode配置

### [Atom One Dark Theme](https://marketplace.visualstudio.com/items?itemName=akamud.vscode-theme-onedark)
> 这是我用的Vscode皮肤

### [Chinese (Simplified) Language Pack for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=MS-CEINTL.vscode-language-pack-zh-hans)
> VS Code 的中文（简体）语言包
>安装后，在 locale.json 中添加 "locale": "zh-cn"，即可载入中文（简体）语言包。要修改 locale.json，你可以同时按下 Ctrl+Shift+P 打开命令面板，之后输入 "config" 筛选可用命令列表，最后选择配置语言命令。请参阅文档并获取更多信息。

### [Prettier Now](https://marketplace.visualstudio.com/items?itemName=remimarsal.prettier-now)
> 格式化CSS, Sass，Less  Jsx 等等

### [auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag "auto Rename Tag")
> 自动重命名配对HTML标签

![](./img/Vscode配置/AutoRenameTag.gif)
### [Easy LESS](https://marketplace.visualstudio.com/items?itemName=mrcrowl.easy-less)
> 在保存时自动编译LESS到CSS

```less
// out: index.css, compress: true, sourceMap: false, autoprefixer: > 5%; last 2 Chrome versions; not ie 6-9
// 新建less文件 把以上内容复制到less内容最顶部
```
| 设置 | 说明 | 值 |
| ------------ | ------------ | ------------ |
|  out |  将css输出到文件名 | String |
| sourceMap  | 允许生成源映射文件 *.map 文件  | true: &nbsp;&nbsp;输出<br />false: &nbsp;不输出<br />|
| compress  | 通过删除多余的空白来压缩css输出  | true: &nbsp;删除<br />false: 不删除 |
| autoprefixer  | 此插件会自动添加/删除支持您指定的一组浏览器所需的供应商前缀  | > 5%; last 2 Chrome versions; not ie 6-9 |

### [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
> 自动填充文件名

![](./img/Vscode配置/PathIntellisense.gif)

### [vscode weapp api](https://marketplace.visualstudio.com/items?itemName=coderfee.vscode-weapp-api)
> 微信小程序 API 代码片段

### [vscode wxml](https://marketplace.visualstudio.com/items?itemName=coderfee.vscode-wxml)
> 为VSCode提供wxml语法支持及代码片段
