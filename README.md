# YUUNALAB+ Quotation System

A lightweight, single-file quotation/estimate generator designed for photography, video production, and creative studios.

一个轻量级的单文件报价单生成器，专为摄影、视频制作及创意工作室设计。

---

## About / 关于

This project was born from real production needs — originally built as an internal tool at YUUNALAB+ for daily quoting work, and now open-sourced for all visual creatives to use freely.

这个项目源于真实的制作需求 —— 最初是 YUUNALAB+ 内部自用的报价工具，在日常商业拍摄中不断打磨，现在开源出来，希望能帮到所有视觉行业的从业者。

Whether you're a photographer, videographer, retoucher, 3D artist, or production manager — this tool is made for you.

无论你是摄影师、视频创作者、修图师、三维艺术家还是制片人 —— 这个工具都适合你。

## Features / 功能

- **Single HTML file / 单文件** - No build tools, no dependencies, just open and use / 无需构建，无需依赖，打开即用
- **Bilingual (EN/CN) / 中英双语** - Full English & Chinese support for international productions / 完整的中英文支持，适合国际化制作
- **Multiple project types / 多项目类型** - Photography, Video, Full Production, AI/3D / 摄影、视频、全案制作、AI/3D
- **Smart templates / 智能模板** - Pre-built role & fee templates (photographers, stylists, editors, 3D artists, etc.) / 内置角色和费用模板（摄影师、造型师、剪辑师、3D艺术家等）
- **PDF export / PDF导出** - One-click export to professional PDF quotations / 一键导出专业PDF报价单
- **Equipment & Props lists / 器材与道具清单** - Dedicated tabs for tracking gear and props / 独立标签页管理器材和道具
- **Auto-calculation / 自动计算** - Real-time subtotals, tax, and grand total / 实时小计、税费和总计
- **Customizable branding / 自定义品牌** - Logo upload, accent color, brand name / 上传Logo、自定义主题色和品牌名
- **Local storage / 本地存储** - Auto-saves your work in the browser / 浏览器自动保存
- **Save/Load JSON / 数据导入导出** - Export and import quotation data / 导出和导入报价数据

## Quick Start / 快速开始

1. Download `index.html` / 下载 `index.html`
2. Open it in your browser / 用浏览器打开
3. Start creating quotations / 开始制作报价单

That's it. No server, no installation, no configuration.

就这么简单，不需要服务器，不需要安装，不需要配置。

## Project Types / 项目类型

| Type / 类型 | Sections Included / 包含模块 |
|------|------------------|
| Photography / 摄影 | Photo, Styling, Equipment, Setting |
| Video / 视频 | Video, Styling, Equipment, Setting |
| Full Production / 全案制作 | Photo, Video, Styling, Equipment, Setting |
| AI / 3D | Photo, Equipment |

## Customization / 自定义设置

Click the **Settings** gear icon to: / 点击 **设置** 齿轮图标可以：
- Change brand name and logo / 更换品牌名称和Logo
- Set accent color theme / 设置主题色
- Configure default photographer name and city / 配置默认摄影师和城市

## Roadmap / 开发计划

### Next Up / 近期优化

- [ ] Package price field with override — enter a flat rate to override per-day calculation / 打包价格字段 —— 填入即覆盖按天计算的结果
- [ ] JSON export/import button — easily transfer quotation data between devices / JSON 导出/导入按钮 —— 方便在不同电脑间传输报价数据

### Phase 2: AI Integration / 第二阶段：AI 接入

- [ ] AI-powered quotation suggestions — auto-generate fee estimates based on project description / AI 智能报价建议 —— 根据项目描述自动生成费用预估
- [ ] AI-powered supplier quote import — scan PDF/image quotes from vendors and auto-fill into equipment list / AI 识别供应商报价 —— 扫描设备商的 PDF/图片报价单，自动导入设备清单
- [ ] Support OpenAI-compatible & Anthropic APIs / 支持 OpenAI 兼容接口及 Anthropic API
- [ ] Smart role & template recommendations / 智能角色和模板推荐

### Phase 3: Local Equipment Database / 第三阶段：本地设备数据库

- [ ] Built-in equipment library with IndexedDB — store your gear catalog locally in the browser, no server needed / 基于 IndexedDB 的本地设备库 —— 浏览器内置存储，无需服务器
- [ ] Auto-complete equipment names & prices — type a device name and get suggestions with rental prices / 设备名称和价格自动补全 —— 输入设备名自动联想并填入租赁价格
- [ ] Editable after auto-fill — prices from the database are suggestions, always adjustable per project / 自动填入后仍可修改 —— 数据库价格仅作参考，每个项目可单独调整

> This project is designed to stay lightweight — a single HTML file, pure frontend, no backend required. For multi-user or team-shared databases, you're welcome to fork and extend!
>
> 本项目定位轻量化 —— 单文件、纯前端、无需后端。如需多人共享数据库，欢迎 fork 后自行扩展！

### Future / 未来规划

- [ ] Mobile & tablet responsive layout / 手机和平板端适配
- [ ] Multi-currency support / 多币种支持
- [ ] Client management / 客户管理
- [ ] Quotation history & analytics / 报价历史与数据分析

## License / 开源协议

[MIT](LICENSE) - Free for personal and commercial use. / 免费用于个人和商业用途。

## Author / 作者

Made by **Yuuna Wang** — [GitHub](https://github.com/ichthyo-na) · [Xiaohongshu/小红书](https://xhslink.com/m/2SfBwkrah8m)

由 **Yuuna Wang** 制作 — 欢迎关注小红书交流！
