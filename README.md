<div align="center">

<img src="avatar.jpg" width="110" style="border-radius:50%" alt="avatar">

# 紫雲山人 · ineway

**仁義禮智信，溫良恭儉讓**

我的个人主页 —— 一个手写的极简静态站点，托管在 GitHub Pages 上。

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-在线访问-1a5c4a?style=flat-square&logo=github)](https://ineway.github.io)
[![HTML5](https://img.shields.io/badge/HTML5-单文件-E34F26?style=flat-square&logo=html5&logoColor=white)](index.html)
[![No Build](https://img.shields.io/badge/构建-零依赖-4a90d9?style=flat-square)](#技术栈)
[![License](https://img.shields.io/badge/License-MIT-8a8a8a?style=flat-square)](LICENSE)

[🌐 在线访问](https://ineway.github.io) · [🏠 自定义域名](https://chenronghui.com) · [👤 GitHub 主页](https://github.com/ineway)

</div>

---

## ✨ 关于这个项目

这是我在 GitHub 上的个人名片页。没有框架、没有构建工具、没有一行 JavaScript —— 只有一个 `index.html`，用最朴素的方式把「我是谁、我在做什么、去哪里找我」讲清楚。

写它的时候我正在学 Git，所以它也算是我练习版本控制的第一块试验田：每一次改动，都是一次 commit。

## 🖼 预览

| 项目 | 说明 |
|------|------|
| 页面结构 | 头像 → 姓名 → 格言 → 关于我 → 链接 |
| 设计风格 | 米白纸感底色 + 墨绿主色，中文排版优先 |
| 适配 | 响应式，手机 / 平板 / 桌面均可正常浏览 |
| 体积 | 单个 HTML 文件，约 3 KB |

## 🚀 快速开始

想在自己的电脑上看看效果，直接双击打开即可：

```bash
git clone git@github.com:ineway/ineway.github.io.git
cd ineway.github.io
open index.html        # macOS
```

或者起一个本地服务器（推荐，行为更接近线上）：

```bash
python3 -m http.server 8000
# 浏览器访问 http://localhost:8000
```

## 📁 目录结构

```
ineway.github.io/
├── index.html      # 唯一的页面文件（结构 + 样式全部内联）
├── avatar.jpg      # 头像图片
├── CNAME           # 自定义域名声明（chenronghui.com）
└── README.md       # 你正在读的这份文件
```

## 🛠 技术栈

- **HTML5** —— 语义化标签
- **原生 CSS** —— CSS 变量统一配色，无任何 UI 框架
- **零 JavaScript** —— 不需要交互逻辑，也就不引入运行时负担
- **GitHub Pages** —— 免费静态托管，push 即部署

配色变量集中在 `:root`，想换风格只改这几行：

```css
:root {
  --ink: #2b2b2b;      /* 正文 */
  --paper: #faf9f6;    /* 背景 */
  --accent: #1a5c4a;   /* 主色 */
  --line: #e6e3dc;     /* 分割线 */
}
```

## 🔄 更新与部署

修改内容后，三条命令即可上线，约 1 分钟自动生效：

```bash
git add .
git commit -m "更新主页内容"
git push
```

## 🌐 域名与托管说明

| 访问方式 | 地址 | 说明 |
|---------|------|------|
| GitHub 默认域名 | `ineway.github.io` | 国内访问可能间歇性不稳定 |
| 自定义域名 | `chenronghui.com` | 需在域名商配置 A / CNAME 记录 |
| www 子域 | `www.chenronghui.com` | CNAME 指向 `ineway.github.io` |

GitHub Pages 的 A 记录（裸域用）：

```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

## 📄 License

本项目采用 [MIT License](LICENSE)，随便用，不用打招呼。

<div align="center">

**© 2026 ineway** · Built with plain HTML, hosted free on GitHub Pages.

</div>
