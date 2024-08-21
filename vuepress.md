# **[VuePress ](https://vuepress.vuejs.org/zh/guide/getting-started.html)**

- 页头分区叫导航栏
- `Frontmatter`参数无视配置文件，直接修改当前页面的配置
- 内部 Markdown 文件的链接，尽可能使用相对路径  .表示当前路径 ..为父目录
- Markdown扩展语法：可用[emoji](https://github.com/ikatyang/emoji-cheat-sheet)、仅代码行高亮 、`:no-line-numbers`参数取消行号



### Public  文件使用场景

- 需要提供一些静态资源时，但是它们并不直接被你的 Markdown 文件引用，比如 favicon 和 PWA 图标。
- 想要托管一些共享的静态资源时，甚至可能需要在你的网站外部引用它，比如 Logo 图片。
