# 🎬 酷炫电影网站

一个基于 React + TypeScript + Tailwind CSS 构建的现代化电影展示平台，提供流畅的用户体验和精美的视觉设计。

## ✨ 功能特性

### 🎯 核心功能
- **电影浏览** - 精美的电影卡片展示，支持网格和列表视图
- **智能搜索** - 实时搜索电影标题、演员和描述
- **分类筛选** - 按类型（动作、科幻、剧情等）快速筛选
- **详情展示** - 丰富的电影详情页，包含演员信息、剧情简介
- **响应式设计** - 完美适配桌面端、平板和移动设备

### 🎨 设计特色
- **现代化UI** - 采用最新设计趋势，简洁而不失优雅
- **流畅动画** - 精心设计的过渡动画和交互效果
- **暗色主题** - 护眼的深色配色方案
- **视觉层次** - 清晰的信息架构和视觉引导

### 🚀 技术亮点
- **TypeScript** - 类型安全，提升开发效率
- **Zustand** - 轻量级状态管理
- **React Router** - 单页应用路由管理
- **Tailwind CSS** - 原子化CSS框架
- **Lucide Icons** - 精美的图标库

## 🛠️ 技术栈

### 前端框架
- **React 18** - 现代化前端框架
- **TypeScript** - 静态类型检查
- **Vite** - 快速构建工具

### 样式方案
- **Tailwind CSS** - 原子化CSS框架
- **PostCSS** - CSS后处理器
- **Autoprefixer** - 自动添加浏览器前缀

### 状态管理
- **Zustand** - 轻量级状态管理库
- **React Hooks** - 组件状态管理

### 路由导航
- **React Router DOM** - 客户端路由

### 开发工具
- **ESLint** - 代码质量检查
- **TypeScript ESLint** - TypeScript代码规范
- **Vite Plugin React** - React开发支持

## 📦 安装和运行

### 环境要求
- Node.js >= 18.0.0
- pnpm >= 8.0.0 (推荐) 或 npm >= 9.0.0

### 快速开始

1. **克隆项目**
```bash
git clone https://github.com/xiaoweiruby/cool-movie-website.git
cd cool-movie-website
```

2. **安装依赖**
```bash
# 使用 pnpm (推荐)
pnpm install

# 或使用 npm
npm install
```

3. **启动开发服务器**
```bash
# 使用 pnpm
pnpm dev

# 或使用 npm
npm run dev
```

4. **打开浏览器**
访问 [http://localhost:5173](http://localhost:5173) 查看网站

### 构建部署

```bash
# 构建生产版本
pnpm build

# 预览构建结果
pnpm preview
```

## 📁 项目结构

```
src/
├── components/          # 可复用组件
│   ├── HeroSection.tsx     # 首页英雄区域
│   ├── MovieCard.tsx       # 电影卡片组件
│   ├── MovieGrid.tsx       # 电影网格布局
│   ├── Navbar.tsx          # 导航栏组件
│   └── PopularMoviesCarousel.tsx # 热门电影轮播
├── pages/               # 页面组件
│   ├── Home.tsx            # 首页
│   ├── MovieDetail.tsx     # 电影详情页
│   ├── GenrePage.tsx       # 分类页面
│   ├── SearchResults.tsx   # 搜索结果页
│   └── NotFound.tsx        # 404页面
├── store/               # 状态管理
│   └── movieStore.ts       # 电影数据状态
├── data/                # 静态数据
│   └── movies.ts           # 电影数据
├── types/               # 类型定义
│   └── movie.ts            # 电影相关类型
├── hooks/               # 自定义Hooks
│   └── useTheme.ts         # 主题管理Hook
├── lib/                 # 工具函数
│   └── utils.ts            # 通用工具函数
└── assets/              # 静态资源
    └── react.svg           # React图标
```

## 🎯 核心功能说明

### 电影数据管理
- 使用 Zustand 进行全局状态管理
- 支持电影搜索、筛选和排序
- 响应式数据更新

### 路由系统
- 首页 (`/`) - 展示热门电影和分类
- 电影详情 (`/movie/:id`) - 单个电影的详细信息
- 分类页面 (`/genre/:genre`) - 按类型筛选电影
- 搜索结果 (`/search`) - 搜索结果展示

### 响应式设计
- 移动端优先的设计理念
- 灵活的网格布局系统
- 自适应的组件设计

## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request！

### 开发规范

本项目遵循 [Conventional Commits](https://www.conventionalcommits.org/) 规范：

- `feat`: 新功能
- `fix`: 修复问题
- `docs`: 文档更新
- `style`: 代码格式调整
- `refactor`: 代码重构
- `test`: 测试相关
- `chore`: 构建过程或辅助工具的变动

### 提交示例
```bash
git commit -m "feat(search): 添加高级搜索功能"
git commit -m "fix(ui): 修复移动端布局问题"
git commit -m "docs: 更新README文档"
```

## 📄 许可证

MIT License - 详见 [LICENSE](LICENSE) 文件

## 🙏 致谢

- [React](https://reactjs.org/) - 前端框架
- [Tailwind CSS](https://tailwindcss.com/) - CSS框架
- [Lucide](https://lucide.dev/) - 图标库
- [Zustand](https://github.com/pmndrs/zustand) - 状态管理

---

⭐ 如果这个项目对你有帮助，请给它一个星标！