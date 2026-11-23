# Metering Hardware Lab

一个面向电能计量、智能量测、PCB、嵌入式硬件设计的个人工程师网站 Demo。

## 部署到 GitHub Pages

### 方法 A：网页上传（最简单）
1. 在 GitHub 新建一个公开仓库，例如 `metering-hardware-lab`
2. 上传 `index.html`、`style.css` 和 `assets/`
3. 进入仓库 `Settings → Pages`
4. `Build and deployment` 选择 `Deploy from a branch`
5. Branch 选择 `main` / `/ (root)`
6. 保存，等待 GitHub Pages 构建完成

### 方法 B：个人主页仓库
如果仓库名称直接使用：

`你的GitHub用户名.github.io`

网站地址就是：

`https://你的GitHub用户名.github.io/`

## 替换自己的图片

以后可以把图片放进 `assets/`，然后把 HTML 中的示例区域替换成：

```html
<img src="assets/your-board.jpg" alt="我的PCB">
```

建议 PCB 图片先压缩到约 0.5–1.5 MB/张，网站加载速度会更好。

## 设计说明

当前 Demo 是纯 HTML + CSS，无数据库、无构建工具、无服务器依赖，适合 GitHub Pages 免费部署。
