# Zhiwei Zhang · 个人学术主页

这是为 Zhiwei Zhang 编写的英文个人学术主页，采用纯 HTML 和 CSS，无需安装 Node、Jekyll、Python 或其他开发工具。中文说明见本文件。

**当前状态：网站文件已准备好，尚未上传至你的 GitHub，也未上线。你的 GitHub 用户名尚未确认。**

## 1. 文件与内容

| 文件 | 用途 |
|---|---|
| `index.html` | 个人介绍、研究方向、新闻、论文和教育经历 |
| `styles.css` | 字体、颜色、间距和手机适配 |
| `assets/profile.jpg` | 个人照片 |
| `assets/daterra.png`、`assets/gtpbd.png`、`assets/gtpbd-mm.png` | 论文配图 |
| `publications.bib` | 论文 BibTeX 条目 |
| `SOURCES.md` | 个人资料、论文及图片的来源说明 |
| `.nojekyll` | 告诉 GitHub Pages 直接发布静态文件 |

页面栏目为 About、Research、News、Selected publications、Other publications、Preprints、Education。精选论文为 DATerra、GTPBD；其他论文包括 TORA、UniFLoW、APBD review、AgroMind；GTPBD-MM 单列为预印本。

教育信息依据现有 CV：2024–2027 年中山大学人工智能学院硕士阶段，2027 年为预计毕业年份，导师为 Juepeng Zheng；2020–2024 年本科就读于福建师范大学软件工程专业。页面使用硕士在读身份。公开邮箱为 `zhangzhw65@mail2.sysu.edu.cn`，照片来自公开实验室页面。发表状态、身份或日期变化后，请及时更新。

## 2. 先在电脑上查看

1. 下载网站 ZIP 文件并**解压**。
2. 打开解压后的文件夹，双击 `index.html`，用浏览器查看。
3. 保持 `index.html`、`styles.css` 和 `assets` 文件夹的位置关系，图片和样式才会正常显示。

## 3. 在 GitHub 免费上线

### 第一步：确认账号与仓库名

登录 [GitHub](https://github.com/)，确认自己的用户名。个人主页仓库名必须是 **`小写用户名.github.io`**，不是随意填写的论文名或英文姓名。[官方命名说明](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)

公开论文代码出现在 `Z-ZW-WXQ` 账号下。**如果这是你本人希望用于主页的账号**，则可采用：

| 项目 | 条件示例 |
|---|---|
| GitHub 用户名 | `Z-ZW-WXQ` |
| 主页仓库名 | `z-zw-wxq.github.io` |
| 未来主页地址 | `https://z-zw-wxq.github.io/` |

这里只说明命名方式，未确认账号归属、仓库是否存在或网站是否已发布。若使用其他账号，请替换为该账号的用户名。

### 第二步：创建公开仓库

1. 点击 GitHub 右上角 **＋ → New repository**。
2. 填写上一步确定的仓库名，选择 **Public**。
3. 可开启 **Add README** 来初始化默认分支，然后点击 **Create repository**。

GitHub Free 可以为公开仓库免费提供 Pages 服务。[官方说明](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages)

### 第三步：上传解压后的内容

在仓库首页点击 **Add file → Upload files**，将网站文件夹**里面的文件和 `assets` 文件夹**拖入上传区域，保持目录结构，然后提交到 `main` 分支。[官方上传说明](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)

**仓库首页必须直接出现 `index.html`。不要只上传 ZIP，也不要多套一层 `zhiwei-zhang-homepage` 文件夹。**

确认 `.nojekyll` 也已上传。若电脑隐藏此文件，可在仓库通过 **Add file → Create new file** 创建名为 `.nojekyll` 的空文件；它用于跳过默认 Jekyll 构建。

### 第四步：开启 Pages

进入仓库 **Settings → Pages**，在 Build and deployment 区域设置：

| 设置项 | 选择 |
|---|---|
| Source | `Deploy from a branch` |
| Branch | `main` |
| Folder | `/(root)` |

点击 **Save**。此后，发布分支的内容更新会自动触发网站发布。[官方设置说明](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

### 第五步：打开网站

等待发布完成，在 **Settings → Pages** 点击 **Visit site**，以 GitHub 实际显示的地址为准。官方说明提交后发布可能需要最多约 10 分钟；发布记录和失败原因可以在仓库的 **Actions** 中查看。[官方发布说明](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)

## 4. 以后怎样更新

| 需要修改 | 操作 |
|---|---|
| 简介、研究方向、邮箱、教育经历 | 在 GitHub 打开 `index.html`，点击铅笔，修改文字，保留 HTML 标签，点击 **Commit changes**。 |
| 照片或论文图 | 替换 `assets` 中的同名文件；更改文件名时，同步修改 `index.html` 中的图片路径。 |
| 新增论文 | 在 `index.html` 找到相应论文栏目，复制一个完整的 `<article>…</article>` 论文块，修改标题、作者、年份、链接和配图。 |
| 更新论文状态 | 已正式发表、已录用和预印本应准确区分；确认录用后再更新栏目和会议/期刊信息。 |
| 作者标注 | 本人姓名、共同第一作者、通讯作者标记以论文原文为准，不根据作者顺序自行推断。 |
| 更新论文引用 | 同步修改 `publications.bib`，并在 `SOURCES.md` 保留可核查出处。 |
| 颜色与排版 | 编辑 `styles.css`；修改后同时检查电脑和手机宽度下的显示。 |

保存后等待自动发布即可。[GitHub 网页编辑说明](https://docs.github.com/en/repositories/working-with-files/managing-files/editing-files)

## 5. 常见问题

| 问题 | 检查方法 |
|---|---|
| 首页 404 | 确认 Pages 已开启、发布任务成功，来源为 `main` 和 `/(root)`。 |
| 只看到 README | 检查仓库根目录是否有 `index.html`，是否误放进额外子文件夹。 |
| 有 HTML 文件仍打不开 | 文件名须为小写 `index.html`，不要使用 `Index.html` 或 `index.HTML`。 |
| 图片或样式缺失 | 检查文件是否上传完整，路径、扩展名及大小写是否一致。 |
| 修改后还是旧内容 | 先检查 Actions 是否发布成功，再等待并刷新浏览器。 |

[GitHub Pages 官方 404 排查指南](https://docs.github.com/en/pages/getting-started-with-github-pages/troubleshooting-404-errors-for-github-pages-sites)
