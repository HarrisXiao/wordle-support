# Wordle 中文版 技术支持网站

## 📖 简介

这是一个为 Wordle 中文版 iOS 应用创建的技术支持网站。该网站可以作为 App Store 上架时的技术支持 URL 使用。

## 🌟 功能特性

- ✅ 现代化响应式设计
- ✅ 完整的技术支持信息
- ✅ 用户指南和常见问题
- ✅ 联系方式和反馈渠道
- ✅ 隐私政策页面
- ✅ 移动端友好
- ✅ 快速加载和平滑动画

## 📁 文件结构

```
support-website/
├── index.html          # 主页
├── privacy.html        # 隐私政策页面
├── style.css          # 样式文件
├── script.js          # JavaScript 功能
└── README.md          # 说明文档
```

## 🚀 部署方式

### 方式1：GitHub Pages（推荐）

1. 将 `support-website` 文件夹上传到 GitHub 仓库
2. 在仓库设置中启用 GitHub Pages
3. 选择源分支（通常是 main）
4. 获得类似这样的URL：`https://yourusername.github.io/repository-name/`

### 方式2：Netlify

1. 在 [Netlify](https://netlify.com) 注册账号
2. 将 `support-website` 文件夹拖拽到 Netlify 部署区域
3. 获得免费的 `.netlify.app` 域名

### 方式3：Vercel

1. 在 [Vercel](https://vercel.com) 注册账号
2. 连接 GitHub 仓库或直接上传文件
3. 自动部署并获得域名

### 方式4：自己的服务器

1. 将所有文件上传到你的 Web 服务器
2. 确保服务器支持静态文件托管
3. 通过你的域名访问

## 🔧 自定义修改

### 更换邮箱地址

在以下文件中替换 `support@wordlegame.com`：
- `index.html` (多处)
- `privacy.html`

### 修改应用名称

将 "Wordle 中文版" 替换为你的应用名称：
- `index.html`
- `privacy.html`
- `style.css` (如果有相关样式)

### 更新联系信息

在 `index.html` 的联系部分更新：
- 开发者信息
- 工作时间
- 其他联系方式

### 修改颜色主题

在 `style.css` 的 `:root` 部分调整颜色变量：
```css
:root {
    --primary-color: #6366f1;  /* 主色调 */
    --secondary-color: #8b5cf6; /* 辅助色 */
    /* ... 其他颜色 */
}
```

## 📱 App Store 使用

当你在 App Store Connect 中上架应用时：

1. 在"应用信息"部分找到"技术支持 URL"
2. 填入你部署后的网站URL
3. 例如：`https://yourusername.github.io/wordle-support/`

## ✅ 检查清单

部署前请确认：

- [ ] 邮箱地址已更新为你的真实邮箱
- [ ] 应用名称已正确修改
- [ ] 所有链接都可以正常访问
- [ ] 在不同设备上测试响应式设计
- [ ] 检查拼写和语法错误
- [ ] 隐私政策内容符合你的实际情况

## 🌐 支持的浏览器

- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+
- ✅ iOS Safari 13+
- ✅ Android Chrome 80+

## 📈 SEO 优化

网站已包含基本的 SEO 优化：
- 语义化 HTML 结构
- 合适的标题层级
- Meta 标签设置
- 响应式设计
- 快速加载速度

## 🔒 安全考虑

- 所有外部链接使用 HTTPS
- 没有收集用户敏感信息
- 遵循 Web 安全最佳实践
- 包含完整的隐私政策

## 🆘 技术支持

如果你在部署或使用过程中遇到问题：

1. 检查浏览器控制台是否有错误
2. 确认所有文件路径正确
3. 验证网站在不同设备上的显示效果
4. 检查邮箱链接是否正常工作

## 📜 许可证

此项目基于 MIT 许可证，你可以自由使用、修改和分发。

## 🎯 更新日志

- **v1.0.0** (2024-01): 初始版本发布
  - 完整的技术支持网站
  - 响应式设计
  - 隐私政策页面
  - 交互功能和动画效果

---

**提示**：记得将邮箱地址 `support@wordlegame.com` 替换为你的真实邮箱地址！ 