# 🚀 快速部署到 GitHub Pages

## 📋 你的仓库信息
- **GitHub 用户**: liankong31
- **仓库地址**: https://github.com/liankong31/liqi.github.io
- **网站地址**: https://liankong31.github.io/liqi.github.io/

---

## 🎯 部署步骤（最简单方法）

### 步骤 1: 下载文件

我已经为你准备好了所有文件，包括：
- ✅ 完整的网站文件（HTML, CSS, JS）
- ✅ Git 仓库已初始化（包含初始提交）
- ✅ 只需推送到 GitHub 即可

### 步骤 2: 推送到 GitHub

在你的本地机器上执行以下命令：

```bash
# 1. 解压文件
unzip liqi-github-page-files.zip

# 2. 进入目录
cd liqi-github-page

# 3. 推送到 GitHub（需要输入凭据）
git push -u origin main
```

**推送时需要输入**：
- **Username**: `liankong31`
- **Password**: 你的 GitHub Personal Access Token (PAT)

### 步骤 3: 创建 Personal Access Token (如果还没有)

1. 访问: `https://github.com/settings/tokens/new`
2. 填写:
   - Note: `GitHub Pages Deployment`
   - Expiration: `90 days` 或更长
   - 勾选: `repo` (Full control of private repositories)
3. 点击 "Generate token"
4. **立即复制 Token**（只显示一次！）

### 步骤 4: 启用 GitHub Pages

1. 访问你的仓库: `https://github.com/liankong31/liqi.github.io`
2. 点击 "Settings" → 左侧 "Pages"
3. 配置:
   - Source: `main` 分支
   - Folder: `/ (root)`
4. 点击 "Save"
5. 等待 1-2 分钟

### 步骤 5: 访问网站

访问: `https://liankong31.github.io/liqi.github.io/`

---

## 📁 文件说明

压缩包包含：
- `index.html` - 主页（35.9 KB）
- `styles.css` - 样式（15.7 KB）
- `script.js` - 脚本（4.7 KB）
- `404.html` - 错误页
- `README.md` - 说明
- `.git/` - Git 仓库（已初始化）

---

## ✅ 部署检查清单

- [ ] 文件已解压
- [ ] 已进入 `liqi-github-page` 目录
- [ ] 已执行 `git push -u origin main`
- [ ] 已输入正确的用户名和 Token
- [ ] GitHub Pages 已启用
- [ ] 已等待 1-2 分钟
- [ ] 网站可以正常访问

---

## 🔧 故障排除

### 问题: 推送失败，提示认证错误

**解决**: 
1. 确认用户名是 `liankong31`
2. 确认使用的是 Personal Access Token，不是密码
3. 确认 Token 有 `repo` 权限

### 问题: 网站显示 404

**解决**:
1. 等待 2-3 分钟（GitHub Pages 需要时间部署）
2. 确认 GitHub Pages 已启用
3. 确认分支选择正确（main）

### 问题: 页面样式不正常

**解决**:
1. 清除浏览器缓存
2. 检查 `styles.css` 是否存在
3. 检查浏览器控制台是否有错误

---

## 🎨 自定义修改

### 修改个人信息

编辑 `index.html` 第 14-35 行：

```html
<h1>Li Qi <span class="title-badge">Ph.D.</span></h1>
<p class="subtitle">Postdoctoral Research Fellow @ Queen's University</p>
<a href="mailto:qi.li@queensu.ca">qi.li@queensu.ca</a>
```

### 修改社交媒体

编辑 `index.html` 第 37-42 行，添加你的社交链接。

### 修改主题颜色

编辑 `styles.css` 第 6-19 行，修改颜色变量。

---

## 📞 需要帮助？

如果遇到问题，随时告诉我！

---

**祝你部署成功！** 🎉
