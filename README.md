# 番剧删减记录表

一个可直接部署到 GitHub Pages 的静态网站。

## 功能
- 搜索番剧、季度和备注
- 按季度筛选
- 封面 URL 展示
- 添加、编辑、删除番剧
- 每部番剧添加分集记录，每集可添加多个时间点、删减时长和备注
- JSON 导出备份、JSON 导入恢复
- 手机与桌面端自适应布局
- 数据保存在当前浏览器的 localStorage

## 部署到 GitHub Pages
1. 在 GitHub 新建一个仓库，例如 `anime-cut-notes`。
2. 将 `index.html` 上传到仓库根目录（和 README.md 同级）。
3. 打开仓库的 **Settings → Pages**。
4. 在 **Build and deployment** 中选择 **Deploy from a branch**。
5. Branch 选择 `main`，目录选择 `/(root)`，点击 **Save**。
6. 等待部署完成后，在 Pages 页面点击 **Visit site**。网址通常类似 `https://你的用户名.github.io/anime-cut-notes/`。

官方说明：
- https://docs.github.com/en/pages/quickstart
- https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## 数据与隐私说明
- GitHub Pages 只托管网页文件；它不提供数据库。
- 添加、编辑、删除的记录只保存在正在使用的浏览器中，不会自动同步给其他访客或设备。
- 清理浏览器数据前请使用“导出 JSON”备份。
- “导入备份”会替换当前浏览器中的所有记录，导入前请确认已有数据已备份。
- 网站公开发布后，仓库中的网页文件是公开可访问的；不要将私人信息写入公开文件。
- 封面图片使用你填写的 HTTP(S) 图片链接，图片是否能显示取决于原图片站点。
