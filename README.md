# 功能胶 + 胶水｜产品宣讲决策看板

这是一个纯静态 HTML 看板，可直接上传到 GitHub，再在 Vercel 中导入仓库部署。

## 目录结构

```text
功能胶+胶水项目-vercel/
├─ index.html      # 网站入口
├─ vercel.json     # Vercel 静态站点配置
└─ README.md       # 项目说明
```

## Vercel 部署

1. 将此文件夹内的文件上传到 GitHub 仓库根目录。
2. 在 Vercel 选择 **Add New Project**，导入该 GitHub 仓库。
3. Framework Preset 选择 **Other**。
4. Build Command 留空，Output Directory 留空（根目录静态部署）。
5. 点击 Deploy。

网页无需数据库、环境变量或额外依赖，直接访问域名即可使用。
