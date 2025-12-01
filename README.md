# 星际粒子系统 - 部署指南

这是一个基于 Three.js 的 3D 粒子系统网站，支持多种粒子模式和交互功能。

## 功能特性

- 🌌 **星云模式** - 螺旋星系粒子效果
- 🔷 **四维投影** - 超立方体投影效果
- 🔄 **莫比乌斯** - 莫比乌斯带粒子效果
- 🌊 **上岸模式** - 波浪上升粒子效果（新增）
- 🖌️ **手绘模式** - 自定义绘制粒子形状
- 📷 **手势控制** - 通过摄像头手势交互
- 🎨 **颜色自定义** - 可调整核心和边缘颜色
- 📱 **响应式设计** - 支持桌面和移动设备

## 快速部署

### 方法一：GitHub Pages（推荐）

1. 将项目上传到 GitHub 仓库
2. 在仓库设置中启用 GitHub Pages
3. 选择 `main` 分支和 `/ (root)` 目录
4. 访问 `https://你的用户名.github.io/仓库名/`

### 方法二：Netlify

1. 访问 [Netlify](https://www.netlify.com/)
2. 拖拽包含 `index.html` 的文件夹到部署区域
3. 网站会自动部署并获得一个免费域名

### 方法三：Vercel

1. 访问 [Vercel](https://vercel.com/)
2. 导入项目并选择包含 `index.html` 的目录
3. 点击部署即可

### 方法四：本地服务器

使用 Python 3：
```bash
python -m http.server 8000
```

使用 Node.js：
```bash
npx http-server -p 8000
```

然后访问 `http://localhost:8000`

## 文件结构

```
.
├── index.html          # 主文件（包含所有代码）
└── README.md          # 本说明文件
```

## 技术栈

- **Three.js** - 3D 图形库
- **MediaPipe Hands** - 手势识别
- **WebGL Shaders** - GPU 加速渲染
- **原生 JavaScript** - 无需构建工具

## 浏览器要求

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- 支持 WebGL 的现代浏览器

## 注意事项

1. 手势控制功能需要摄像头权限
2. 建议使用 HTTPS 部署以支持摄像头功能
3. 移动设备上性能可能有所降低

## 许可证

本项目可自由使用和修改。

