# tianmind-landing

天智工坊（TianMind Studio）企业数字化与 AI 落地服务着陆页。

面向中小企业的数字化转型与 AI Agent 落地咨询，中英双语，零构建、零依赖、可 fork、可部署。

## 核心定位

- **企业数字化转型**：从官网建设到内部管理系统
- **AI Agent 落地**：Claude Skill、Agent 工作流、Prompt 工程
- **本地化交付**：可签合同、可开发票、源码完整交付

## Features / 特性

- Blueprint 工程图纸风格设计，深色背景、渐变高光
- 中英双语切换（无需刷新）
- 纯静态 HTML/CSS/JS，零构建依赖
- 响应式布局，适配移动端
- 开源贡献与能力证明区块
- 悬浮咨询按钮（移动端）
- 无障碍友好（ARIA labels、reduced motion 支持）
- SEO 优化（Open Graph、Twitter Cards）

## Page Sections / 页面结构

1. **Hero** — 企业 AI 落地专家定位 + 免费咨询 CTA
2. **Manifesto** — 三条底线：阶段交付、不转包、长期售后
3. **Services** — 6 大服务方向（官网、后台、小程序、SaaS、AI、运维）
4. **Tech Stack** — 技术栈展示
5. **Featured Work** — 开源项目与作品
6. **Capabilities** — 能力证明：开源贡献（Omi）、AI 落地、自研工具链
7. **Pricing** — 透明报价 + 合作流程
8. **FAQ** — 常见问题解答
9. **Contact** — 联系方式（淘宝、邮件、GitHub）

## Quick Start / 快速开始

```bash
# 克隆仓库
git clone https://github.com/491034170/tianmind-landing.git
cd tianmind-landing

# 本地预览（任选一种方式）
# 方式 1: Python
python3 -m http.server 8000

# 方式 2: Node.js
npx serve .

# 方式 3: 直接打开 index.html
open index.html
```

然后访问 `http://localhost:8000` 预览。

## 文件结构

```
tianmind-landing/
├── index.html          # 主页面
├── assets/
│   ├── styles.css      # 样式（含响应式）
│   └── app.js          # 交互 + i18n
├── articles/           # 技术文章
├── README.md
└── LICENSE
```

## 自定义 / Customization

### 修改内容

- `index.html` — 页面结构和默认中文内容
- `assets/app.js` — i18n 对象中的中英文文案
- `assets/styles.css` — 颜色变量和视觉样式

### 品牌色

编辑 `assets/styles.css` 顶部的 CSS 变量：

```css
:root {
  --accent: #4facfe;       /* 主色 */
  --accent-bright: #00f2fe; /* 亮色 */
  --accent-warm: #ffd89b;   /* 暖色 */
  --bg: #050b18;            /* 背景 */
}
```

## 部署 / Deployment

### GitHub Pages

1. 在仓库 Settings → Pages 中启用
2. Source 选择 `main` branch，`/ (root)`
3. 等待几分钟，访问 `https://<username>.github.io/tianmind-landing/`

### Cloudflare Pages

1. 连接 GitHub 仓库到 Cloudflare Pages
2. 构建设置：
   - Build command: （留空）
   - Output directory: `/`
3. 部署完成后绑定自定义域名

### VPS / 自有服务器

```bash
# 使用 nginx
cp -r tianmind-landing /var/www/html/
# 配置 nginx server block 指向该目录

# 或使用 site-bootstrap（天智工坊自研工具）
site-bootstrap deploy --domain your-domain.com
```

## 性能与无障碍

- **预加载字体**：Google Fonts 已配置 `preconnect`
- **Reduced motion**：支持 `prefers-reduced-motion` 媒体查询
- **语义化 HTML**：使用正确的 heading 层级和 ARIA labels
- **移动端优化**：悬浮咨询按钮、触摸友好间距
- **图片**：OG 图片已优化为 1200x630

## 注意事项

### 内容准则

- 不捏造客户名称或营收数字
- 不发布虚假评价
- 开源贡献标注来源，可公开核查
- 保持中英文内容一致性

### 隐私边界

不要发布：
- 客户私有文件或对话记录
- 凭证、tokens、密钥
- 未经授权的合同内容
- 私有后台截图

## 联系 / Contact

天智工坊 · TianMind Studio

- 官网: <https://tianmind.com>
- GitHub: <https://github.com/491034170>
- 邮箱: `wx@tianmind.com`
- 淘宝: 搜索「天智工坊」

## License

MIT © TianMind Studio / 天智工坊
