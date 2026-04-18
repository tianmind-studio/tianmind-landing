<h1 align="center">tianmind-landing</h1>
<p align="center">
  <b>独立开发者 / 代码工作室品牌着陆页模板</b><br>
  <sub>Indie dev / software studio landing page template — zero build, zero deps</sub>
</p>

<p align="center">
  <a href="https://491034170.github.io/tianmind-landing"><img src="https://img.shields.io/badge/Live_Demo-View-4facfe?style=flat-square"/></a>
  <a href="./LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square"/></a>
  <img src="https://img.shields.io/badge/Dependencies-Zero-2EA043?style=flat-square"/>
  <img src="https://img.shields.io/badge/Deploy-GitHub_Pages_|_Cloudflare-F38020?style=flat-square"/>
</p>

---

## ✨ 特点 / Features

- 🎨 **Blueprint / 工程图纸美学** — 深蓝渐变 + 发光蓝 + 精细网格 + 工业编号
- 🌏 **中英双语** — 一键切换,localStorage 记忆偏好
- ⚡ **零构建 / 零依赖** — 纯 HTML + CSS + JS,直接部署
- 📱 **完全响应式** — 手机到 4K 显示器都能看
- 💫 **流畅微交互** — 滚动淡入、数字计数、Hero 电源图标呼吸发光、hover 刻线延伸
- 🔤 **独特字体组合** — Syne + JetBrains Mono + Archivo (非 Inter / 非 Space Grotesk)
- ♿ **尊重 `prefers-reduced-motion`** — 关闭动画时自动降级
- 🚀 **一键 Fork 可用** — 改内容就是你的品牌页

---

## 🧩 页面结构 / Sections

1. **Hero** — 品牌标语 + 核心指标 + 电源图标动画
2. **Manifesto** — 3 条工作底线
3. **Services** — 6 类服务(工程图纸卡片)
4. **Tech Stack** — 4 栏技术栈
5. **Featured Work** — 代表作品链接
6. **Pricing** — 报价表 + 6 步合作流程
7. **FAQ** — 6 个预防问题
8. **Contact** — 淘宝 / 邮件 / 官网 / GitHub 四卡片

---

## 🚀 快速开始 / Quick start

### 方式一:Fork 后改

```bash
# 1. Fork 到自己的账号
# 2. Clone 下来
git clone https://github.com/YOUR_USERNAME/tianmind-landing.git
cd tianmind-landing

# 3. 改文案(index.html) + 改颜色(styles.css 顶部 :root 变量)
# 4. 推回 GitHub,启用 Pages 即可
```

### 方式二:直接部署到 Cloudflare Pages

1. Fork 本仓库
2. [Cloudflare Pages](https://pages.cloudflare.com) → 连接 Git → 选 fork 后的仓库
3. Build command 留空,Output directory 设为 `/`
4. Deploy

---

## 🎨 自定义 / Customization

### 换品牌色(styles.css 顶部)

```css
:root {
  --accent: #4FACFE;         /* 主色 */
  --accent-bright: #00F2FE;  /* 渐变终点 */
  --accent-warm: #FFD89B;    /* 点缀色(淘宝卡片) */
  --bg: #050B18;             /* 深背景 */
}
```

### 换字体(index.html `<link>` 标签)

Google Fonts 替换 `Syne`、`Archivo`、`JetBrains Mono` 为你的选择,同步改 `--font-display` 等变量。

### 改文案

- **中文文案**:直接改 `index.html` 中 `data-i18n` 元素的内容
- **英文文案**:改 `assets/app.js` 里 `i18n.en` 对象
- **中英文本对照位置**一致,方便同步维护

---

## 📂 文件说明

```
tianmind-landing/
├── index.html           # 结构 + 中文默认文案
├── assets/
│   ├── styles.css       # 全部样式(单文件)
│   └── app.js           # 语言切换 + 动画 + 滚动触发
├── README.md
└── LICENSE
```

---

## 🎯 谁适合用

- 想自建品牌页的独立开发者 / Freelancer
- 小团队 / 工作室对外宣传
- Claude Code / AI 开发者想做作品集
- 任何需要"快速有一个像样官网"的场景

---

## 📬 支持 / Contact

模板由 **[天智工坊 · Tianmind Studio](https://tianmind.com)** 设计开发。
Designed & built by [Tianmind Studio](https://tianmind.com).

- 🌐 官网:[tianmind.com](https://tianmind.com)
- 📧 邮箱:wx@tianmind.com
- 🛒 淘宝店铺:搜索「**天智工坊**」— 定制版本可联系报价

---

## License

MIT © 2026 天智工坊 · Tianmind Studio

<sub>If you use this template, a ⭐ Star means a lot. Happy shipping.</sub>
