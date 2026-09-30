# J Shell 隐私政策 / Privacy Policy

J Shell（Android SSH 客户端，`com.jay.harborshell`）的隐私政策，公开发布用。这个仓库只放这一份静态页面，**不包含任何应用源码、密钥或配置**。

Public privacy policy for the J Shell Android SSH client. This repository contains nothing but that one static page — no app source, no keys, no configuration.

- 线上地址 / Published at: `https://<你的GitHub用户名>.github.io/jshell-privacy/`（以实际部署为准）
- 页面文件 / Page: [`index.html`](index.html)（自包含，无外部依赖，中英双语）
- 联系邮箱 / Contact: mayuluck021@gmail.com

## 怎么更新 / How to update

政策正文的源文件在应用仓库的 `docs/privacy-policy.md`（改内容先改它），导出的页面是 `docs/privacy-policy.html`。更新线上的步骤：

```sh
# 1) 在应用仓库里改 docs/privacy-policy.md（含顶部“最近更新”日期）
# 2) 重新导出页面（或直接编辑 docs/privacy-policy.html）
# 3) 同步到这个仓库并推送
cp docs/privacy-policy.html index.html
git add index.html
git commit -m "Update privacy policy (YYYY-MM-DD)"
git push
```

推送后 GitHub Pages 会在 1 分钟内自动重建；打开线上地址强制刷新（或用无痕窗口）确认已生效。

After each update, refresh the live URL in a private window to confirm the new “Last updated” date is visible.

## 部署 / Deployment

GitHub Pages，`Deploy from a branch` → `main` → `/ (root)`。

**不要改仓库名、也不要改这个地址**：Google Play 后台填写的隐私政策 URL 必须长期有效，改名会导致审核与用户投诉时链接 404。若必须迁移，先在新地址上线，再更新 Play Console，最后才下线旧地址。

**Do not rename this repository**: the URL is referenced from the Google Play listing and must stay reachable.
