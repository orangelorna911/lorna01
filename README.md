# 古诗词智能文档 📚

> 传统文化与智能技术的完美融合，精选古诗词作品集，提供深入的文学赏析和文化传承，弘扬中华优秀传统文化。

[![Deploy Status](https://github.com/orangelorna911/lorna01/workflows/Deploy%20VitePress%20site%20to%20Remote%20Server/badge.svg)](https://github.com/orangelorna911/lorna01/actions)
[![VitePress](https://img.shields.io/badge/VitePress-1.6.3-blue.svg)](https://vitepress.dev/)
[![Vue](https://img.shields.io/badge/Vue-3.5.18-green.svg)](https://vuejs.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## ✨ 项目特色

- 📝 **古诗词赏析** - 按照朝代、体裁、主题分类整理古诗词，提供深入的文学赏析和智能解读
- 🏛️ **怀古诗词** - 怀古咏史类诗词，感怀历史兴衰，抒发人生感慨
- 🏔️ **山水诗词** - 描绘自然山水，表达对自然的热爱与感悟，体现人与自然的和谐统一
- 💝 **抒情诗词** - 抒发个人情感，表达内心世界的真挚感受，展现诗人的情感世界
- 🔍 **智能搜索** - 支持全文搜索，快速定位所需内容
- 📱 **响应式设计** - 完美适配桌面端和移动端设备
- 🌙 **深色模式** - 支持明暗主题切换，保护视力

## 📖 内容分类

### 🏺 古诗词四大主题

| 分类 | 描述 | 特点 |
|------|------|------|
| [边塞诗](./docs/frontier/) | 描写边疆风光和军旅生活 | 雄浑壮阔，豪迈奔放 |
| [怀古诗](./docs/history/) | 咏史怀古，感慨兴衰 | 深沉厚重，哲理深刻 |
| [山水诗](./docs/landscape/) | 描绘自然山水美景 | 清新自然，意境深远 |
| [抒情诗](./docs/lyrical/) | 抒发个人情感世界 | 真挚感人，情深意切 |

## 🚀 快速开始

### 环境要求

- Node.js >= 18.0.0
- npm >= 8.0.0 或 pnpm >= 7.0.0

### 安装依赖

```bash
# 克隆项目
git clone https://github.com/orangelorna911/lorna01.git
cd lorna01

# 安装依赖（使用淘宝镜像源）
npm config set registry https://registry.npmmirror.com
npm install
```

### 本地开发

```bash
# 启动开发服务器
npm run docs:dev

# 访问 http://localhost:5173
```

### 构建部署

```bash
# 构建生产版本
npm run docs:build

# 预览构建结果
npm run docs:preview

# 部署到远程服务器
npm run deploy
```

## 🛠️ 技术栈

- **框架**: [VitePress](https://vitepress.dev/) - 基于 Vite 和 Vue 的静态站点生成器
- **前端**: [Vue 3](https://vuejs.org/) - 渐进式 JavaScript 框架
- **构建工具**: [Vite](https://vitejs.dev/) - 下一代前端构建工具
- **样式**: CSS3 + 响应式设计
- **搜索**: 本地搜索引擎
- **部署**: GitHub Actions + SSH 自动化部署

## 📁 项目结构

```
lorna01/
├── .github/
│   └── workflows/          # GitHub Actions 工作流
├── .vitepress/
│   └── config.js          # VitePress 配置文件
├── docs/                  # 文档源文件
│   ├── frontier/          # 边塞诗词
│   ├── history/           # 怀古诗词
│   ├── landscape/         # 山水诗词
│   ├── lyrical/           # 抒情诗词
│   └── index.md           # 首页
├── public/                # 静态资源
├── package.json           # 项目配置
└── README.md             # 项目说明
```

## 🔧 配置说明

### VitePress 配置

项目使用 VitePress 作为静态站点生成器，主要配置包括：

- **自动侧边栏生成**: 使用 `vitepress-sidebar` 插件自动生成导航
- **搜索功能**: 内置本地搜索，支持中文分词
- **主题定制**: 自定义主题色彩和布局
- **SEO 优化**: 完善的 meta 标签和 Open Graph 配置

### 部署配置

支持多种部署方式：

1. **GitHub Pages**: 自动部署到 GitHub Pages
2. **远程服务器**: 通过 SSH 部署到自定义服务器
3. **CDN**: 支持各种 CDN 服务

详细部署配置请参考 [DEPLOYMENT.md](./DEPLOYMENT.md)

## 🤝 贡献指南

我们欢迎所有形式的贡献！

### 贡献类型

- 📝 **内容贡献**: 添加新的古诗词作品和赏析
- 🐛 **问题反馈**: 报告 bug 或提出改进建议
- 💡 **功能建议**: 提出新功能或优化建议
- 🔧 **代码贡献**: 提交代码改进或新功能

### 贡献流程

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

### 内容规范

- 古诗词内容需要准确无误
- 赏析文字要求原创，避免抄袭
- 遵循项目的文档格式规范
- 提交前请检查链接有效性

## 📊 项目统计

- 📚 **诗词分类**: 4 个主要分类
- 📝 **收录作品**: 持续更新中
- 🔍 **搜索功能**: 全文搜索支持
- 📱 **设备支持**: 桌面端 + 移动端
- 🌍 **浏览器兼容**: 现代浏览器全支持

## 📄 许可证

本项目基于 [MIT 许可证](LICENSE) 开源。

## 🙏 致谢

感谢所有为中华优秀传统文化传承做出贡献的开发者和文学爱好者！

## 📞 联系我们

- 📧 邮箱: [项目邮箱]
- 🐛 问题反馈: [GitHub Issues](https://github.com/orangelorna911/lorna01/issues)
- 💬 讨论交流: [GitHub Discussions](https://github.com/orangelorna911/lorna01/discussions)

---

<div align="center">
  <p>⭐ 如果这个项目对你有帮助，请给我们一个星标！</p>
  <p>📚 让我们一起传承和弘扬中华优秀传统文化！</p>
</div>