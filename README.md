# 大学城美食地图 - GitHub Pages 部署指南

## 项目简介
这是一个功能完整的大学城美食地图应用，包含地图展示、餐厅筛选、菜单日历、个人资料等功能。

## 部署步骤

### 1. 在 GitHub 上创建仓库

1. 访问 https://github.com/new
2. 创建一个新的公开仓库（例如：`food-map` 或其他你喜欢的名字）
3. 不要初始化 README、.gitignore 或 LICENSE
4. 点击 "Create repository"

### 2. 推送代码到 GitHub

在终端中执行以下命令（替换 `your-username` 和 `your-repo-name`）：

```bash
cd /Users/bytedance/Documents/studentfood/deploy-html
git remote add origin https://github.com/your-username/your-repo-name.git
git branch -M main
git push -u origin main
```

### 3. 启用 GitHub Pages

1. 进入你的 GitHub 仓库页面
2. 点击 "Settings"（设置）
3. 在左侧菜单中找到 "Pages"
4. 在 "Build and deployment" 部分：
   - Source 选择 "Deploy from a branch"
   - Branch 选择 "main" 分支
   - Folder 选择 "/ (root)"
5. 点击 "Save"

### 4. 访问你的网站

等待几分钟后，你的网站将可以通过以下地址访问：
```
https://your-username.github.io/your-repo-name/
```

## 本地预览

在浏览器中直接打开 `index.html` 文件即可预览：
```bash
open index.html
```

## 功能特性

- 🗺️ 交互式地图展示
- 🍽️ 餐厅筛选（菜系、价格、评分）
- 📋 菜单日历规划
- 🧑‍🎓 个人资料管理
- 🌙 亮色/暗色主题切换
- 💾 本地数据存储
- 📱 响应式设计

## 技术栈

- HTML5 + CSS3 + JavaScript
- Leaflet 地图库
- 纯前端应用，无需后端服务器
