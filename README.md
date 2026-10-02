# 学生姓名汇总工具

更新发布通道：更新清单 + Windows x64 下载包（StudentNameAggregator）。

- 当前版本：**v1.3.2**（build 5）
- 最近更新：修复其他电脑首次安装的两个问题：安装包自动创建 config.json 与空白名单模板 roster\学生名单.txt（已存在绝不覆盖）；界面里填好设置后直接点「开始汇总」即可，设置自动保存，不再要求先点「保存设置」。另修复运行日志里的版本号显示。

## 下载

| 用途 | 文件 |
|---|---|
| 首次安装（推荐，双击即装） | [StudentNameAggregator-1.3.2-win-x64-Setup.exe](https://github.com/xmuhl-tools/StudentNameAggregator-updates/releases/download/v1.3.2/StudentNameAggregator-1.3.2-win-x64-Setup.exe) |
| 便携版（解压即用） | [StudentNameAggregator-1.3.2-win-x64.zip](https://github.com/xmuhl-tools/StudentNameAggregator-updates/releases/download/v1.3.2/StudentNameAggregator-1.3.2-win-x64.zip) |

## 安装与使用

- **安装包**：双击运行 → 确认或修改安装位置（默认 `%USERPROFILE%\学生姓名汇总工具`）→ 自动创建桌面快捷方式。
  装完双击桌面图标即可用：安装包已建好 `config.json` 与空白名单 `roster\学生名单.txt`，
  首次使用在界面里填好邮箱账号、把名单补上即可（点「开始汇总」时设置自动保存）。
  不需要管理员权限，不写注册表；卸载 = 删除安装目录与快捷方式。
- **便携版**：解压到任意文件夹，双击里面的 `StudentNameAggregator.exe`；
  首次使用在界面里填好邮箱账号与名单、点「开始汇总」即可（设置会自动保存）。

详细步骤（含 QQ 邮箱授权码怎么申请）见包内《使用手册.pdf》。

## 自动更新

程序启动时会在后台读取本仓库的更新清单 ⟦update.json⟧（清单带 RSA-2048/SHA-256 签名，
客户端内置公钥验签，签名不符即拒绝），发现新版本会**弹窗询问**：
确认后自动下载、校验 sha256 与签名、替换文件并重新打开；选择"否"会跳过该版本。
也可在程序界面点「检查更新」手动检查。
## 校验（sha256）

```text
StudentNameAggregator-1.3.2-win-x64.zip
  b04806db3a20caaea8f78d16b74ea3cc3cf76bd48fc7657d1605303a843bc3ea
StudentNameAggregator-1.3.2-win-x64-Setup.exe
  dda9f3c4ec9094d57084d3b41e2fc8875f4e19736496b1354be361cebbcf7974
```

---

本文件由发布流程自动生成/更新（portable-app-release 技能，2026-10-03），请勿手工改动。
