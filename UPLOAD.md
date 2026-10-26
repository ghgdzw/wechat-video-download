# 介绍仓库维护说明

独立仓库：https://github.com/ghgdzw/wechat-video-download

本目录只管理软件介绍、使用教程、FAQ 和配套图片。父项目通过 `.gitignore` 忽略本目录，两个仓库各自提交，不将桌面软件源码、安装包、日志、数据库或证书复制到本仓库。

## 内容结构

```text
README.md
docs/
  USAGE.md
  FAQ.md
images/
  logo.png
  01-download-center.png
UPLOAD.md
```

## 下载与引流入口

- 微信公众号：HG阿伟。
- 官网资源库：https://www.hgawei.cn/software
- 现有视频版 v0.1.6 安装包：https://www.hgawei.cn/api/v1/desktop/updates/be1cd0cd-5b77-452c-868c-549b0007d2f7/installer
- 公众号图文下载器：https://github.com/ghgdzw/wechat-download

官网公开资源库目前未列出视频版单独详情页，因此不编造视频版详情地址。已有安装包链接来自视频版发布记录，并在整理时核对公开响应；上线新版本或新增官网详情页后同步修改三份用户文档。

## 版本与图片

介绍根据 v0.1.6 源码和现有使用说明整理。截图沿用项目已有的 `artifacts/protected-0.1.6/frontend-validation.png`，是下载中心的浏览器预览，未连接微信、没有下载任务；文档明确标注，不能充当真实下载验收证据。Logo 来自项目现有应用图标。

不自动把主项目后续新增功能写入本介绍，也不将界面预览、回归测试等同于微信各版本兼容性或全流程实测。这里不新增软件开源许可证或变更桌面程序、上游组件原有授权。
