## 🔷 提示 Tip

> 本 Hexo 主题为 Icarus 个人魔改版，官方主题请移步[ppoffice/hexo-theme-icarus](https://github.com/ppoffice/hexo-theme-icarus)。<br>
> This is an Hexo theme Icarus for personal use, the official one is [ppoffice/hexo-theme-icarus](https://github.com/ppoffice/hexo-theme-icarus).

> 本魔改主题不提供文档（因为存在大量硬编码），代码可以随意参考，有使用上的疑问可在 [Issue](https://github.com/imaegoo/hexo-theme-icarus/issues) 中提问，也可[在博客中留言](https://www.imaegoo.com/messages/)。<br>
> No documentations are provided, codes are free to use, if you have any question, please [open an issue](https://github.com/imaegoo/hexo-theme-icarus/issues) or [leave me a message](https://www.imaegoo.com/messages/).

## 🔷 用法 Usage

本主题还未兼容 hexo v7.0.0，可以先暂时使用 hexo v6.3.0

```sh
npm i -g hexo@6
mkdir blog
cd blog
hexo init --no-clone
git clone https://github.com/imaegoo/hexo-theme-icarus.git themes/icarus
hexo config theme icarus
npm i bulma-stylus@0.8.0 hexo-component-inferno@^2.0.2 hexo-pagination@^2.0.0 hexo-renderer-inferno@^0.1.3 inferno@^7.3.3 inferno-create-element@^7.3.3
hexo g # 第一遍运行会因为没有配置文件而报错，并自动生成配置文件
hexo g # 第二遍运行不会报错
```
