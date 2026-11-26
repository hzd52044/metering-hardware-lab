# 计量硬件实验室（Metering Hardware Lab）

一个专注于**电能计量、智能量测、充电桩控制、工业通信与嵌入式硬件设计**的个人工程记录站，用于沉淀真实的硬件项目经历、调试排错笔记、AI 辅助硬件设计实测以及硬件照片与视频分享。

- **在线访问**：`https://hzd52044.github.io/metering-hardware-lab/`
- **仓库地址**：`https://github.com/hzd52044/metering-hardware-lab`

## 页面内容模块

- **最新更新横幅**：首页顶部直达最新发布的文章或实测记录。
- **硬件项目（`#projects`）**：展示直流计量单元、智能量测开关、充电桩控制器、工业通信板等核心硬件项目。
- **实验笔记（`#notes`）**：记录真实调试排错与工具实测（如《变废为宝：废弃无线电子标签改造超低功耗“墨水屏背题器”》《AI 画 PCB 实测对比：Gemini 4 Neon vs DeepSeek 4.1 Flash》）。
- **工程视频（`#vlog`）**：预留 B 站 / 抖音实验视频展示区。
- **关于实验室（`#about`）**：个人硬件工程理念与方向简介。
- **联系与关注（`#contact`）**：微信、抖音、哔哩哔哩（B站）二维码，欢迎同行交流。

## 目录结构

```text
metering-hardware-lab-demo/
├── index.html                   # 首页
├── note-eink-flashcard.html     # 实验笔记：废弃无线电子标签改造墨水屏背题器
├── note-kicad-ai-compare.html   # 实验笔记：AI 画 PCB 实测对比文章页
├── style.css                    # 全站与文章页样式表（支持桌面端与移动端自适应）
├── assets/                      # 图片与静态资源
│   ├── qr-wechat.jpg            # 微信二维码
│   ├── qr-douyin.jpg            # 抖音二维码
│   ├── qr-bilibili.jpg          # B站账号二维码
│   ├── eink-flashcard/          # 墨水屏背题器改造实拍图
│   └── kicad-compare/           # KiCad AI 对比实测截图
└── README.md                    # 项目说明
```

## 技术特点

- 纯静态 **HTML + CSS** 实现，无数据库、无前端构建依赖、加载速度快。
- 直接托管于 **GitHub Pages**，提交更新后 1–2 分钟自动发布生效。
- 本地双击 `index.html` 即可离线预览。
