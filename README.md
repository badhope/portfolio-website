
# DevPortfolio - 个人作品集网站
> 一个基于纯 HTML/CSS/JavaScript 的响应式个人作品集网站，支持暗色/亮色主题、多语言（中英文）、项目展示、技术博客、收藏与评论等交互功能。
---
## 项目简介
DevPortfolio 是一个面向开发者的个人作品集静态网站模板，采用单页面应用架构，无需任何后端服务即可运行。  
适合用于：
- 个人作品集 / 技能展示
- GitHub Pages 个人主页
- 求职简历与项目展示
- 技术博客与知识沉淀
主要特性：
- 响应式设计，适配手机、平板和桌面端
- 支持中文 / 英文切换
- 暗色 / 亮色 / 护眼多主题模式
- 项目案例展示（支持分类筛选、收藏）
- 技术博客列表（支持分类与分页）
- 粒子背景动画（可关闭）
- 本地存储收藏、评论、访问统计
- 图片懒加载、骨架屏加载占位
- 完全静态，无需后端，可部署到 GitHub Pages / Vercel / Netlify 等
---
## 在线预览
- 本地直接打开 `index.html` 即可预览
- 推荐部署到 GitHub Pages、Vercel 或 Netlify
---
## 项目结构
```text
.
├── index.html          # 单页面应用入口
├── README.md           # 项目说明文档
├── LICENSE             # 开源协议
├── assets/             # （如需本地化资源可在此扩展）
│   ├── images/         # 图片资源
│   └── fonts/          # 字体文件（可选）
└── ...
```
> 注：当前版本使用 CDN 引入 Tailwind、Chart.js、Marked、Highlight.js 等，保持仓库体积轻量。
---
## 快速开始
### 1. 克隆仓库
```bash
git clone https://github.com/badhope/portfolio-website.git
cd portfolio-website
```
### 2. 本地预览
直接用浏览器打开 `index.html`：
- macOS:  
  ```bash
  open index.html
  ```
- Windows:  
  ```bash
  start index.html
  ```
- Linux:  
  ```bash
  xdg-open index.html
  ```
或使用任意静态服务器，例如：
```bash
# 使用 Python 3
python -m http.server 8080
# 使用 Node.js 的 serve
npx serve .
```
然后访问 `http://localhost:8080`。
---
## 部署到 GitHub Pages
1. 将代码推送到 GitHub 仓库：  
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```
2. 在仓库设置中开启 GitHub Pages：
   - `Settings` → `Pages`
   - `Source` 选择 `Deploy from a branch`
   - `Branch` 选择 `main`（或你的默认分支），目录选择 `/ (root)`
   - 保存后等待几分钟，即可通过 `https://<your-username>.github.io/<repo-name>/` 访问。
---
## 功能说明
### 1. 响应式布局
- 使用 Tailwind CSS 实现移动优先的响应式设计
- 针对手机端提供底部导航栏，方便快速切换页面区域
- 自动适配不同屏幕尺寸和设备类型
### 2. 多语言支持（中英文）
- 支持中文 / 英文一键切换
- 语言配置保存在本地存储，刷新后保持选择
- 主要文案均通过 `data-i18n` 属性标记，方便扩展更多语言
### 3. 主题模式
- 支持三种主题：
  - 浅色模式（Light）
  - 深色模式（Dark）
  - 护眼模式（Eye Care）
- 主题设置保存在本地存储，自动记住用户偏好
### 4. 项目展示
- 项目案例以卡片形式展示，支持悬浮动画效果
- 按类别筛选：Web 应用 / 移动端 / API 后端 / 工具开源
- 支持收藏功能，收藏数据保存在本地
- 点击卡片可查看项目详情（模态框展示）
### 5. 技术博客
- 博客文章支持分类浏览（前端 / 后端 / DevOps / 教程等）
- 支持分页加载
- 支持收藏，方便后续阅读
- 阅读量统计与显示
### 6. 粒子背景与动画
- 首页粒子背景动画，支持鼠标交互
- 可在设置中一键开启 / 关闭粒子效果
- 支持 `prefers-reduced-motion` 媒体查询，尊重系统减少动画设置
### 7. 本地存储与交互
- 收藏的项目、博客保存在本地
- 评论数据保存在本地（演示用途，无后端）
- 访问统计用于记录页面访问情况（本地存储）
---
## 自定义配置
### 修改个人信息
在 `index.html` 中找到以下区域，修改为你的真实信息：
- 头像与姓名（Hero 区域）
- 个人简介（About 区域）
- 技能栈（Skills 区域）
- 项目案例数据（`projectsData` 对象）
- 博客文章数据（`blogData` 对象）
- 联系方式与社交链接
### 更换主题色
在 `<style>` 部分或 Tailwind 配置中调整：
- `--primary-color` 等主色变量
- `--bg-primary`、`--text-primary` 等背景与文字颜色
- 或直接在 Tailwind 的 `theme.extend.colors` 中修改
### 添加真实数据
将 `projectsData` 与 `blogData` 替换为你的真实项目和文章：
- `title` / `titleEn`：中英文标题
- `description` / `descriptionEn`：中英文描述
- `image`：项目封面图链接
- `tags`：技术标签
- `github` / `demo`：源码与演示链接
---
## 技术栈
- HTML5 / CSS3 / JavaScript (ES6+)
- Tailwind CSS（通过 CDN）
- Chart.js（雷达图、饼图）
- Marked.js（Markdown 渲染）
- Highlight.js（代码高亮）
- Hammer.js（触摸手势支持）
- 本地存储（LocalStorage）
---
## 目录结构说明
- `index.html`：单页面应用入口，包含所有页面结构与逻辑
- 内联 CSS 与 JavaScript，减少外部依赖，适合快速部署
- 所有数据通过前端对象配置，方便维护与扩展
---
## 常见问题
### 1. 图片无法加载？
- 检查 `projectsData` 与 `blogData` 中的 `image` 字段是否为有效链接
- 如使用本地图片，请确保路径正确，或放在 `assets/images/` 目录下
### 2. 如何添加更多页面？
当前为单页面应用，可通过以下方式扩展：
- 在 `index.html` 中增加新的 `section`
- 在导航栏与底部导航中添加对应锚点链接
- 或改造为多页面结构，每个页面单独维护
### 3. 如何接入后端？
当前为纯静态项目，如需接入后端：
- 可将 `projectsData`、`blogData` 等改为从 API 获取
- 将评论、收藏等数据改为保存到数据库
- 使用 GitHub Issues / Discussions 或第三方评论系统（如 Giscus）
---
## 联系方式
- 邮箱：x18825407105@outlook.com
- GitHub：https://github.com/badhope/portfolio-website
如有问题或建议，欢迎提 Issue 或 Pull Request。
---
## 许可证
本项目基于 MIT 协议开源，详情见 [LICENSE](LICENSE) 文件。
```
---
