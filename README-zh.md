# 便捷添加反引号插件

我个人是 `Markdown` 的深度使用者，但是在写 `Markdown` 的时候发现手动添加反引号是一件非常麻烦的事情。包括两种情况：一种是单行代码的两个反引号；另一种是使用两组一共六个反引号包含的代码块。因此花了半天研究了一下 `VSCode` 的插件开发流程，写了这个简易的小插件。

## Features
对于选中的文本使用插件会添加单行代码的反引号，不选中文本的情况下会在当前的文本的下一行自动插入代码块的反引号。

使用快捷键添加（推荐）：

- Mac: `cmd+d`
- Windows: `ctrl+d`

![add-backquote](https://www.zhangaoo.com/upload/2018/11/0a05bbv3fkglqphtorqg2fsmt6.gif)

## 安装

![install](https://www.zhangaoo.com/upload/2018/11/1nk66cbtdeh2ioc7sg9mfrgm11.png)

## Release Notes
0.0.1 (2018/11/11)
- 初始版本

### 0.0.2
- 添加自动生成代码块反引号功能

## 更多

如果有更好的建议可以在 `Github` 或者个人博客留言，后续还会添加更多的功能

* [zealzhangz Github](https://github.com/zealzhangz/markdown-add-backquote)
* [zealzhangz Blog](https://www.zhangaoo.com/article/markdown-add-backquote)

**Enjoy!**
