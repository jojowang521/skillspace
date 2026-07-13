# Skill Forge · AI Product & Design Skill Workspace

> **TRAE AI 创造力大赛 · 学习工作赛道 · 初赛提交作品**
> Build AI Skills That Grow with Your Team · 让团队经验，持续成长为 AI 能力

## 在线体验

**GitHub Pages Demo**:https://jojowang521.github.io/skillspace/

打开链接,2.5 秒后自动进入 9 视图演示。

## 仓库内容

```
skillspace/
├── demo.html              ← 主 Demo(9 视图单页应用)
├── index.html             ← 入口页(品牌信息 + 自动跳转)
├── 404.html               ← 友好 404 兜底
├── README.md              ← 本文件
├── _config.yml            ← Jekyll 配置(已禁用 Jekyll 构建)
├── .nojekyll              ← 跳过 Jekyll 处理
├── assets/                ← 产品截图(3 张)
│   ├── hero_1280x720.jpg
│   ├── lifecycle_1280x720.jpg
│   └── demo_1152x864.jpg
└── _shared/
    └── fonts/             ← Demo 使用的字体文件
        ├── InstrumentSans-Regular.ttf
        ├── InstrumentSans-Bold.ttf
        └── GeistMono-Regular.ttf
```

## Demo 介绍

Skill Forge 是一个**单页交互式 Demo 网站**(纯 HTML/CSS/JS,无后端依赖),跑在浏览器里 9 个连续视图,完整演示"团队知识 → AI Skill → TRAE 协作 → Skill 评审 → 持续进化"的产品闭环。

### 9 个视图概览

| # | 视图 | 关键内容 |
|---|---|---|
| v1 | 开场故事 | 设计师小序接手 ERP 支付模块的场景 |
| v2 | 知识上传 | 上传 PRD / Figma / Excel / Word 等团队资料 |
| v3 | AI 分析 | 自动抽取 Knowledge / Pattern / Workflow / Rule |
| v4 | 生成 Skill | Product Skill + Design Skill 双卡,含 Skill Capability |
| v5 | Skill 编辑器 | 可编辑 + 建议规则块 + Source 引用 + 保存 v1.0 |
| v6 | Use in TRAE 桥接 | 三段式加载:已选 Skill / 上下文 / 目标工作区 |
| v7 | TRAE 工作区 | 5 轮对话自动播放(约 8 秒)+ Output Preview |
| v8 | Skill 评审 | Overall Score 82→94 + Issue Why/Severity/Related Rule |
| v9 | Skill 进化 | Before/After v1.0→v1.1 对比 + 时间线 + Replay |

### 核心交互

- **顶部 9 项导航** + **左侧 5 项 Sidebar** 双向切换
- v7 TRAE 对话**自动播放**完整流程
- v8 评审可点 "应用建议" 看 82→94 分数变化中间状态
- v9 进化可点 "更新 Skill 到 v1.1" 看 Before/After 对比
- v9 末尾 "Replay Demo" 一键重置所有交互状态

## 本地使用

```bash
git clone https://github.com/jojowang521/skillspace.git
cd skillspace

# 方式 A:直接双击 demo.html
open demo.html

# 方式 B:本地静态服务器(推荐,字体加载更稳定)
python3 -m http.server 8000
# 访问 http://localhost:8000
```

## 技术栈

- 纯 HTML + CSS + JavaScript,无后端依赖
- ~1660 行单页应用,自包含
- 9 视图 View 切换 + 侧边栏联动 + TRAE 对话自动播放 + 评分变化动画 + Skill 版本演进时间线

## 浏览器要求

Chrome 90+ / Edge 90+ / Safari 14+ / Firefox 88+,需开启 JavaScript。

## 作品背景

- **产品名**:Skill Forge
- **定位**:AI Product & Design Skill Workspace
- **核心创新**:Skill Lifecycle 框架——Knowledge → Pattern → Workflow → Rule → Skill → TRAE 集成 → 评审 → 进化
- **目标用户**:B 端产品设计师 / 设计经理 / 设计工程师

## 联系方式

- GitHub:[@jojowang521](https://github.com/jojowang521)
- 赛事:TRAE AI 创造力大赛 2026
