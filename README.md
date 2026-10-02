# 学生姓名汇总工具

从 QQ 邮箱只读读取学生提交材料的附件名，与名单比对后汇总成 Excel 名单（Windows x64）。

- 当前版本：**v1.3.1**（build 4）
- 最近更新：更新手册内嵌截图（补齐界面右上角的「检查更新」按钮说明）；版本号在三处显示面保持一致。

## 下载

| 用途 | 文件 |
|---|---|
| 首次安装（推荐，双击即装） | [StudentNameAggregator-1.3.1-win-x64-Setup.exe](https://github.com/xmuhl-tools/StudentNameAggregator-updates/releases/download/v1.3.1/StudentNameAggregator-1.3.1-win-x64-Setup.exe) |
| 便携版（解压即用） | [StudentNameAggregator-1.3.1-win-x64.zip](https://github.com/xmuhl-tools/StudentNameAggregator-updates/releases/download/v1.3.1/StudentNameAggregator-1.3.1-win-x64.zip) |

## 安装与使用

- **安装包**：双击运行 → 确认或修改安装位置（默认 `%USERPROFILE%\学生姓名汇总工具`）→ 自动创建桌面快捷方式，
  装完双击桌面图标即可用。不需要管理员权限，不写注册表；卸载 = 删除安装目录与快捷方式。
- **便携版**：解压到任意文件夹，双击里面的 `StudentNameAggregator.exe`；
  首次使用在界面里填好邮箱账号与名单、点「保存设置」即可。

详细步骤（含 QQ 邮箱授权码怎么申请）见包内《使用手册.pdf》。

## 自动更新

程序启动时会在后台读取本仓库的更新清单 ⟦update.json⟧（清单带 RSA-2048/SHA-256 签名，
客户端内置公钥验签，签名不符即拒绝），发现新版本会**弹窗询问**：
确认后自动下载、校验 sha256 与签名、替换文件并重新打开；选择"否"会跳过该版本。
也可在程序界面点「检查更新」手动检查。
## 校验（sha256）

```text
StudentNameAggregator-1.3.1-win-x64.zip
  b4fd9188ed005ded59e66bd4d85a0e542b687f1cb148be5fffe3f3d80e516250
StudentNameAggregator-1.3.1-win-x64-Setup.exe
  0f9fea0c4b6caa09ce6e86ce31b935160771e58d0ebda3ea5345f83f5065be20
```

---

本文件由发布流程自动生成/更新（portable-app-release 技能，2026-10-02），请勿手工改动。
