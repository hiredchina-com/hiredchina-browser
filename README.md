# HiredChinaCRM

[下载最新版本](https://github.com/hiredchina-com/hiredchina-browser/releases/latest)

## 选择安装包

进入最新版本的 Releases 页面，在 **Assets** 中选择对应文件：

| 系统 | 文件名结尾 |
| --- | --- |
| Windows 64 位 | `win-x64.exe` |
| Mac，Apple 芯片（M 系列） | `mac-arm64.dmg` |
| Mac，Intel 芯片 | `mac-x64.dmg` |

Mac 可通过苹果菜单 →“关于本机”查看芯片类型。安装时无需下载 `.blockmap`、`.yml` 或 `.zip` 文件。

## macOS 安装与首次打开

1. 打开下载的 `.dmg`，将 **HiredChinaCRM** 拖到“应用程序”文件夹。
2. 从“应用程序”打开 HiredChinaCRM。
3. 如果提示“Apple 无法验证 HiredChinaCRM 是否包含可能危害 Mac 安全或泄漏隐私的恶意软件”，点击“完成”。
4. 打开“系统设置 → 隐私与安全性”，向下找到安全性区域，点击 HiredChinaCRM 对应的“仍要打开”。
5. 按提示验证身份，再点击“打开”。

当前 Mac 版本未经 Apple 开发者认证或公证，因此首次打开可能需要以上授权。仅为从本仓库下载的应用执行这些步骤，无需关闭系统整体安全检查。

如果找不到“仍要打开”，先再次尝试打开应用，再返回“隐私与安全性”。较旧 macOS 的入口为“系统偏好设置 → 安全性与隐私 → 通用”。具体操作见 [Apple 官方说明](https://support.apple.com/zh-cn/102445)。

### 提示“已损坏，无法打开”

这与“Apple 无法验证”的提示不同。请先退出旧应用，从本仓库下载最新版本并重新安装。请使用 `v6.2.5` 或更新版本。

如果最新版本仍提示“已损坏”，请通过本仓库 [Issues](https://github.com/hiredchina-com/hiredchina-browser/issues) 提供应用版本、macOS 版本、芯片类型和提示截图，便于排查。

## Windows 安装

1. 下载 `win-x64.exe` 安装包并运行，按向导完成安装。
2. 如果出现“Windows 已保护你的电脑”，确认安装包来自本仓库后，点击“更多信息 → 仍要运行”。当前 Windows 安装包未使用发行证书，可能出现未知发布者提示。
3. 安装完成后打开 HiredChinaCRM。

### Windows 10 登录背景没有动画

登录背景遵循系统的“减少动态效果”设置。请打开“设置 → 轻松使用 → 显示”，检查“在 Windows 中显示动画”。关闭此选项时，登录背景保持静止，属于预期行为；希望显示动画时，可以开启该选项并重新打开应用。

系统设置入口见 [Microsoft 官方说明](https://support.microsoft.com/en-gb/accessibility/windows/make-it-easier-to-focus-on-tasks)。如果该选项已经开启，但背景仍不动，请在 Issues 中提供 Windows 版本、应用版本和该选项的状态。背景动画不会参与账号验证。

## 更新

- **Windows**：应用发现新版后在后台下载；下载完成后可点击“重启更新”，也可正常退出应用，让更新安装后在下次打开时生效。
- **macOS**：应用提示新版后打开下载页面，请下载对应 `.dmg`，退出旧应用，再将新版拖到“应用程序”替换。若再次出现首次打开提示，按上方授权步骤操作。
