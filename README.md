# Yucong XU - Personal Academic Website

一个专业的个人学术网站，展示教育背景、研究成果、项目经历等信息。

## 🌐 网站结构

```
personal-website/
├── index.html          # 首页/关于我
├── education.html      # 教育背景
├── publications.html   # 发表论文
├── projects.html       # 科研项目
├── honors.html         # 荣誉奖项
├── css/
│   └── style.css       # 统一样式文件
├── js/
│   └── nav.js          # 导航脚本
└── README.md           # 本说明文件
```

## 🚀 如何使用

### 本地预览
1. 直接用浏览器打开 `index.html` 文件
2. 点击导航菜单切换不同页面

### 在线部署
可将整个文件夹上传到以下平台：
- **GitHub Pages**（推荐）
- Netlify
- Vercel
- 任何静态网站托管服务

## ✏️ 如何编辑内容

### 1. 修改个人信息（首页）
编辑 `index.html` 文件：

```html
<!-- 修改姓名 -->
<h1 class="header-name">Yucong XU</h1>
<p class="header-chinese">徐宇聪</p>

<!-- 修改联系方式 -->
<span><i class="fas fa-phone"></i> +86 15367487397</span>
<span><i class="fas fa-envelope"></i> yucong-xu@hku.hk</span>

<!-- 修改个人简介 -->
<p class="intro-text">你的个人简介内容...</p>
```

### 2. 修改教育背景
编辑 `education.html` 文件，复制 `.edu-card` 模块添加新的教育经历。

### 3. 添加论文
编辑 `publications.html` 文件，复制 `.pub-card` 模块添加新论文：

```html
<div class="pub-card">
    <span class="pub-type journal">Journal Article</span>
    <h4 class="pub-title">论文标题</h4>
    <p class="pub-authors">作者列表（你的名字加高亮）</p>
    <p class="pub-journal">
        <strong>期刊名</strong>, 年份, 卷: 页码
        <span class="pub-if">IF = 影响因子</span>
    </p>
</div>
```

### 4. 添加项目经历
编辑 `projects.html` 文件，复制 `.section` 模块添加新项目。

### 5. 添加荣誉奖项
编辑 `honors.html` 文件，复制 `.honor-item` 模块添加新奖项：

```html
<div class="honor-item">
    <div class="honor-icon"><i class="fas fa-trophy"></i></div>
    <div class="honor-text">
        <strong>奖项名称</strong>
        <br><span style="color: #888; font-size: 0.85rem;">奖项说明</span>
    </div>
</div>
```

## 🎨 自定义样式

### 修改配色方案
编辑 `css/style.css` 文件，修改以下颜色变量：

```css
/* 深蓝学术风配色 */
- Primary: #1e3a5f (深蓝) - 主导航、标题
- Accent: #c9a227 (金色) - 强调色、徽章
- Text: #333333 (深灰) - 正文
- Background: #fafafa (浅灰) - 背景
```

### 修改字体大小
在 `css/style.css` 中搜索对应的选择器修改：

```css
.header-name { font-size: 2.8rem; }    /* 姓名大小 */
.edu-degree { font-size: 1.2rem; }     /* 学位大小 */
.pub-title { font-size: 1.1rem; }      /* 论文标题大小 */
```

## 📱 响应式设计

网站已适配：
- 💻 桌面电脑（> 768px）
- 📱 手机（< 768px）

在手机端，导航栏会自动折叠为汉堡菜单。

## 🖨️ 打印样式

网站已添加打印样式优化，可以直接打印或保存为 PDF：
- 隐藏导航栏和页脚
- 移除阴影效果
- 确保背景色打印

## 🔗 Google Scholar 链接

在以下位置修改你的 Google Scholar 链接：
1. `index.html` - 头部区域
2. `publications.html` - 页面底部引用区域

将 `href="https://scholar.google.com"` 替换为你的实际 Scholar 主页链接。

## 🆘 常见问题

### 图标不显示？
确保网络连接正常，图标使用 Font Awesome CDN 加载。

### 如何添加新页面？
1. 复制现有 HTML 文件（如 `education.html`）
2. 重命名为新页面（如 `teaching.html`）
3. 修改导航栏中的链接
4. 在每个页面的导航栏中添加新链接

### 如何修改导航栏顺序？
编辑所有 HTML 文件中的导航部分：

```html
<ul class="nav-menu" id="navMenu">
    <li><a href="index.html">Home</a></li>
    <!-- 调整这里的顺序 -->
</ul>
```

## 📧 联系方式

如有问题，请联系：yucong-xu@hku.hk

---

**最后更新：** 2025年3月
