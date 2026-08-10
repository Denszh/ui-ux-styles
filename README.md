# 🎨 UI/UX Pro Max — 84 种 UI 风格实景渲染

> 把 [UI/UX Pro Max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) 的 84 种 UI 风格，**每种风格渲染成一个真实可交互的完整界面** —— 不是效果图、不是设计稿，是浏览器里直接打开、可以滚动、可以 hover、带完整组件的真实网页。

## 🌐 在线预览

| 平台 | 地址 |
|------|------|
| **GitHub Pages** | https://denszh.github.io/ui-ux-styles/ |

下载整个仓库，双击 `index.html` 即可本地浏览，**断网也能用**（唯一外部引用是 Google Fonts，离线自动回退）。

## 📁 目录结构

```
ui-ux-styles-real/
├── index.html          # 入口索引页（可按分类筛选）
├── general/            # 通用风格 × 49 —— 完整产品网页
├── landing/            # 营销落地页 × 8 —— Hero + 特性 + 转化 CTA
├── dashboard/          # 数据看板 × 10 —— 纯 CSS 图表（柱状/折线/环形）
└── mobile/             # 移动端 × 17 —— 手机框内真实 App 界面
```

### 四种界面形态

| 分类 | 数量 | 渲染形态 |
|------|------|---------|
| 🎨 **General** | 49 | 完整产品网页：Hero + 特性 + 图表 + 统计 + 列表 + 表单 + CTA |
| 🚀 **Landing Page** | 8 | 营销落地页：围绕转化目标组织区块 |
| 📊 **BI/Analytics** | 10 | 数据看板：柱状图、折线图、环形进度，**全部纯 CSS 实现** |
| 📱 **Mobile** | 17 | 手机 App 界面：状态栏 + 导航 + 卡片 + 底部 Tab |

## ✨ 实现特点

- **纯 HTML + CSS，零依赖** —— 没有构建工具、没有 JS 框架、没有 npm install
- **每页自包含** —— 每种风格的完整 CSS 内联在 `<style>` 中，单个 HTML 拿走即用
- **设计系统变量** —— 每种风格用 `:root` 定义完整 token（颜色 / 圆角 / 阴影 / 字体）
- **语义化命名** —— 所有页面共用 `.nav` `.hero` `.card` `.stat` `.chart` `.tag` `.badge` 体系
- **20+ 视觉配方** —— 毛玻璃、赛博朋克（扫描线+霓虹）、像素风（8-bit 字体）、新拟态（双阴影）、蒸汽波（透视网格）……
- **纯 CSS 图表** —— BI 系列 10 个看板全部用 CSS 绘制，单页无需任何图表库
- **响应式** —— 桌面 / 平板 / 手机均可访问

## 🧭 风格分类速览

**通用风格 (49)**：极简主义 · 新拟态 · 毛玻璃 · 粗野主义 · 3D 超写实 · 暗黑 OLED · Claymorphism · Aurora UI · 蒸汽波 · 像素艺术 · 孟菲斯 · 赛博朋克 · 包豪斯 · Bento Grid · 编辑式杂志风 …

**落地页 (8)**：Hero 主导 · 转化优化 · 功能展示 · 极简直给 · 社会证明 · 交互式产品演示 · 信任权威 · 故事驱动

**数据看板 (10)**：数据密集型 · 热力图 · 高管驾驶舱 · 实时监控 · 下钻分析 · 对比分析 · 预测分析 · 用户行为 · 财务看板 · 销售智能

**移动端 (17)**：现代暗黑影院 · SaaS 高科 · 终端 CLI · 动能粗野 · 触控优先扁平 · Material You · 新粗野 · 大胆排版 · 学术风 · 赛博 HUD · Bitcoin DeFi · Claymorphism · 企业 SaaS · 手绘涂鸦 · 新拟态 …

## 🛠️ 本地开发

```bash
# 方式一：直接双击 index.html（本地文件协议）
open index.html

# 方式二：本地静态服务器（推荐，体验最完整）
python3 -m http.server 8000
# 访问 http://localhost:8000
```

## 📦 部署

仓库已配置 GitHub Pages（`main` 分支根目录），推送后自动发布：

```bash
git add -A && git commit -m "更新" && git push
```

约 1 分钟后访问 https://denszh.github.io/ui-ux-styles/

## 📄 数据来源

- 风格数据来自 [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) 的 `src/ui-ux-pro-max/data/styles.csv`
- 生成脚本按风格匹配视觉配方，产出对应类型的完整界面

## 📄 License

MIT
