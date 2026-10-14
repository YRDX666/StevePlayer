# Steve Player

Q某乐Steve Player 桌面版。

## 下载

最新安装包请到本仓库的 **Releases** 页面下载：

| 版本 | 安装包 | 大小 | SHA-256 |
|---|---|---|---|
| 2.0.1 | StevePlayer-Setup-2.0.1.exe | 106.36 MB | `8DB0A1BD8979A5C7674C12CFDABC2E85CE74A648DAE3F892D249162858CE3D64` |

> 2.0.1 对应的发行版本标签为 `v2.0.1`。

## 安装

1. 在 **Releases** 页面下载 `StevePlayer-Setup-2.0.1.exe`。
2. 双击运行，按安装向导提示完成安装。
3. 卸载：使用开始菜单中的卸载入口，或安装目录下的 `uninstall.exe`。

## 校验安装包

下载后可在 PowerShell 中核对文件哈希，确认安装包完整且未被篡改：

```powershell
Get-FileHash .\StevePlayer-Setup-2.0.1.exe -Algorithm SHA256
```

输出应与上表中的 SHA-256 一致。

## 系统要求

- Windows 10 / Windows 11（64 位）
- 安装路径由安装程序决定，默认以安装向导显示为准

## 说明

- 本仓库仅用于发布安装包，不含源码。
- 安装包为 106.36 MB，超过 GitHub 网页直接上传文件到仓库的 25 MB 限制，
  因此安装包以 **Release 附件** 形式提供（单个附件上限 2 GB）。
