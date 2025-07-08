# 🚀 部署指南

本指南将帮助您将简约卡片生成器部署到GitHub Pages，让全世界的用户都能访问您的工具。

## 📋 部署步骤

### 1. 创建GitHub仓库

1. 登录 [GitHub](https://github.com)
2. 点击右上角的 "+" 按钮，选择 "New repository"
3. 仓库名称建议使用：`card-generator` 或 `simple-card-generator`
4. 设置为 **Public** （公开仓库才能使用免费的GitHub Pages）
5. 勾选 "Add a README file"
6. 点击 "Create repository"

### 2. 上传文件

#### 方法一：通过GitHub网页界面
1. 在新创建的仓库页面，点击 "uploading an existing file"
2. 将以下文件拖拽到上传区域：
   - `index.html` （主页面文件）
   - `README.md` （项目说明）
3. 在页面底部填写提交信息：
   - Commit title: `Add card generator files`
   - Description: `Initial upload of the card generator application`
4. 点击 "Commit changes"

#### 方法二：通过Git命令行
```bash
# 克隆仓库到本地
git clone https://github.com/your-username/card-generator.git
cd card-generator

# 复制文件到仓库目录
# 将 index.html 和 README.md 复制到这个目录

# 添加文件到Git
git add .
git commit -m "Add card generator files"
git push origin main
```

### 3. 启用GitHub Pages

1. 在仓库页面，点击 "Settings" 选项卡
2. 在左侧菜单中找到 "Pages"
3. 在 "Source" 部分：
   - 选择 "Deploy from a branch"
   - Branch 选择 "main"
   - Folder 选择 "/ (root)"
4. 点击 "Save"

### 4. 访问您的网站

- GitHub会自动构建您的网站
- 几分钟后，您可以通过以下地址访问：
  ```
  https://your-username.github.io/card-generator/
  ```
- 将 `your-username` 替换为您的GitHub用户名

## 🔧 自定义域名（可选）

如果您有自己的域名，可以设置自定义域名：

1. 在仓库根目录创建 `CNAME` 文件
2. 文件内容为您的域名，例如：`cards.yourdomain.com`
3. 在您的域名DNS设置中添加CNAME记录，指向 `your-username.github.io`

## 📱 分享您的工具

部署完成后，您可以：

1. **社交媒体分享**：在微博、朋友圈等平台分享链接
2. **技术社区**：在掘金、CSDN、知乎等平台发布介绍文章
3. **GitHub推广**：为仓库添加详细的README和标签
4. **SEO优化**：在index.html中添加更多meta标签

## 🛠️ 维护和更新

### 更新内容
1. 修改本地文件
2. 提交到GitHub仓库
3. GitHub Pages会自动更新网站

### 监控访问
- 可以集成Google Analytics追踪访问数据
- GitHub仓库的Insights可以查看流量统计

## 🎯 推广建议

1. **优化SEO**：
   - 添加更多关键词到meta标签
   - 创建sitemap.xml
   - 提交到Google Search Console

2. **社区推广**：
   - 在相关技术论坛分享
   - 参与开源项目展示
   - 制作使用教程视频

3. **功能增强**：
   - 添加更多设计模板
   - 支持图片导出功能
   - 增加用户反馈机制

## 🔍 故障排除

### 常见问题

**Q: 网站无法访问**
A: 检查GitHub Pages设置，确保选择了正确的分支和目录

**Q: 样式显示异常**
A: 检查CSS文件路径，确保所有资源都在仓库中

**Q: 字体无法加载**
A: Google Fonts可能在某些地区访问受限，可以考虑使用本地字体

**Q: 移动端显示问题**
A: 检查viewport meta标签和响应式CSS

## 📞 技术支持

如果遇到部署问题，可以：
1. 查看GitHub Pages官方文档
2. 在GitHub仓库中提交Issue
3. 联系项目作者：硅基鸟人（公众号同名）

---

祝您部署顺利！🎉
