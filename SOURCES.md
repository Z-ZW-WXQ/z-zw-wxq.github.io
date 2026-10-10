# 个人主页内容与书目信息来源

核对日期：**2026-10-09**。

本记录说明 Zhiwei Zhang 个人学术主页的身份信息、研究介绍和论文条目依据。`publications.bib` 包含 7 项已交叉核对署名的成果，其中 6 项为已发表的期刊或会议论文，1 项为预印本。这是经核实的精选集合，**不是 Google Scholar 全量导出**。

## 1. 身份定位与访问范围

用户指定的 Google Scholar 档案：

- [Google Scholar（用户提供的地址）](https://scholar.google.com.hk/citations?user=0M4TJKYAAAAJ&hl=zh-CN)
- [同一 Scholar ID 的 google.com 地址](https://scholar.google.com/citations?user=0M4TJKYAAAAJ&hl=zh-CN)

检索工具未能直接读取完整 Scholar 页面；搜索索引显示其姓名为 **Zhiwei Zhang**，单位为 **Sun Yat-sen University**，认证邮箱域名为 **mail2.sysu.edu.cn**，研究标签为 **Remote Sensing**。索引中的 GTPBD 和农业地块综述条目，与下列论文及课题组公开资料交叉匹配。

因此，本主页使用的是中山大学遥感方向的 Zhiwei Zhang 的资料，不采用其他机构同名研究者的学历、论文或身份。没有完整核对 Scholar 的所有条目、引用次数、h-index 或 i10-index；主页不填入此类统计。

## 2. 身份与教育经历

| 字段 | 已核实内容 | 来源 |
| --- | --- | --- |
| 英文姓名 | Zhiwei Zhang | 课题组公开 CV、正式论文作者列表 |
| 学校与学院 | School of Artificial Intelligence, Sun Yat-sen University, Zhuhai, China | TORA 正式论文首页；农业地块综述的 Author Information |
| 学生身份 | 人工智能硕士在读；公开 CV 记载 M.E., Artificial Intelligence，2024–2027 (expected) | 课题组公开 CV |
| 硕士导师 | Prof. Juepeng Zheng | 课题组公开 CV |
| 本科 | B.E., Software Engineering, Fujian Normal University，2020–2024 | 课题组公开 CV |
| 科研邮箱 | zhangzhw65@mail2.sysu.edu.cn | 课题组公开 CV、TORA 正式论文、作者发布的数据集页面 |

主要一手链接：

- [课题组公开 CV](https://rssysu.github.io/assets/resume/zzw.html)
- [TORA 正式论文 PDF](https://rssysu.github.io/assets/paper/tora.pdf)
- [农业地块综述正式论文 PDF](https://rssysu.github.io/assets/paper/apbd.pdf)
- [IEEE 作者资料](https://ieeexplore.ieee.org/author/914603048248610)
- [GTPBD-MM 作者发布的数据集页面](https://huggingface.co/datasets/wxqzzw/GTPBD-MM)
- [SYSU IGCS Lab 主页](https://rssysu.github.io/)

“2027”是 CV 中的**预计毕业年份**，不代表已经取得硕士学位。当前证据支持使用 **Master’s student**。中文姓名尚未从唯一匹配的一手来源确认，主页使用用户提供的英文姓名。未自行加入博士生身份、个人奖项、审稿服务或其他未核实经历；公开 CV 中的电话号码不纳入主页或本交付资料。

## 3. 研究方向与简介的写作依据

主页研究介绍是根据下列论文内容重新撰写的概括，**不是将某一个来源中的标签原样作为本人确认的完整研究范围**。

| 主页采用的研究方向 | 对应的公开工作 |
| --- | --- |
| Agricultural Remote Sensing | GTPBD、DATerra、农业地块综述、AgroMind、TORA |
| Parcel and Boundary Delineation | GTPBD、DATerra、农业地块综述、GTPBD-MM |
| Cross-Region Adaptation | DATerra 的跨区域域适应；GTPBD 中的跨区域评测 |
| Multimodal Learning and Foundation Model Adaptation | GTPBD-MM 的影像、文本和 DEM；AgroMind 的多模态评测；TORA 的基础模型适配；UniFLoW 的多模态联邦微调 |

研究愿景和行文表述属于基于这些公开工作的编辑归纳。主页没有将合作论文的全部贡献都表述为 Zhiwei Zhang 个人独立完成。

## 4. 论文逐项核实

### DATerra

- 完整标题：**DATerra: Boundary and structure aware domain adaptation for cross-regional terraced parcel extraction**。
- 期刊：*International Journal of Applied Earth Observation and Geoinformation*，153，105579，2026。
- DOI：[10.1016/j.jag.2026.105579](https://doi.org/10.1016/j.jag.2026.105579)。
- 来源：[出版社页面](https://www.sciencedirect.com/science/article/pii/S1569843226004954)；[课题组论文列表](https://rssysu.github.io/pub.html)；[作者托管 PDF](https://rssysu.github.io/assets/paper/daterra.pdf)。
- 出版社页面直接访问受限，但搜索索引提供了标题、完整作者表、卷号、文章号、DOI 及共同贡献脚注；已与课题组记录交叉核对。
- Zhiwei Zhang 与 Xingyuan Zeng 均带相同的共同贡献脚注，`publications.bib` 的 `note` 据此注明共同第一作者的等贡献关系。
- 出版社原文给出的代码地址：[Z-ZW-WXQ/DATerra](https://github.com/Z-ZW-WXQ/DATerra)。记录此链接不代表已检验仓库代码可运行。

### GTPBD

- 完整标题：**GTPBD: A Fine-Grained Global Terraced Parcel and Boundary Dataset**。
- 会议：NeurIPS 2025，Datasets and Benchmarks Track；*Advances in Neural Information Processing Systems* 38。
- DOI：[10.52202/085713-4963](https://doi.org/10.52202/085713-4963)。
- 来源：[NeurIPS 官方论文页](https://papers.nips.cc/paper_files/paper/2025/hash/da3f5e8ad41aea0980bcf4f55fb099f4-Abstract-Datasets_and_Benchmarks_Track.html)；[arXiv](https://arxiv.org/abs/2507.14697)；[OpenReview](https://openreview.net/forum?id=A3aV30YGqP)。
- [官方关联仓库](https://github.com/Z-ZW-WXQ/GTPBD/)；[作者发布的数据集](https://huggingface.co/datasets/wxqzzw/GTD)。
- NeurIPS 网页元数据把一位作者写为 `Huang Jianxi`；arXiv 和课题组作者列表使用 `Jianxi Huang`。本主页及 BibTeX 采用正常姓名顺序 **Jianxi Huang**，不改变作者次序。
- 若主页展示 47,537 张图像、200,000+ 梯田地块等数字，其依据是官方论文摘要，不是对当前数据下载文件重新统计。

### TORA

- 完整标题：**TORA: Parameter-Efficient Token-Driven Residual Adaptation of Remote Sensing Foundation Models for Multiscale Agricultural Vision**。
- 期刊：*IEEE Transactions on Geoscience and Remote Sensing*，64，文章号 5626216，2026。
- DOI：[10.1109/TGRS.2026.3699401](https://doi.org/10.1109/TGRS.2026.3699401)。
- 来源：[IEEE 页面](https://ieeexplore.ieee.org/document/11547234/)；[作者托管的正式论文 PDF](https://rssysu.github.io/assets/paper/tora.pdf)。
- 正式 PDF 首页核实了完整作者表、卷号、文章号、DOI，以及 Zhiwei Zhang 的学院与邮箱。没有为这篇论文猜测专门的代码地址。

### UniFLoW

- 完整标题：**UniFLoW: Universal Multi-Modal Federated LoRA Fine-Tuning Framework with Analytical Aggregation**。
- 会议：ICML 2026。
- 来源：[OpenReview](https://openreview.net/forum?id=21J9OI6mhc)；[ICML 官方下载目录](https://icml.cc/Downloads/2026)；[作者托管的会议论文 PDF](https://rssysu.github.io/assets/paper/uniflow.pdf)。
- ICML 官方索引和作者论文的会议页脚共同确认会议状态；完整作者列表取自论文首页。没有填入未核实的 DOI、页码或专门的代码地址。

### 农业地块与边界提取综述

- 完整标题：**A Comprehensive Review of Agricultural Parcel and Boundary Delineation From Remote Sensing Images: Recent progress and future perspectives**。
- 期刊：*IEEE Geoscience and Remote Sensing Magazine*，2026。
- DOI：[10.1109/MGRS.2026.3658493](https://doi.org/10.1109/MGRS.2026.3658493)。
- 来源：[IEEE 页面](https://ieeexplore.ieee.org/document/11396383)；[作者托管的正式论文 PDF](https://rssysu.github.io/assets/paper/apbd.pdf)；[arXiv 版本](https://arxiv.org/abs/2508.14558)。
- 作者表以正式 PDF 为准，共 10 人，包含 **Baodong Xu**；部分第三方索引遗漏该作者，未采用这些不完整列表。
- 所核对的作者托管 PDF 标记为将编入后续期刊卷期的版本，最终卷期页码未独立核实。因此 BibTeX 和主页只保留已确认的期刊、年份与 DOI，不补写卷期页码。

### AgroMind

- 完整标题：**Can Large Multimodal Models Understand Agricultural Scenes? Benchmarking with AgroMind**。
- 会议：NeurIPS 2025，Datasets and Benchmarks Track；*Advances in Neural Information Processing Systems* 38。
- DOI：[10.52202/085713-5271](https://doi.org/10.52202/085713-5271)。
- 来源：[NeurIPS 官方论文页](https://papers.nips.cc/paper_files/paper/2025/hash/e75dcde67f29d1e8efd0a86aaa332331-Abstract-Datasets_and_Benchmarks_Track.html)；[作者项目页](https://rssysu.github.io/AgroMind/)；[arXiv](https://arxiv.org/abs/2505.12207)。
- NeurIPS 网页作者元数据中的 `Loushuohong` 和 `Huang Jianxi`，依据作者项目页的 BibTeX 与课题组列表规范为 **Shuohong Lou** 和 **Jianxi Huang**，保留原作者次序。

### GTPBD-MM

- 完整标题：**GTPBD-MM: A Global Terraced Parcel and Boundary Dataset with Multi-Modality**。
- 当前采用的状态：**arXiv preprint，2026**。
- arXiv ID：2604.12315；DOI：[10.48550/arXiv.2604.12315](https://doi.org/10.48550/arXiv.2604.12315)。
- 来源：[arXiv 论文页](https://arxiv.org/abs/2604.12315)；[作者发布的数据集](https://huggingface.co/datasets/wxqzzw/GTPBD-MM)；[GTPBD 仓库中的多模态扩展介绍](https://github.com/Z-ZW-WXQ/GTPBD/)。
- arXiv 页面记载首次提交日期为 2026-04-14，Comments 字段仍称投稿 ACM Multimedia 2026 Dataset Track。该字段不能证明录用。因此本主页仅将其列为预印本，不标记 ACM MM 或 AAAI 已录用。
- BibTeX 使用 `@misc`，保留 `eprint`、`archivePrefix`、`primaryClass` 和预印本状态。

## 5. 参考主页与 GitHub 发布范围

- 用户提供的版式参考：[https://wenddhe0119.github.io/](https://wenddhe0119.github.io/)。
- 参考页面结构已读取，用于理解个人学术主页的内容组织方式。本站代码独立编写，未复制原站 HTML/CSS 代码、身份信息或论文内容。
- **Z-ZW-WXQ** 是上述论文官方关联代码仓库所在的 GitHub 账号。该关联不等于已经确认用户本次希望使用此账号发布个人主页，也不构成对该账号的写入授权。
- 本次交付为可用于 GitHub Pages 的静态文件。没有执行远程建库、推送或公开部署；实际发布账号及对应仓库名称应按用户使用的 GitHub 账号设置。
- 主页使用已公开的科研邮箱，不公开 CV 电话号码，也不包含访问凭据或私人联系方式。

## 6. 后续维护

更新时优先核查正式出版社、会议论文集、作者论文、作者项目页与数据集页面。预印本录用后，应同时更新主页条目、`publications.bib` 和本文件中的状态说明。若最终期刊卷期页码发生变化，应以正式出版记录为准。用户确认的个人信息变更应优先于可能滞后的公开 CV，并相应标注更新日期。


## 7. 本次采用的公开图片

图片以原始文件保存，未更改科研内容；网页只通过 CSS 控制显示尺寸。

| 文件 | 来源页面 | 原图 |
| --- | --- | --- |
| `assets/profile.jpg` | [实验室成员页](https://rssysu.github.io/people.html)，成员卡明确标注 Zhiwei Zhang，并链接上述 CV | [原图](https://rssysu.github.io/assets/img/kit/faces/zzw.jpg) |
| `assets/daterra.png` | [实验室论文列表](https://rssysu.github.io/pub.html)，DATerra 论文条目 | [原图](https://rssysu.github.io/assets/paper/daterra.png) |
| `assets/gtpbd.png` | [实验室论文列表](https://rssysu.github.io/pub.html)，GTPBD 论文条目 | [原图](https://rssysu.github.io/assets/paper/gtpbd.png) |
| `assets/gtpbd-mm.png` | [GTPBD-MM arXiv 正文](https://arxiv.org/html/2604.12315v1)，Figure 4 的 ETTerra 框架 | [原图](https://arxiv.org/html/2604.12315v1/method.png) |

头像的对应关系来自公开页面文字，并非基于人脸推断身份。论文配图仅用于介绍所列本人署名研究，相关权利归原作者或对应权利人；网站代码与说明的交付不改变这些图片的许可。

## 8. 文件检查范围

已检查本地资源、页内锚点、论文条目数量与 HTML 基础结构，并核对素材内容。当前环境未执行真实浏览器渲染或 GitHub Pages 部署测试。上线前可先双击 `index.html`，检查电脑和手机宽度下的实际显示；外链依赖各来源网站的实时可用性。
