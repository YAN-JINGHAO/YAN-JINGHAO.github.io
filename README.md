# Jinghao Yan · 晏景豪

个人学术主页：<https://yan-jinghao.github.io>

基于 [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io) 模板，保留模板原有的布局、字体、配色和响应式样式。个人资料、新闻与论文内容迁移自旧版个人网站。

## 内容维护

- `_config.yml`：网站标题、个人介绍、头像、邮箱和社交链接。
- `_pages/about.md`：个人简介、新闻、论文、荣誉、教育和实习经历。
- `_data/navigation.yml`：顶部导航及对应的页面锚点。
- `images/`：个人照片、论文配图及 favicon。个人微信二维码默认不提交或发布。
- `CV/latex_en/main.pdf`：导航栏 CV 对应的英文简历，替换此文件即可更新。

研究方向为具身智能，重点关注世界建模和灵巧操作。头像通过 CSS 调整取景；favicon 和设备图标由同一张照片生成，采用圆形取景和透明背景。

没有提供 Google Scholar 账号，因此默认关闭引用统计，也不展示模板中的示例数据。配置 `_config.yml` 中的 `author.googlescholar`、仓库 Actions secret `GOOGLE_SCHOLAR_ID` 并将 `google_scholar_stats_enabled` 设为 `true` 后，即可启用模板的引用统计功能。

## 公开范围

网站公开姓名、照片、学术联系邮箱、教育和科研经历，以及中英文简历 PDF。简历源文件、模板、预览图与编译日志不作为网站内容发布；编译产物和个人微信二维码不提交到公开仓库。未配置 Google Analytics 时不加载其脚本。

## 本地预览

安装 Ruby、Bundler 和 Jekyll 所需的构建工具后，在仓库目录运行：

```sh
bundle install
bundle exec jekyll serve --host 127.0.0.1
```

打开 <http://127.0.0.1:4000>。修改 `_config.yml` 后需要重启服务。

## GitHub Pages

本项目保持标准 Jekyll / GitHub Pages 结构。在仓库的 **Settings → Pages** 中选择实际使用的分支和根目录，即可通过 GitHub Pages 构建发布。

## 致谢

- [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io)
- [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes)
- [Academic Pages](https://github.com/academicpages/academicpages.github.io)
- Font Awesome
