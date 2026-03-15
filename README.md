# 综应答题卡生成器

> 一个开源的、可自定义字数要求的综应/申论答题卡生成工具，支持在线预览与 PDF 下载。

[![示例截图](https://github.com/MF-142/Comprehensive-Application-Ability-answer_card/blob/main/%E9%A2%84%E8%A7%88.png?raw=true)

本工具专为公务员考试、事业单位《综合应用能力》等主观题练习设计，帮助考生在标准答题卡格式下进行模拟作答，提升卷面规范意识。

---

## ✨ 功能特点

- 📝 **动态添加/删除题目**：自由设置每道题的字数要求（1~1000 字）
- 🖨️ **一键导出高清 PDF**：基于 A4 纸张尺寸（210mm × 297mm），适配打印
- 🔢 **自动编号**：题目序号以中文“一、二、三…”显示
- 🧮 **智能格子布局**：每行 25 格，每格约 8mm，符合主流考试答题卡标准
- 🌐 **纯前端实现**：无需服务器，可直接保存 HTML 文件离线使用
- 📱 **响应式控制面板**：左侧配置，右侧实时预览

---

## 🚀 使用方式

### 方式一：在线使用（推荐）
访问部署好的在线版本：
> [⏳ *（你可在此处填写你的 Vercel / GitHub Pages / Netlify 链接）*](https://mf-142.github.io/Comprehensive-Application-Ability-answer_card/)

### 方式二：本地运行
1. 点击右上角 **`Code` → `Download ZIP`** 下载项目
2. 解压后，用浏览器打开 `index.html`
3. 在左侧设置标题和题目，右侧实时预览
4. 点击 **“下载PDF”** 按钮保存答题卡

> 💡 无需安装任何依赖，完全在浏览器中运行！

---

## 📄 许可证

本项目采用 **[GNU Affero General Public License v3.0 (AGPL-3.0)](LICENSE)**。

这意味着：
- ✅ 你可以自由使用、修改、分发本项目；
- ✅ 你可以将其用于个人、教育或商业用途；
- ⚠️ **但如果你基于本项目提供网络服务（如部署自己的答题卡网站）或分发修改版，必须公开完整源码**；
- 👤 作为版权所有者，作者保留所有权利，并可提供商业闭源授权（如有需求请联系）。

> 选择 AGPL 是为了确保所有衍生作品回馈社区，推动教育工具的开放共享。

---

## 🛠️ 技术栈

- **HTML5 + CSS3 + JavaScript (ES6)**
- **[jsPDF](https://github.com/parallax/jsPDF)** – 生成 PDF
- **[html2canvas](https://github.com/niklasvh/html2canvas)** – 将 DOM 转为图像
- **A4 尺寸标准**：210mm × 297mm（符合 ISO 216）

---

## 🤝 贡献与反馈

欢迎提交 Issue 或 Pull Request！  
如果你有以下需求，也欢迎提出：
- 新增答题卡模板（如高考、考研）
- 支持多语言
- 优化移动端体验
- 添加页眉/考生信息栏

> 💬 本项目旨在服务广大考生，期待你的参与！

---

## ❤️ 致谢

- 感谢 [jsPDF](https://github.com/parallax/jsPDF) 和 [html2canvas](https://github.com/niklasvh/html2canvas) 的开源贡献
- 灵感来源于真实考试答题卡规范

---

> 📌 **提示**：打印前请在 PDF 阅读器中选择“实际大小”而非“适应页面”，以确保格子尺寸准确。
