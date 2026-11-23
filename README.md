# Seedance 深度案例集

此仓库存放已构建的公开网站。当前展示的案例、中英文内容、图片与影片均在 public/，不依赖公司登录。飞书原文档链接仍遵循原文档自己的权限。

## 更新

修改网站后，把完整构建结果同步到 public/，提交到 main；GitHub Actions 会自动发布 GitHub Pages。不要单独上传 index.html 而遗漏媒体文件。

可编辑源项目保存在本机 output/seedance-gpt-site/.sites-checkout；运行 node build.mjs 后，把 dist/ 同步至本仓库 public/。

## 恢复旧版

在 GitHub 恢复上一版提交并提交至 main，即会重新发布旧版。

## 首次启用

仓库 Settings → Pages → Source 选择 GitHub Actions。免费账号使用公开仓库。
