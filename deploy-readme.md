# PK挑战赛 - GitHub Pages 部署指南

## 部署步骤

### 1. 创建 GitHub 仓库
1. 访问 https://github.com
2. 登录账号（没有就注册）
3. 点击右上角 "+" → "New repository"
4. 填写：
   - Repository name: `pk-challenge-web`
   - Public (公开)
   - 不要勾选"Initialize this repository with a README"
5. 点击 "Create repository"

### 2. 上传文件到 GitHub
方法一（推荐）：使用 GitHub Desktop
1. 下载 GitHub Desktop: https://desktop.github.com
2. 克隆你刚创建的仓库到本地
3. 将本文件夹所有文件复制到仓库文件夹
4. 提交并推送

方法二：使用网页上传
1. 在仓库页面，点击 "Add file" → "Upload files"
2. 将本文件夹的 3 个文件拖拽进去：
   - `index.html`
   - `challenge.html`
   - `SPEC.md`
3. 填写提交信息，点击 "Commit changes"

### 3. 开启 GitHub Pages
1. 在仓库页面，点击 "Settings"
2. 左侧菜单找到 "Pages"
3. 在 "Source" 部分，选择：
   - Branch: `main`
   - Folder: `/ (root)`
   - 点击 "Save"

### 4. 等待部署
1. 稍等 1-2 分钟
2. 刷新 GitHub Pages 设置页面
3. 你会看到一个绿色的提示，显示你的网站地址：
   - `https://[你的用户名].github.io/pk-challenge-web/`

### 5. 测试网站
1. 打开上面生成的链接
2. 如果显示 "PK挑战赛" 主页，说明部署成功！

## 文件说明
- `index.html` - 主页面，选择科目和挑战类型
- `challenge.html` - 挑战答题页面
- `SPEC.md` - 项目说明文档

## GitHub Pages 链接格式
你的公开链接会是：
```
https://[你的GitHub用户名].github.io/pk-challenge-web/
```

例如：
```
https://zhangsan.github.io/pk-challenge-web/
```

## 注意事项
- GitHub Pages 完全免费
- 网站自动更新（每次推送代码后约 1-2 分钟生效）
- 支持 HTTPS
- 没有流量限制
- 可以绑定自定义域名（可选）

## 测试完成
部署完成后，把这个链接发给任何人，他们都能访问你的 PK挑战赛 网站！