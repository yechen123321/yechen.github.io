# David的博客

一个基于 VitePress 构建的个人技术博客，专注于全栈开发技术分享。

## 功能特性

- 📝 技术文章分享
- 🎨 现代化设计界面
- 📱 响应式布局
- 🔍 本地搜索功能
- 🌙 深色模式支持
- ⚡ 快速加载

## 技术栈

- [VitePress](https://vitepress.dev/) - 静态站点生成器
- [Vue 3](https://vuejs.org/) - 前端框架
- [Vite](https://vitejs.dev/) - 构建工具

## 本地开发

```bash
# 安装依赖
npm install

# 启动开发服务器
npm run dev

# 构建生产版本
npm run build

# 预览构建结果
npm run preview
```

## 部署到 GitHub Pages

### 方式一：用户名.github.io 仓库（推荐）
1. 将代码推送到名为 `用户名.github.io` 的仓库（如：yechen123321.github.io）
2. 在 GitHub 仓库设置中启用 Pages
3. 选择 "GitHub Actions" 作为部署源
4. 推送代码到 `main` 分支会自动触发部署
5. 网站将在 `https://用户名.github.io` 访问

### 方式二：普通仓库
1. 修改 `docs/.vitepress/config.js` 中的 `base` 为 `"/仓库名/"`
2. 推送到任意仓库名
3. 网站将在 `https://用户名.github.io/仓库名` 访问

## 项目结构

```
.
├── docs/                 # 文档源文件
│   ├── .vitepress/       # VitePress 配置
│   │   ├── config.js     # 站点配置
│   │   └── theme/        # 主题文件
│   ├── about/            # 关于页面
│   ├── blog/             # 博客文章
│   ├── contact/          # 联系页面
│   ├── projects/         # 项目展示
│   └── public/           # 静态资源
├── .github/workflows/    # GitHub Actions
└── package.json          # 项目配置
```

## 许可证

MIT License