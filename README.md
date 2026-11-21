# Absolutely Perfect Specimen 简体中文补丁

《绝对完美的实验体》是 chambersoft 制作的视觉小说。本简体中文补丁由 **Codex 全程制作**，涵盖翻译、补丁开发、安装工具及测试。补丁为非官方本地化，适配 **Windows PC 版 1.2.1**，需要自备原版游戏。

[下载简体中文补丁](https://github.com/1530292501-wq/absolutely-perfect-specimen-zh-cn/releases/latest) · [获取原版游戏](https://chambersoft.itch.io/absolutely-perfect-specimen)

## 安装

1. 从 Release 页面的 **Assets** 下载 `APS-1.2.1-zh-CN-v1.0.zip`，完整解压后关闭游戏。
2. 双击 `Install.cmd`，输入包含 `AbsolutelyPerfectSpecimen.exe` 的游戏根目录。
3. 看到 `Installed and verified` 后启动游戏。首次启用默认为简体中文，标题画面和设置页可切换 **简体中文／English**。

安装器会校验原版文件和补丁文件的 SHA-256。其他构建或同名文件冲突可能导致安装停止。安装无需管理员权限。

## 校验与卸载

- 要校验下载的 ZIP，在 PowerShell 运行 `Get-FileHash -Algorithm SHA256 .\APS-1.2.1-zh-CN-v1.0.zip`，对照 Release 附件 `SHA256SUMS.txt`。
- 要核对已安装的文件，运行 `Verify.cmd` 并输入游戏根目录。
- 卸载前先切换到 **English** 并退出游戏，再运行 `Uninstall.cmd`，输入同一个游戏根目录。卸载会移除补丁文件及对应的 Ren’Py 编译缓存，保留原版文件和存档。

## 汉化范围

- 全部 443 条剧情文本，含结局。
- 346 条界面及引擎字符串，另保留 13 条按键名、字体名、符号或数字等条目。
- 标题、片头和片尾文字，以及两处画内英文的中文注释。

Windows 上已验证主线、语言切换及新建存档的保存和加载。其他平台、游戏版本及任意旧存档未逐项验证。完整测试范围与已知问题见压缩包内的文档。

## 反馈与署名

反馈时请提供游戏和补丁版本、复现步骤，以及安装器或游戏的报错文字。[提交问题](https://github.com/1530292501-wq/absolutely-perfect-specimen-zh-cn/issues/new)

原作由 chambersoft 制作。补丁包仅提供本地化文件、安装工具、文档及 Noto Sans CJK SC 字体，字体使用 SIL Open Font License 1.1，许可文件随包提供。原作的内容提示见 [作者页面](https://chambersoft.itch.io/absolutely-perfect-specimen)。
