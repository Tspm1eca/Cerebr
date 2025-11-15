<p align="center">
<img src="./icons/icon128.png">
</p>

# 🧠 Cerebr - 智能 AI 助手

![screenshot](./statics/image.png)

Cerebr 是一款强大的浏览器 AI 助手扩展，现已支持 Chrome、Firefox 和 Edge，专注于提升您的工作效率和学习体验。"Cerebr"源自拉丁语词根，与"大脑"或"脑"相关。这个命名体现了我们的愿景：整合 Claude、OpenAI 等 AI 的强大能力，使 Cerebr 成为您的第二大脑，为您提供深度阅读和理解支持。

在尝试了市面上现有的浏览器 AI 助手后，我们发现它们要么有使用次数限制，要么界面过于花哨。Cerebr 应运而生，专注于提供一个简洁、高效、无干扰的 AI 助手体验。

---
## 個人修改內容

### 侧边栏介面
  * 為打开/关闭 Cerebr 侧边栏的動畫添加淡入淡出和稍微放大縮小效果。
  * 添加主窗口拉伸
<img width="1395" height="1577" alt="image" src="https://github.com/user-attachments/assets/2247530d-19bd-41ec-962b-5a206bfecfe5" />

### 聊天介面
  * 為等待模型回覆期間加一個等待小動畫。
  * 在聊天主頁添加滾動條
<img width="709" height="816" alt="image" src="https://github.com/user-attachments/assets/2ec674c1-e3a6-4802-bf2c-82cacbc21ad1" />
<img width="795" height="312" alt="image" src="https://github.com/user-attachments/assets/08d16252-8317-44ad-9e6a-51e529b30a40" />

### 快速選項
  * 增加「快速選項」功能，並允許用戶自訂prompt、名稱和圖標。
  * 「快速選項」會在用戶發送訊息後會自動隱藏（帶動畫）。
<img width="751" height="211" alt="image" src="https://github.com/user-attachments/assets/ed0911c4-75d5-42e5-a778-f93052c5b2a9" />
<img width="735" height="1406" alt="image" src="https://github.com/user-attachments/assets/48646ddc-2c35-451f-bb5f-e1432a461499" />

### 輸入框與菜單
  * 在主介面輸入框中顯示當前使用模型名稱。
  * 在主介面輸入框旁添加常用的「新對話」按鍵。
  * 當鼠標懸停在菜單按鍵時，會自動彈出菜單。
  * 刪除菜單中的「新的對話」按鍵。
  * 為菜單添加是否「传送网页」內容按鍵。
<img width="751" height="211" alt="image" src="https://github.com/user-attachments/assets/758a8ee7-44f3-404c-98ed-e2618800cefa" />
<img width="334" height="542" alt="image" src="https://github.com/user-attachments/assets/39121a5b-6ea6-403c-a7b0-8aa33975923e" />

### 历史
  * 增加刪除所有歷史記錄的按鈕。
  * 增加刪除二次確定。
<img width="728" height="97" alt="螢幕擷取畫面 2025-11-11 022306" src="https://github.com/user-attachments/assets/579512b6-a160-4590-9819-d4aa23a01462" />
<img width="736" height="323" alt="image" src="https://github.com/user-attachments/assets/7d5af081-79cc-4b3d-a030-f2ecbc7bc967" />

### API 设置
  * 自動抓取Base URL可用模型。
  * 同時支持用戶輸入和列表選擇模型
  * 輸入模型名稱時動態刷新模型列表。
  * 添加測試模型是否可用按鍵。
<img width="661" height="389" alt="image" src="https://github.com/user-attachments/assets/bc8c0b90-b84b-4c27-b995-c5514b29c520" />

### 修正`<think>`和`<thinking>`標籤問題
  * 修正LLM流式回覆帶有`<think>`或`<thinking>`標籤時，部份正文會被包裹在cot中。

**修正前**
<img width="696" height="739" alt="螢幕擷取畫面 2025-11-11 054048" src="https://github.com/user-attachments/assets/6158bc5d-1cc5-4473-acbd-ba724801f5ba" />

**修正後**
<img width="736" height="614" alt="image" src="https://github.com/user-attachments/assets/79a3ef15-3baa-41a0-9b5f-9cc7325777b1" />

**LLM返回內容**
<img width="780" height="806" alt="image" src="https://github.com/user-attachments/assets/7db22dee-b9a2-4f53-a862-18f5caa9faf6" />

---
## 原版訊息

## ✨ 核心特性

- 🎯 **智能侧边栏** - 通过快捷键(Windows: `Alt+Z` / Mac: `Ctrl+Z`)快速唤出,随时随地与 AI 对话
- 🔄 **多 API 支持** - 支持配置多个 API,灵活切换不同的 AI 助手
- 🔁 **配置同步** - 支持跨浏览器的 API 配置同步，轻松在不同设备间共享设置
- 💻 **多平台支持** - 已上架 Chrome、Firefox 和 Edge 商店，在不同浏览器中提供一致的体验。
- � **全能问答** - 支持网页内容问答、PDF 文档问答、图片问答等多种场景
- 🎨 **优雅渲染** - 完美支持 Markdown 文本渲染、LaTeX 数学公式显示
- ⚡ **实时响应** - 采用流式输出,即时获取 AI 回复
- ⏹️ **灵活控制** - 支持在生成过程中随时停止，发送新消息自动停止当前生成
- 🌓 **主题切换** - 支持浅色/深色主题,呵护您的眼睛
- 🌐 **网页版** - 支持网页版，无需安装，通过任何浏览器访问，支持 vercel、GitHub Pages 和 cloudflare pages 部署

