# 我的个人网站

基于 [vCard - Personal Portfolio](https://github.com/codewithsadee/vcard-personal-portfolio)（⭐ 8k+）定制的中文个人网站。

纯 HTML / CSS / JavaScript 实现，零构建依赖，克隆即可运行。

## 快速开始

### 方式一：直接打开（最简单）

双击 index.html 即可在浏览器中查看。

### 方式二：本地开发服务器（推荐）

```bash
# 任选其一
npx serve .
python -m http.server 8080
# 然后访问 http://localhost:8080
```

## 定制指南

所有内容都在 index.html 中，直接搜索以下关键词修改：

| 内容 | 搜索关键词 |
|------|-----------|
| 姓名 / 职位 | 刘春庆、大数据开发工程师 |
| 邮箱 / 电话 | PetterQing@163.com、+86 138-0000-0000 |
| 头像 | assets/images/my-avatar.svg（可替换为自己的照片） |
| 社交链接 | logo-github、mail-outline、logo-youtube 对应区块的 href |
| 关于我 | 关于我板块的简介段落 |
| 服务 | 我正在做什么板块 |
| 好友评价 | 好友评价板块 |
| 教育 / 经历 | 教育背景、工作经历板块 |
| 技能 | 我的技能板块 |
| 作品集 | 作品集板块（分类：全部 / 网页设计 / 应用程序 / Web 开发） |
| 博客 | 博客板块 |
| 联系表单 | 留言表单板块（提交需接入后端或第三方表单服务，如 Formspree） |
| 地图 | 联系页的 Google Maps iframe（可替换为高德/百度地图） |

## 技术栈

- HTML5 / CSS3 / JavaScript（原生）
- Ionicons 图标
- Google Fonts（Poppins 字体）

## 部署

- **GitHub Pages**：推送到仓库后开启 Pages 即可
- **Vercel / Netlify**：导入仓库直接部署，零配置
