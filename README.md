# Modern Developer Portfolio Template
> 面向开发者的现代化、响应式个人作品集网站模板 | 开箱即用 | 高可定制 | 全设备兼容

[![GitHub Stars](https://img.shields.io/github/stars/badhope/portfolio-website?style=flat-square&logo=github)](https://github.com/badhope/portfolio-website/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/badhope/portfolio-website?style=flat-square&logo=github)](https://github.com/badhope/portfolio-website/network/members)
[![GitHub License](https://img.shields.io/github/license/badhope/portfolio-website?style=flat-square)](https://github.com/badhope/portfolio-website/blob/main/LICENSE)
[![Vercel Deploy](https://img.shields.io/github/deployments/badhope/portfolio-website/production?style=flat-square&logo=vercel&label=deploy-status)](https://badhope.github.io/portfolio-website/)
[![Code Size](https://img.shields.io/github/languages/code-size/badhope/portfolio-website?style=flat-square)](https://github.com/badhope/portfolio-website)
[![Last Commit](https://img.shields.io/github/last-commit/badhope/portfolio-website?style=flat-square)](https://github.com/badhope/portfolio-website/commits/main)

## 📖 项目简介
这是一套专为开发者打造的**开箱即用型个人作品集网站模板**，基于语义化HTML5、Tailwind CSS和原生JavaScript构建，完美适配全栈/前端/后端/运维等技术从业者快速搭建个人线上主页。
模板预设了个人简介、技能栈展示、项目作品、技术博客、联系方式等核心模块，无需复杂的框架学习成本，即使是仅掌握HTML/CSS基础的新手，也能快速完成个性化修改与上线部署。

👉 在线预览：[https://badhope.github.io/portfolio-website/](https://badhope.github.io/portfolio-website/)

## ✨ 核心特性
### 技术向核心优势
1. **语义化原生技术栈**：基于HTML5+CSS3+原生JavaScript开发，无过重框架依赖，兼容性强，二次开发门槛极低
2. **原子化CSS架构**：采用Tailwind CSS实现样式开发，支持一键自定义主题色、字体、间距，告别冗余CSS代码
3. **全响应式布局**：从移动端到桌面端全尺寸设备完美适配，基于Flex/Grid实现流式布局，无横向滚动与样式错乱
4. **SEO友好优化**：完整的语义化标签结构、meta标签预设，支持搜索引擎快速收录，适配个人品牌线上曝光
5. **模块化代码结构**：页面模块完全解耦，支持一键新增/删减/调整模块顺序，无需重构整体代码
6. **极速首屏加载**：轻量化代码体积，静态资源按需加载，无冗余依赖，首屏加载速度优于90%以上的同类模板
7. **多部署方案兼容**：原生支持GitHub Pages、Vercel、Netlify、云服务器、虚拟主机等几乎所有部署方式，零成本上线

### 开箱即用的功能模块
- 🏠 英雄区(Hero)：个人身份与核心定位快速展示
- 👤 关于我：个人履历、从业经验、学历背景等基础信息展示
- 🛠️ 技能栈：多维度技能进度展示、技术标签云，清晰呈现技术能力
- 📂 项目作品：分类式项目卡片展示，支持筛选、跳转预览与仓库地址
- 📝 技术博客：文章列表与分类管理，支持对接第三方博客平台
- 📞 联系方式：多渠道联系入口，支持表单提交与直连方式

## 🛠️ 技术栈
| 技术分类 | 核心技术 | 说明 |
|----------|----------|------|
| 结构层 | HTML5 | 语义化标签，SEO友好，兼容所有现代浏览器 |
| 样式层 | Tailwind CSS 3.x + CSS3 | 原子化样式开发，支持自定义主题，响应式断点预设 |
| 交互层 | 原生JavaScript (ES6+) | 无框架依赖，轻量交互实现，平滑滚动、分类筛选等功能 |
| 构建工具 | 可选Vite/Webpack | 支持原生HTML直接运行，也可接入构建工具实现工程化开发 |
| 部署兼容 | GitHub Pages/Vercel/Netlify/云服务器 | 全平台部署支持，提供一键部署方案 |
| 扩展兼容 | React/Vue/Next.js/Nuxt.js | 支持无缝迁移至主流前端框架，适配SSR/SSG场景 |

## 🚀 快速开始
### 环境准备
- 基础运行：仅需现代浏览器与代码编辑器（VS Code推荐），无需Node.js环境
- 进阶开发：Node.js 16.x+ 、Git、npm/yarn/pnpm包管理器

### 1. 获取项目
#### 方式一：直接下载（零门槛，新手推荐）
1. 进入项目仓库：[https://github.com/badhope/portfolio-website](https://github.com/badhope/portfolio-website)
2. 点击 `Code` -> `Download ZIP` 下载完整项目压缩包
3. 解压后用代码编辑器打开文件夹，直接修改 `index.html` 即可完成个性化配置

#### 方式二：Git克隆（开发者推荐）
```bash
# 克隆仓库到本地
git clone https://github.com/badhope/portfolio-website.git

# 进入项目目录
cd portfolio-website
```

#### 方式三：一键Fork（用于GitHub Pages部署）
直接点击仓库右上角 `Fork` 按钮，复制完整项目到自己的GitHub账号下，即可开始自定义修改。

### 2. 本地运行
#### 原生HTML直接运行（无依赖）
直接用浏览器打开项目根目录下的 `index.html` 文件，即可实时预览效果，修改代码后刷新浏览器即可更新。

#### 带构建工具的开发模式（进阶使用）
```bash
# 安装依赖
npm install

# 启动本地开发服务器（带热更新）
npm run dev

# 构建生产环境产物
npm run build
```

## ⚙️ 个性化配置
模板所有内容均支持无代码基础的可视化修改，核心配置均集中在 `index.html` 中，无需修改复杂的逻辑代码。

### 1. 基础个人信息配置
直接修改HTML中对应标签的文本内容，即可完成个人核心信息更新：
- 姓名、职业定位、个人简介（Hero区与关于我模块）
- 所在地、从业年限、邮箱、学历、电话、地址等联系方式
- 社交账号链接（GitHub、LinkedIn、掘金、知乎等，可自行新增）

### 2. 技能栈配置
- 技能进度条：修改 `data-percent` 属性值，即可调整技能熟练度百分比展示
- 技能分类：支持新增/删减前端开发、后端开发、DevOps等分类模块
- 技术标签：修改标签云内的文本，即可自定义个人技术标签

### 3. 项目作品配置
- 项目卡片：复制预设的项目卡片DOM结构，即可新增项目；删除对应DOM即可移除项目
- 项目分类：支持自定义Web应用、移动端、API后端、开源工具等分类，实现筛选功能
- 项目信息：修改项目名称、描述、技术标签、预览链接、GitHub仓库地址即可

### 4. 样式主题自定义
在 `tailwind.config.js` 中修改主题配置，一键更换全站主题色、字体、圆角、间距等：
```javascript
// tailwind.config.js 示例
module.exports = {
  theme: {
    extend: {
      colors: {
        primary: '#你的主题色',
        secondary: '#你的辅助色',
      },
      fontFamily: {
        sans: ['你的字体', 'system-ui', 'sans-serif'],
      },
    },
  }
}
```

### 5. 模块自定义
- 删减模块：直接删除HTML中对应模块的完整DOM结构，不影响其他模块运行
- 新增模块：参考预设模块的DOM结构，新增自定义模块（如获奖经历、开源贡献、服务案例等）

## 📦 部署指南
### 方案一：GitHub Pages 部署（零成本，永久免费，强烈推荐）
1. 将修改后的项目代码推送到你的GitHub仓库
2. 进入仓库 `Settings` -> `Pages`
3. 在 `Build and deployment` 中，Source选择 `Deploy from a branch`
4. Branch选择 `main` ，文件夹选择 `/root` ，点击Save
5. 等待1-2分钟，即可通过 `https://你的用户名.github.io/仓库名/` 访问你的个人网站

### 方案二：Vercel 一键部署（全球CDN，自动更新，推荐）
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/badhope/portfolio-website)
1. 点击上方一键部署按钮，使用GitHub账号登录Vercel
2. 确认仓库信息，点击Deploy，等待30秒即可完成部署
3. 后续修改代码推送到GitHub，Vercel会自动完成更新部署

### 方案三：云服务器/虚拟主机部署
1. 执行 `npm run build` 构建生产环境产物（原生HTML直接使用根目录文件）
2. 将产物文件上传到服务器的网站根目录
3. 配置Nginx（示例）：
```nginx
server {
    listen 80;
    server_name 你的域名.com;
    root /var/www/portfolio;
    index index.html;

    location / {
        try_files $uri $uri/ /index.html;
    }
}
```
4. 解析域名到服务器IP，即可通过域名访问

## 📁 项目结构
```
portfolio-website/
├── index.html          # 主页面入口，完整的HTML结构与内容配置
├── tailwind.config.js  # Tailwind CSS 主题与自定义配置
├── package.json        # 项目依赖与构建脚本配置
├── .gitignore          # Git忽略文件配置
├── src/
│   ├── css/
│   │   └── main.css    # 全局样式入口，Tailwind指令与自定义样式
│   ├── js/
│   │   └── main.js     # 全局交互逻辑，平滑滚动、分类筛选等功能
│   └── assets/         # 静态资源目录
│       ├── images/     # 头像、项目截图、banner等图片资源
│       └── icons/      # favicon、社交图标等图标资源
├── public/             # 构建产物输出目录
├── LICENSE             # 开源许可证
└── README.md           # 项目说明文档
```

## 🤝 参与贡献
我们非常欢迎社区开发者参与本项目的贡献，让这个模板变得更好！
- 🐛 提交Issue：反馈Bug、提出功能建议、优化想法
- 🔧 提交PR：修复Bug、新增功能、优化代码、完善文档
- ✨ 分享推广：Star本项目，分享给更多开发者朋友，让更多人受益

### 贡献步骤
1. Fork本仓库
2. 创建你的功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交你的修改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开一个Pull Request

## 📄 开源许可证
本项目基于 **MIT License** 开源，你可以：
- ✅ 免费商用、个人使用
- ✅ 修改、二次开发、分发代码
- ✅ 私有使用
- 仅需保留原作者的版权声明与许可证信息，无其他限制

完整许可证内容见 [LICENSE](https://github.com/badhope/portfolio-website/blob/main/LICENSE)

## ❓ 常见问题
1. **我只会HTML和CSS，能使用这个模板吗？**
完全可以！模板核心内容都在index.html中，只需修改对应文本内容，无需修改逻辑代码，零前端基础也能快速上手。

2. **可以用于商业用途吗？**
可以，基于MIT协议，你可以自由用于个人、商业项目，无需额外授权。

3. **怎么添加深色模式？**
模板已预留深色模式适配入口，只需在tailwind.config.js中开启darkMode，添加对应的深色样式类即可，仓库Wiki提供了完整的深色模式适配教程。

4. **怎么对接自己的博客系统？**
支持对接WordPress、Notion、VuePress、Hexo等博客系统，只需修改博客模块的链接，或通过API拉取博客列表渲染即可。

## 💖 鼓励与支持
如果这个模板帮你快速搭建了属于自己的个人网站，欢迎给本项目点一个 **Star** ⭐，这是对我们最大的鼓励与支持！

也欢迎你把这个模板分享给身边的开发者朋友，让更多人能零成本搭建自己的线上个人品牌主页。

有任何使用问题，都可以在仓库Issue区留言，我们会尽快回复解答。