## 🛠️ 技术特性

- 💾 **状态持久化** - 自动保存对话历史、侧边栏状态等
- 🔄 **配置同步** - 支持通过浏览器原生同步API实现跨设备配置共享
- 🔍 **智能提取** - 自动识别并提取网页/PDF 内容
- ⌨️ **快捷操作** - 支持快捷键清空聊天(Windows: `Alt+X` / Mac: `Ctrl+X`)、上下键快速调用历史问题
- 🔒 **安全可靠** - 支持多 API Key 管理,数据本地存储
- 🎭 **兼容性强** - 官方支持 Chrome、Firefox、Edge 等主流浏览器，适配各类网页环境。

## 🎮 使用指南

1. 🔑 **配置 API**
   - 点击设置按钮
   - 填写 API Key、Base URL 和模型名称
   - 支持添加多个 API 配置

2. 💬 **开始对话**
   - 使用快捷键 Windows: `Alt+Z` / Mac: `Ctrl+Z` 唤出侧边栏
   - 输入问题并发送
   - 支持图片上传进行图像问答

3. 📚 **网页/PDF 问答**
   - 开启网页问答开关
   - 自动识别并提取当前页面内容
   - 支持 PDF 文件智能问答

## 🔧 高级功能

- 📋 **右键复制** - 支持右键直接复制消息文本
- 🔄 **历史记录** - 使用上下方向键快速调用历史问题
- ⏹️ **停止生成** - 在生成消息时右键显示停止按钮，可随时中断生成
- 🖼️ **图片预览** - 点击图片可查看大图
- ⚙️ **自定义配置** - 支持自定义快捷键、主题等设置

## 🚀 网页版部署

1. 你可以一键将 Cerebr 的 Web 版本部署到 Vercel：

[![使用 Vercel 部署](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fyym68686%2Fcerebr)

2. 你可以部署到 Cloudflare Pages：

2.1 注册好 CF 账号后，申请 Workers API TOKEN。

进入 CF 首页后，右上角选择配置文件 -> 我的个人资料 -> API 令牌 -> 创建令牌 -> 编辑 Cloudflare Workers -> `账户资源`和`区域资源`可以自己选择授予权限 -> 继续以显示摘要 -> 创建令牌 -> 保存令牌（**注意：** 保存好自己的令牌，因为只显示一次）

2.2 回到首页，左侧找到 Workers -> 打开 `Worker 和 Pages` -> 点击`创建` -> `Pages` -> 导入现有 Git 存储库 -> 找到 Fork 的存储库 -> 开始部署

2.3 项目名称写上自己喜欢的名字，在`构建命令`项输入：

`npm install -g wrangler && wrangler pages deploy . --project-name cerebr --branch main`

2.4 下方`环境变量（高级）` -> 添加变量：

`CLOUDFLARE_API_TOKEN`：填上刚申请到的API
`CLOUDFLARE_ACCOUNT_ID`：Cloudflare 控制台首页的 URL 中获取，格式如 https://dash.cloudflare.com/<ACCOUNT_ID>

2.5 保存并部署。

（由于直接构建部署会导致 API 和 accountID 会以明文形式保存，若想更改成密文，可以选择部署完成后点击`继续处理项目` -> 设置 -> 变量和机密 -> 编辑 -> 把`文本`形式更改成`密文` -> 保存）

3. 你也可以部署到 GitHub Pages：

```bash
# Fork 这个仓库
# 然后进入你的仓库的 Settings -> Pages
# 在"构建和部署"部分：
# - 将"Source"选择为"Deploy from a branch"
# - 选择你的分支（main/master）和根目录（/）
# - 点击保存
```

部署将由 GitHub Actions 自动处理。你可以通过 `https://<你的用户名>.github.io/cerebr` 访问你的站点

### Web 版本特点
- 🌐 无需安装，通过任何浏览器访问
- 💻 与 Chrome 扩展版本具有相同的强大功能
- ☁️ 部署自己的实例以获得更好的控制
- 🔒 安全私密的部署方案

## mac 桌面应用

安装 dmg 后，需要执行以下命令：

```bash
sudo xattr -r -d com.apple.quarantine /Applications/Cerebr.app
```

本项目使用 Pake 打包，打包命令如下：

```bash
iconutil -c icns icon.iconset
pake https://xxx/ --name Cerebr --hide-title-bar --icon ./icon.icns
```

https://github.com/tw93/Pake

## 🚀 最新更新

- 🆕 支持图片问答功能
- 🔄 优化网页内容提取算法
- 🐛 修复数学公式渲染问题
- ⚡ 提升整体性能和稳定性

## 📝 开发说明

本项目采用 Chrome Extension Manifest V3 开发,主要技术栈:

- 🎨 原生 JavaScript + CSS
- 📦 Chrome Extension API
- 🔧 PDF.js + KaTeX + Marked.js

## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request 来帮助改进项目。在提交之前,请确保:

- 🔍 已经搜索过相关的 Issue
- ✅ 遵循现有的代码风格
- 📝 提供清晰的描述和复现步骤

## 📄 许可证

本项目采用 GPLv3 许可证