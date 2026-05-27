# Emersive-Enlish-Reader
📚 沉浸式英文阅读助手 (Immersive English Reader)

一个轻量级、无需后端的纯前端单页面应用，旨在提供无干扰的英文阅读和沉浸式的生词学习体验。

✨ 核心特性

🚀 零依赖，开箱即用： 纯 HTML、CSS (Tailwind)、JavaScript 实现，只有一个 .html 文件，无需安装 node_modules 或配置环境。

📖 沉浸式标注： 粘贴任意英文段落，保留段落格式，点击任意单词即可高亮标注。

🌐 实时双引擎翻译：

自动调用 Google Translate API 获取准确的中文主翻译和多词性详细释义。

自动调用 Free Dictionary API 获取标准音标 (IPA)。

📝 智能生词本： 选中的单词会自动汇集成右侧的生词本，支持独立删除。

💾 本地数据持久化： 刷新页面不会丢失当前的阅读进度和生词本数据。

🔊 单词发音： 内置 TTS 语音引擎，点击生词卡片上的喇叭图标即可发音。

🌙 暗色模式： 护眼暗色主题，支持一键切换。

📋 多格式导出： 支持一键排版复制到剪贴板，或 导出为 CSV 表格 方便导入 Anki / Notion。

📸 界面预览
<img width="1343" height="764" alt="Screenshot 2026-05-26 at 7 31 21 PM" src="https://github.com/user-attachments/assets/0eb02242-f16b-42b0-b5e2-0cf9cfdbe38d" />

🛠️ 如何使用

下载或克隆本仓库

git clone [https://github.com/joanzhangcw/Emersive-Enlish-Reader.git](https://github.com/joanzhangcw/Emersive-Enlish-Reader.git)


直接运行
直接双击打开 EnglishReader.html 文件，即可在浏览器中运行。
(推荐使用 VS Code 的 Live Server 插件以获得最佳体验)

开始阅读

在左侧文本框粘贴你想阅读的英文文章。

点击“开始阅读”。

在阅读区，点击任何你不认识的单词，它会被高亮，并在右侧生成带有音标和翻译的生词卡片。

💻 技术栈

HTML5

Vanilla JavaScript (无框架)

Tailwind CSS (通过 CDN 引入，用于快速构建现代化 UI)

APIs: Google Translate Public API (查词/释义), Free Dictionary API (音标), Web Speech API (发音)

🤝 贡献与反馈

欢迎提交 Issue 和 Pull Request！如果你觉得这个小工具对你有帮助，欢迎点一个 ⭐️ Star！

📫 联系方式

如果你有任何建议、发现了 bug，或者想交流技术，欢迎随时联系我：

Email: joanzhangcw@gmail.com

📄 License

本项目基于 MIT License 开源。
