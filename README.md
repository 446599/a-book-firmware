# A Book 固件发布

小纸 Pico `read-pico-4.7` 的固件发布与在线刷机入口。

- [直接连接设备并刷写](https://446599.github.io/a-book-firmware/)
- [固件版本与下载包](https://github.com/446599/a-book-firmware/releases)

本仓库不包含 A Book 固件工程源码或刷机页源码。固件 ZIP、清单、第三方许可和 SHA-256 校验文件作为 GitHub Release 附件发布。Pages 工作流通过私有源仓库的只读部署密钥临时获取网页文件，校验所选 Release 的 ZIP，再提取刷机页所需镜像；刷机页不会依赖跨域下载。

仓库默认分支和 Release 标签的自动源码压缩包只含说明与部署配置；网页文件不会提交到本仓库。

刷写需要支持 Web Serial 的桌面 Chrome 或 Edge，并通过 USB 连接小纸 Pico。网页会校验板型、分区布局、镜像摘要和设备写入结果；请按页面状态提示完成首次安装、升级或修复。
