# lmyx

这是一个纯静态个人主页项目，可直接部署到 GitHub Pages。

## GitHub Pages 部署

1. 将本仓库推送到 GitHub（默认分支为 `work`）。
2. 在仓库的 **Settings → Pages** 中：
   - **Source** 选择 `Deploy from a branch`。
   - **Branch** 选择 `work`，并将目录设为 `/ (root)`。
   - 点击 **Save**。
3. 等待 Pages 构建完成后，访问页面提示的公网地址。

> 如需使用自定义域名，可在 Pages 设置中填写 `Custom domain` 并按提示配置 DNS。

## 本地预览

```bash
python -m http.server 8000
```

浏览器打开 `http://127.0.0.1:8000`。
