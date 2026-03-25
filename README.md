# Lord Buddha Temple · Blessing Schedule 

A custom-built, lightweight Progressive Web App (PWA) designed for the **Lord Buddha Temple in Singapore**. It provides a seamless way for devotees to check monk blessing schedules and book Buddhist services in English, Chinese, and Thai.

## ✨ Key Features

* **Trilingual Support**: Fully integrated Chinese, English, and Thai interfaces to serve a diverse community.
* **Real-time Status**: Automatically detects Singapore Time (SGT) to highlight the current active blessing session (Morning, Afternoon, or Evening).
* **Dynamic Data**: Powered by the SheetDB API, fetching the latest schedules directly from a Google Sheet.
* **PWA Ready**: Supports "Add to Home Screen" for an app-like experience with offline caching capabilities.
* **Sacred Aesthetic**: A responsive design featuring temple-inspired crimson and gold themes, optimized for mobile devices.
* **Service Integration**: One-click WhatsApp buttons for Sangkathan, Flower Bathing, and Car Blessing appointments.

## 🛠️ Tech Stack

* **Frontend**: HTML5, CSS3 (Flexbox/Grid), Vanilla JavaScript.
* **Backend API**: [SheetDB](https://sheetdb.io/) (Turns Google Sheets into a JSON API).
* **Fonts**: Google Fonts (Noto Serif SC, Noto Serif Thai, Cinzel).
* **Deployment**: GitHub Pages.

## 🚀 Quick Start

1.  **Upload**: Upload your `index.html` file to your GitHub repository.
2.  **Enable Hosting**: 
    * Go to **Settings** > **Pages** in your repository.
    * Under **Branch**, select `main` and click **Save**.
3.  **Access**: Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

## 📊 Data Structure

The app expects a Google Sheet with the following column headers:
* `Date`: Format (DD/MM/YYYY).
* `week`: Weekday name (e.g., Sunday, Monday).
* `Morning`: Morning session details.
* `Afternoon`: Afternoon session details.
* `Evening`: Evening session details.

---
🙏 *May the light of Buddha bring you peace and prosperity.*


# 三宝佛光寺 · 祈福时刻表 (Lord Buddha Temple Blessing Schedule)

一个为新加坡三宝佛光寺定制的轻量级 Web 应用程序（PWA），用于展示僧侣祈福时间安排、提供佛教服务预约功能，并支持中、英、泰三语显示。

## ✨ 项目亮点

* **三语支持**：完整集成中文、英文、泰文界面，服务多元社区。
* **实时状态**：自动根据新加坡时间（SGT）判断当前是否正处于祈福时段，并高亮显示。
* **动态数据驱动**：通过 SheetDB API 实时获取 Google Sheets 中的最新日程。
* **PWA 支持**：支持“添加到主屏幕”，提供类似原生 App 的离线访问体验。
* **响应式设计**：深红与金色的寺庙审美风格，完美适配各种手机屏幕。
* **预约集成**：一键通过 WhatsApp 预约供养僧人、冲花水、车祈福等服务。

## 🛠️ 技术栈

* **前端**: HTML5, CSS3 (Flexbox/Grid), Vanilla JavaScript
* **后端 API**: [SheetDB](https://sheetdb.io/) (将 Google Sheets 转换为 JSON API)
* **字体**: Google Fonts (Noto Serif SC, Noto Serif Thai, Cinzel)
* **部署**: GitHub Pages

## 🚀 快速开始

1.  **上传文件**：将 `index.html` (或你重命名后的文件) 上传至 GitHub 仓库。
2.  **开启托管**：
    * 进入仓库的 **Settings** > **Pages**。
    * 在 **Branch** 下选择 `main` 分支并保存。
3.  **访问网页**：稍等片刻，即可通过 `https://<你的用户名>.github.io/<仓库名>/` 访问。

## 📊 数据结构说明

本项目依赖于 Google Sheets 数据。API 预期的字段名如下：
* `Date`: 日期 (格式: DD/MM/YYYY)
* `week`: 星期 (英文，如 Sunday, Monday)
* `Morning`: 早上时段内容
* `Afternoon`: 下午时段内容
* `Evening`: 傍晚时段内容

## 📸 界面预览

* **今日祈福卡片**：显示当前日期的详细时段及状态。
* **服务快捷入口**：底部集成的 WhatsApp 预约按钮。
* **日程列表**：按月份分组展示未来的祈福安排。

---
🙏 *愿佛光普照，吉祥安康。*
