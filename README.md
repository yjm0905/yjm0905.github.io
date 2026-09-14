# Jinming Yao (姚金名) @ DILab, USTC

静态 HTML / CSS 学术主页，无构建步骤和 JavaScript 依赖。

## 排版与素材

参考 `http://home.ustc.edu.cn/~zzy0929/Home/` 的 jemdoc 风格，采用相同的页首结构、中文楷体姓名、英文姓名、校徽、酒红标题、蓝色链接和论文列表格式。去掉上一版额外的导航与示例项目。

桌面端按参考页 110% 缩放后的字号、尺寸和页面位置重建，不对整个 body 做 transform；手机端单独重排照片、校徽和个人资料。

- `index.html`：全部个人资料与论文信息。
- `style.css`：桌面、手机和打印样式。
- `images/profile.png`：用户最新上传的正装证件照，原文件保留不变。头像居中展示，点击可看原图；不再使用先前的骑行照片。
- `images/ustc.png`：中科大校徽，来源为参考主页的公开素材 `http://home.ustc.edu.cn/~zzy0929/Home/Profile/ustc.png`。

没有复制参考作者的个人经历、论文、导师关系或联系方式。

## 已填入的个人资料

- 中文姓名：姚金名；英文姓名：Jinming Yao。
- 身份：Ph.D. Student / 博士研究生，不写 Dr. 或已获得博士学位。
- 单位：中国科学技术大学软件学院，数据智能实验室（DILab）。
- 导师：汪炀（Yang Wang）与王旭（Xu Wang），已添加至页首和中英文简介，并链接各自主页。
- 邮箱：`yjm0905@mail.ustc.edu.cn`。
- 2021–2025：东北农业大学，数据科学与大数据技术专业，理学学士。
- 2025–Present：中国科学技术大学软件学院，博士在读。
- 研究兴趣：Time Series、AI Agents、Tool Generation、AI for Chemistry。Research Interests 区域仅使用英文，中文简介保持不变。

资料与导师关系依据用户提供的信息填写；没有擅自补充博士专业、校区、邮编、入学月份或预计毕业年份。导师姓名和主页链接已通过用户提供的实验室成员页核对：`https://di.ustc.edu.cn/_upload/tpl/17/94/6036/template6036/members.htm`。

## 论文

**Timely and Stable Online Forecasting under Delayed Supervision**

Jinming Yao, Jinmiao Hu, Yudong Zhang, Zhengyang Zhou, Pengkun Wang, Binwu Wang, Xu Wang*, Yang Wang*.

作者顺序及通讯作者星号按用户提供的论文首页截图填写；本人姓名加粗。Publications 仅展示标题、作者及 ICDE 2027 会议信息，不再显示 `Accepted (first round).`。录用消息保留在 Exciting News 中，不编造 DOI 或页码。

新闻中的录用日期为 `[2026.09]`；`ICDE 2027` 是会议年份，保持不变。

会议全称和 CCF A 分类参考 `https://www.ccf.org.cn/Academic_Evaluation/DM_CS/`。

当前尚未提供论文 PDF 和最终代码链接，因此没有添加假链接，也没有把论文首页截图当作全文发布。

## 可继续补充

1. 可公开的论文 PDF / arXiv 地址和最终代码仓库地址。
2. Google Scholar、CV、办公地址或其他需要展示的资料（可选）。

## 本地预览

直接用浏览器打开 `index.html`，或在仓库目录运行：

```powershell
python -m http.server 8765 --bind 127.0.0.1
```

然后访问 `http://127.0.0.1:8765/`。

## 发布

线上地址为 `https://yjm0905.github.io/`。现有 Pages 发布源为 `main` 分支的根目录，确认内容后沿用该配置发布即可。

更新推送到 `main` 后，由仓库现有的 GitHub Pages 流程构建并发布。GitHub Free 下请保持主页仓库为 Public，以免取消发布 Pages。规则参考：`https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/managing-repository-settings/setting-repository-visibility`。
