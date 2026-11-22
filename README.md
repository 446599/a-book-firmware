# A Book 固件发布

小纸 Pico `read-pico-4.7` 的公开固件下载与发布页面。

本仓库不包含固件源码。版本化固件包、清单、第三方许可和 SHA-256 校验文件均作为 GitHub Release 附件发布。GitHub 自动生成的标签源码压缩包只含仓库说明和 Pages 部署配置。

## 下载与安装

- [固件版本列表](https://github.com/446599/a-book-firmware/releases)
- [固件下载页](https://446599.github.io/a-book-firmware/)
- [A Book 刷机页](https://446599.github.io/a-book/)

每个 Release 附有完整 ZIP 固件包、`manifest.json` 和 `SHA256SUMS.txt`。安装前先核对 SHA-256，并通过 A Book 刷机页执行受支持的设备安装流程。

## 兼容性

`manifest.json` 记录适用板型、版本、镜像用途、Flash 偏移和 SHA-256 摘要。请勿混用不同版本的镜像。
