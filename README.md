# 星火指尖工作室官方网站 ✨

<div align="center">

![星火指尖工作室](images/工作室LOGO(带文字).svg)

**星星之火，可以燎原 | 指尖轻触，点燃梦想**

[![GitHub](https://img.shields.io/badge/GitHub-星火指尖工作室-blue?style=flat-square&logo=github)](https://github.com/bloodcube/my-SparkTip-Studio-website)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/zh-CN/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/zh-CN/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript)

</div>

---

## 📖 项目简介

这是**星火指尖工作室**的官方网站，展示我们的独立游戏作品、工作室理念和团队风采。

我们是一支充满激情的独立游戏开发团队，专注于手游开发，致力于为玩家打造独特而精彩的游戏体验。

## 🎮 正在开发的游戏

### 星辰之旅
一款融合冒险、RPG 和策略元素的手机游戏，目前开发进度 **65%**，预计 **2025 年夏季**上线。

**游戏特色：**
- 🌟 独特的宇宙世界观
- 👥 丰富的角色系统
- 🎯 策略性回合制战斗
- 🎨 精美的像素艺术风格

## ✨ 网站特点

### 🎨 视觉设计
- **现代深色主题**：采用深紫色调，营造神秘科技感
- **动态粒子效果**：首页炫酷的动态背景
- **渐变色设计**：多种渐变配色，视觉冲击力强
- **玻璃态导航栏**：现代时尚的毛玻璃材质

### 🚀 功能特性
- ✅ 响应式设计，完美适配桌面/平板/手机
- ✅ 平滑滚动动画
- ✅ 智能导航高亮
- ✅ 游戏展示卡片
- ✅ 开发进度可视化
- ✅ 愿望单互动功能
- ✅ 社交媒体链接
- ✅ 元素进入视口动画

### 💻 技术栈
- **HTML5** - 页面结构
- **CSS3** - 样式设计（包含动画、渐变、响应式）
- **JavaScript** - 交互逻辑
- **Font Awesome** - 图标库

## 📁 项目结构

```
星火指尖工作室官网/
│
├── index.html              # 主页面
├── README.md              # 项目说明文档
│
├── css/
│   └── style.css          # 样式文件
│
├── js/
│   └── main.js            # JavaScript 脚本
│
├── images/
│   ├── 工作室LOGO(带文字).svg
│   ├── 工作室LOGO(带文字+透明底).svg
│   └── 工作室LOGO(无文字).svg
│
└── pages/                 # 其他页面（预留）
```

## 🚀 快速开始

### 在线预览
直接访问我们的网站：[星火指尖工作室官网](#)

### 本地运行

1. **克隆项目**
```bash
git clone https://github.com/bloodcube/my-SparkTip-Studio-website.git
cd my-SparkTip-Studio-website
```

2. **打开网站**
直接用浏览器打开 `index.html` 文件即可！

> 💡 无需安装任何依赖，纯静态网站，开箱即用！

### 使用 Live Server（推荐）
如果你使用 VS Code，可以安装 **Live Server** 插件：
```bash
# 右键点击 index.html
# 选择 "Open with Live Server"
```

## 🎨 自定义配置

### 修改颜色主题
在 `css/style.css` 中的 `:root` 部分修改：
```css
:root {
    --primary-color: #6c5ce7;      /* 主色调 */
    --secondary-color: #00b894;     /* 次要色 */
    --accent-color: #fd79a8;        /* 强调色 */
    /* 更多颜色变量... */
}
```

### 修改内容
直接编辑 `index.html` 中的文字内容即可。

### 添加社交媒体链接
在 `index.html` 的联系我们部分，将 `href="#"` 替换为实际链接：
```html
<a href="https://weibo.com/你的微博" class="social-link">
    <i class="fab fa-weibo"></i>
</a>
```

## 📱 响应式断点

- **桌面端**：> 968px
- **平板端**：481px - 968px
- **手机端**：< 480px

## 🌟 核心功能说明

### 1. 粒子动画系统
首页背景的动态粒子效果，自动生成 50 个粒子并添加浮动动画。

### 2. 导航栏交互
- 滚动时自动收缩
- 当前页面智能高亮
- 移动端汉堡菜单

### 3. 愿望单功能
点击"加入愿望单"按钮，图标变化并显示通知提示。

### 4. 进度条动画
游戏开发进度条在滚动到视口时自动播放动画。

## 🤝 贡献指南

欢迎为星火指尖工作室官网贡献代码！

1. Fork 本仓库
2. 创建新分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m '添加某个很棒的功能'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 提交 Pull Request

## 📄 开源协议

本项目采用 [MIT License](LICENSE) 开源协议。

## 📞 联系我们

- **邮箱**: contact@studio.com
- **微博**: [@星火指尖工作室](#)
- **微信公众号**: 星火指尖工作室
- **QQ 群**: [点击加入](#)
- **Bilibili**: [星火指尖工作室](#)

## 💖 致谢

感谢以下开源项目：
- [Font Awesome](https://fontawesome.com/) - 图标库
- [Google Fonts](https://fonts.google.com/) - 字体支持

---

<div align="center">

**用指尖编织梦想，用星火点燃激情** 🔥

Made with ❤️ by 星火指尖工作室

© 2025 星火指尖工作室. All rights reserved.

</div>

