# 🔋 电池行业周报

每周自动生成电池行业周报，通过 GitHub Pages 自动部署。

## 📱 在线访问

**最新周报：** https://ughszstu-cmd.github.io/battery-weekly-report/

## 📂 历史周报

| 日期 | 链接 |
|------|------|
| 2026-07-07 | [查看](reports/20260707.html) |
| 2026-07-02 | [查看](reports/20260702.html) |
| 2026-06-29 | [查看](reports/20260629.html) |

## 🚀 更新周报

将新生成的 HTML 文件放到仓库根目录，命名为 `index.html`，同时复制一份到 `reports/` 目录下（以日期命名，如 `20260706.html`），然后提交推送即可自动部署。

```bash
# 示例：更新周报
cp 新周报.html index.html
cp 新周报.html reports/20260706.html
git add .
git commit -m "更新周报 2026-07-06"
git push
```

## ⚙️ 自动部署

使用 GitHub Actions 自动部署到 GitHub Pages，每次 push 到 main 分支后自动更新。
