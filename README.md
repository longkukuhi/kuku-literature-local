# 酷酷文献助手本地版

在 Android、macOS 和 Windows 上离线整理文献、阅读 PDF、写笔记和批注。每台设备从空库开始，文献和附件保存在设备上。[下载最新版本](https://github.com/longkukuhi/kuku-literature-local/releases/latest)

## 安装 1.0.0

| 平台 | 安装包 | 启动方式 |
| --- | --- | --- |
| Android 8.0 及以上 | `KukuLiteratureLocal-1.0.0-Android.apk` | 用系统安装器打开 APK |
| macOS 13 及以上 | `KukuLiteratureLocal-1.0.0-macOS.zip` | 解压，将「酷酷文献助手本地版.app」拖入「应用程序」。此版采用临时签名，未公证 |
| Windows 10 / 11 x64 | `KukuLiteratureLocal-1.0.0-Windows-x64.zip` | 解压后运行 `KukuLiteratureLocal.exe`，需要本机已安装 Microsoft Edge |

三个安装包、中文快速指南 `QUICKSTART.zh-CN.txt` 和校验清单 `SHA256SUMS.txt` 均在 [1.0.0 发布页](https://github.com/longkukuhi/kuku-literature-local/releases/tag/v1.0.0)。

## 加入第一篇文献

1. 选择「导入题录」，打开 RIS、CSL JSON 或 BibTeX 文件，也可以手动新建文献。
2. 在文献详情选择「附件 → 添加附件」，加入 PDF。
3. 打开 PDF 阅读、批注，或在文献详情记录笔记。断网后也可以继续编辑。

## 换设备或备份

打开「文献工具 → Wi-Fi 同步与加密备份」。在同一 Wi-Fi 或热点上，发送方生成下载地址，接收方扫码或在浏览器打开地址，下载 `.kukubackup`，再回到应用输入口令导入。地址有效期为 10 分钟，下载期间保持发送界面打开。

相同记录会跳过，同一记录的不同版本会保留为同步副本。删除只在本机生效。需要反向传送时，互换收发设备再操作一次。

同一界面也可以直接导出加密备份，包含题录、笔记、批注及可读取的附件。备份口令至少 12 个字符，请将口令与备份文件分开保管。
