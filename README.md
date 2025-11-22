# 精品出版 - 高密方言测试网站

## 项目简介
这是一个基于Apple设计风格的高密方言文化测试网站，具有现代化的界面设计和完整的测试功能。

## 功能特色
- 🎨 Apple风格极简设计
- 📱 完全响应式布局
- 🌸 20道精选高密方言测试题
- 📊 实时评分系统
- ✨ 流畅的动画效果

## 技术栈
- HTML5
- CSS3 (现代CSS特性)
- Vanilla JavaScript
- Google Fonts (Inter字体)

## GitHub Pages 部署指南

### 📁 需要上传的文件
```
你的项目根目录/
├── index.html          # 主页面文件 ✅ 必需
├── README.md           # 项目说明文档 ✅ 可选
└── (无其他文件)        # 所有样式和脚本都内嵌在HTML中
```

### 🚀 部署步骤

#### 第一步：创建GitHub仓库
1. 登录 [GitHub](https://github.com)
2. 点击右上角的 "+" → "New repository"
3. 填写仓库名称（建议：`dialect-test-website`）
4. 选择 **Public**（公开仓库）
5. **不要**勾选 "Add a README file"
6. 点击 "Create repository"

#### 第二步：上传文件
**方法A：通过GitHub网页界面（推荐）**
1. 在新创建的仓库页面，点击 "Add file" → "Upload files"
2. 拖拽或选择 `index.html` 文件上传
3. 在 "Commit changes" 部分：
   - 填写提交信息：`Add initial website files`
   - 选择 "Create a new branch" 并命名为 `gh-pages`
   - 勾选 "Start a pull request"
4. 点击 "Commit new file"

**方法B：使用GitHub Desktop（适合新手）**
1. 下载安装 [GitHub Desktop](https://desktop.github.com/)
2. Clone 你刚创建的仓库
3. 将 `index.html` 文件复制到本地仓库文件夹
4. 在GitHub Desktop中：
   - 填写提交信息：`Add website files`
   - 点击 "Commit to main"
   - 点击 "Publish repository"
5. 在GitHub上创建 `gh-pages` 分支

#### 第三步：启用GitHub Pages
1. 在你的GitHub仓库页面，点击 "Settings"
2. 在左侧菜单中找到 "Pages"
3. 在 "Source" 部分：
   - 选择 "Deploy from a branch"
   - Branch 选择：`gh-pages`
   - Folder 选择：`/(root)`
4. 点击 "Save"

#### 第四步：获取网站地址
1. 等待1-2分钟部署完成
2. 在Pages设置页面会显示你的网站地址
3. 格式通常是：`https://[你的用户名].github.io/[仓库名]/`

### 🎉 验证部署
- 访问你的GitHub Pages地址
- 应该能看到"精品出版"的首页
- 测试所有功能是否正常工作

### 🔧 故障排除

#### 问题1：页面显示404
- **解决方案**：确保分支名称是 `gh-pages`，并且在Pages设置中选择了正确的分支

#### 问题2：样式不显示
- **解决方案**：检查HTML文件是否完整上传，确保没有遗漏

#### 问题3：功能无法使用
- **解决方案**：检查浏览器控制台是否有错误信息，确保JavaScript代码完整

### 📝 维护更新
如需更新网站内容：
1. 修改本地的 `index.html` 文件
2. 重新上传到GitHub
3. 等待GitHub Pages自动重新部署（通常1-2分钟）

### 💡 技术说明
- **单文件架构**：所有CSS和JavaScript都内嵌在HTML中，便于部署
- **无依赖**：不需要构建工具或外部依赖
- **跨平台**：支持所有现代浏览器
- **SEO友好**：包含语义化HTML标签和meta信息

### 📞 支持
如果遇到部署问题，请检查：
1. 文件是否正确上传
2. GitHub Pages设置是否正确
3. 浏览器控制台是否有错误信息

---

**享受你的高密方言测试网站！** 🌾