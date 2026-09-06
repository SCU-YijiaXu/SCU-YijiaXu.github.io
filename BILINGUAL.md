# 中英文页面维护

英文正文保存在 `en/`，中文正文保存在 `ch/`。两个目录均包含 `index.md`、`publications.md`、`services.md`、`team.md` 和 `contact.md`。

英文首页仍为 `/`，其他英文页面仍为 `/publications/`、`/services/`、`/team/`、`/contact/`，原来的 `index.html` 地址也仍然可用。中文首页为 `/ch/`，其他中文页面为 `/ch/publications/` 等。

## 更新内容

1. 修改 `en/` 中的英文文件，以及 `ch/` 中对应的中文文件。翻译是独立维护的静态内容，修改英文不会自动更新中文。
2. 保留文件顶部的 `layout`、`lang`、`permalink` 和 `translation_url`。其中 `translation_url` 指向同一页面的另一语言版本。
3. 像以前一样，通过 GitHub Desktop 查看更改、提交并推送，等待 GitHub Pages 发布。

导航名称在 `_config.yml` 的 `links` 中维护：`title` 为英文，`title_ch` 为中文。顶部第一项由 `_includes/navigation.html` 自动显示“中文”或“English”。

中文论文页面包含中文译题和英文原题；作者与期刊、会议名称保留原文。团队学生姓名保留原有拼音，可在确认中文姓名后自行替换。Calendly 预约组件由第三方提供，其界面语言由该服务控制。

`README.md`、备份文件及其他说明文件不属于这五个公开页面，无需移入语言目录。
