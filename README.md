# Warcraft III MPQ 文件

保存 Warcraft III Frozen Throne 的四个 MPQ 文件，供下载和校验。

## 下载

文件保存在 [GitHub Release](https://github.com/Amo-zwk/War3-MPQ/releases/tag/mpq-2026-10-22) 中。请展开页面底部的 **Assets** 下载，或使用以下链接：

| 文件 | 大小（字节） | 下载 |
| --- | ---: | --- |
| War3.mpq | 451,831,950 | [下载](https://github.com/Amo-zwk/War3-MPQ/releases/download/mpq-2026-10-22/War3.mpq) |
| War3x.mpq | 356,761,476 | [下载](https://github.com/Amo-zwk/War3-MPQ/releases/download/mpq-2026-10-22/War3x.mpq) |
| War3xLocal.mpq | 100,480,115 | [下载](https://github.com/Amo-zwk/War3-MPQ/releases/download/mpq-2026-10-22/War3xLocal.mpq) |
| war3patch.mpq | 55,646,795 | [下载](https://github.com/Amo-zwk/War3-MPQ/releases/download/mpq-2026-10-22/war3patch.mpq) |

总计 **964,720,336 字节**（约 920 MiB）。MPQ 文件以原始文件形式上传，未重新打包。

## 校验

[SHA256SUMS.txt](SHA256SUMS.txt) 提供各文件的 SHA-256 校验值；[manifest.json](manifest.json) 提供文件名、大小和校验值。

在 PowerShell 中校验下载的文件：

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath .\War3.mpq, .\War3x.mpq, .\War3xLocal.mpq, .\war3patch.mpq
```

仓库源码下载 ZIP 和 `git clone` 包含说明与校验文件；MPQ 文件请从 Release 下载。
