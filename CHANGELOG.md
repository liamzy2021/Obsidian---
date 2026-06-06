# Changelog

## V17.1.2 (2026-06-06)

### New Features

- **In-Note Code Block Galleries (`t` / `s`)**: Render image/media galleries directly in any note using ````t```` or ````s```` code blocks. Supports both pipe-separated and key-value formats.
- **Spacing Settings Dialog**: Right-click code block → ⚙ Spacing, adjust left/right padding and item gap (px) with real-time parameter updates.
- **Smart Center**: Enable in the spacing dialog to auto-center gallery content with flex layout.
- **Apply to All Notes**: One-click batch update spacing parameters for all `t`/`s` code blocks across the vault.

### Bug Fixes

- Fixed dashboard image gallery module disappearing (`modules/image-gallery.js` extra `});` syntax error)
- Fixed `t` code block "Custom Layout" not taking effect (radio button missing `value` attribute)
- Fixed `t` code block "Custom Size" throwing error (function parameter misalignment causing `parent` to be `undefined`)
- Fixed `s` code block corruption after using menu (`locateBlock` off-by-one in `le` line calculation)
- Fixed `s` code block "Custom Size" not working when path has no `|` (size not written)
- Fixed `t` code block "Edit" throwing error (`scrollIntoView` parameter format)

### Donation UI

- Settings panel donation section redesigned as 3-column layout: Afdian → Ko-fi → WeChat QR
- README English Support section: Ko-fi only
- README Chinese Support section: Afdian + WeChat QR only
- WeChat QR code: `https://img-reg-ab.imagency.cn/e/19467f4b916c082ee6ef3b9d81aa9ecb.png`

### Other

- Cleaned up temporary project files (3.4 MB)
- Added complete code block gallery documentation to README (English & Chinese)
- New `merge.bat` script for generating the 3 official plugin store files

---

# 更新日志

## V17.1.2 (2026-06-06)

### 新增功能

- **笔记内代码块画廊 (`t` / `s`)**：在任意笔记中使用 ````t```` 或 ````s```` 代码块即可渲染图片/媒体画廊。支持管道格式和键值格式两种写法。
- **间距设置对话框**：右键代码块 → ⚙ 间距设置，可调节左距、右距、图片/媒体间距（px），参数实时写入代码块。
- **智能居中**：间距对话框中开启「智能居中」，图片/媒体自动居中排列。
- **应用到所有笔记**：间距对话框中的「应用到所有笔记」按钮，一键批量更新库中所有 `t`/`s` 代码块间距参数。

### 修复

- 修复图片画廊仪表盘模块消失的问题（`modules/image-gallery.js` 多余 `});` 语法错误）
- 修复 `t` 代码块「自定义排版」不生效（radio button 缺少 value 属性）
- 修复 `t` 代码块「自定义大小」报错（函数参数错位导致 parent 为 undefined）
- 修复 `s` 代码块使用菜单后代码块损坏（`locateBlock` 中 `le` 行号 off-by-one 错误）
- 修复 `s` 代码块自定义大小不生效（路径无 `|` 时 size 未写入）
- 修复 `t` 代码块「编辑」报错（`scrollIntoView` 参数格式错误）

### 打赏界面

- 软件设置底部打赏改为三栏布局：爱发电 → Ko-fi → 微信赞赏二维码
- README 英文 Support 只保留 Ko-fi
- README 中文打赏只保留爱发电 + 微信赞赏二维码
- 微信赞赏码使用图床外链 `https://img-reg-ab.imagency.cn/e/19467f4b916c082ee6ef3b9d81aa9ecb.png`

### 其他

- 清理项目临时文件（3.4 MB）
- README 新增代码块画廊完整使用文档（中英文）
- 新增 `合并.bat` 一键生成官方插件商店 3 个文件
