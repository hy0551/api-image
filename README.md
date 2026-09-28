# API-image

通过公司 OpenAI 兼容中转站调用指定图片模型的 Codex Skill 部署包。

## 直接下载

- [Windows 部署包](https://github.com/hy0551/api-image/raw/refs/heads/main/api-image-win.zip)
- [macOS 部署包](https://github.com/hy0551/api-image/raw/refs/heads/main/api-image-mac.zip)
- [部署说明书](https://github.com/hy0551/api-image/raw/refs/heads/main/API-image%E9%83%A8%E7%BD%B2%E8%AF%B4%E6%98%8E%E4%B9%A6.docx)

GitHub 无法在线预览 `.zip` 和 `.docx` 文件。点击上面的链接会直接下载文件，这是正常现象。

## 安装

### Windows

1. 下载并解压 `api-image-win.zip`。
2. 双击解压目录中的 `setup.cmd`。
3. 第一次输入中转站基础网址，第二次输入 API Key。
4. 重启 Codex。

### macOS

1. 下载并解压 `api-image-mac.zip`。
2. 在终端进入解压目录，运行 `bash setup-macos.sh`。
3. 第一次输入中转站基础网址，第二次输入 API Key。
4. 重启 Codex。

默认图片模型为 `gpt-image-2.5-sunburst`。详细配置和故障排查请查看部署说明书。

## 文件校验

| 文件 | SHA-256 |
| --- | --- |
| `api-image-win.zip` | `3D019A119FBDE6FC4EC8F044F0B2E6944D9027D30A4086CE187115A1C7D6B383` |
| `api-image-mac.zip` | `876B01EBEF17E11F1CF4BD0926E244A236B57AEE966AC19322C3A94726B56956` |
| `API-image部署说明书.docx` | `CA24EF45F80DC3EF53DCF67A9CC714BDCE2087A9992E8E97161533E395890727` |
