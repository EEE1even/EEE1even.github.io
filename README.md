# 黄施洋的个人主页

个人主页使用 Jekyll 构建，展示工作经历、研究项目和简历。[访问主页](https://eee1even.github.io/)

## 更新内容

- `_config.yml` 保存站点信息和联系方式。
- `_pages/about.html` 与 `_pages/cv.md` 分别维护首页和简历正文。PDF 简历保存在 `assets/`。
- `_data/selected_work.yml` 和 `_data/navigation.yml` 分别维护项目卡片与导航。
- `_posts/` 保存博客文章，可从站点地图访问。
- `_layouts/profile.html` 与 `assets/css/profile.css` 管理共用布局和样式。

## 本地预览与部署

安装 Ruby 和 Bundler 后，在仓库根目录运行以下命令。

```sh
bundle install
bundle exec jekyll serve
```

在浏览器中打开 `http://localhost:4000`。运行 `bundle exec jekyll build` 可生成 `_site/`。推送到 `master` 后，GitHub Pages 会从仓库根目录构建并发布，进度可在仓库的 Actions 页查看。

## 来源与授权

此项目源自 Academic Pages，其基础主题 Minimal Mistakes 由 Michael Rose 开发，采用 MIT 许可证。[Academic Pages](https://github.com/academicpages/academicpages.github.io) · [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) · [项目许可证](LICENSE)

主页使用的 Font Awesome Free 图标字体由 Fonticons, Inc. 提供，采用 SIL Open Font License 1.1。[字体许可证](assets/webfonts/LICENSE.txt)
