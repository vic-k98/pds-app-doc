# PDS-APP — 矿区车载安全设备程序升级 App（方案文档）

| 路径 | 说明 |
|---|---|
| `docs/PRD.md` | 产品需求文档主稿 v1.2（Markdown + Mermaid 流程图，可直接导入飞书文档）：一期完整需求 + 二期完整方案 + 评审意见处理记录 |
| `docs/PRD.docx` | Word 版本（流程图与界面截图已内嵌），用于飞书附件或无 Mermaid 渲染的场合 |
| `docs/pds-app-prototype.html` | 高保真可点击原型（界面文案英文，见 PRD 6.7），浏览器直接打开；`?screen=reconcile` 可定位到指定页面 |
| `docs/images/fig-*.png` | 10 张架构 / 流程 / 状态机 / 时序图 PNG |
| `docs/images/ui-*.png` | 14 张 App 界面原型截图（含 2 张待确认 / 二期预览页） |

## 版本

- v1.2（2026-09-30）：纳入 PRD 评审意见与业务方问题——设备身份识别、版本总览（Cloud / On Phone / On Device）、二维码连接、日志分层与云端上传、中断后状态对账、Wi-Fi 抢断对策、一期轻量版本服务；第 10 章扩展为二期完整方案。
- v1.1：App 界面语言改为英文，新增 i18n 需求与术语表。
- v1.0：初稿。

## 上传飞书

- 飞书文档 → 导入 → 选择 `docs/PRD.md`（Mermaid 自动渲染，图片需从 `docs/images` 手动插入），或导入 `docs/PRD.docx`（图片已内嵌）。
- 原型 HTML 可作为附件上传到飞书云空间，或放到内网静态站点后在 PRD 中贴链接。
