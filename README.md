# 学生姓名汇总工具

从 QQ 邮箱只读读取学生提交材料的附件名，与名单比对后汇总成 Excel 名单（Windows x64）。

- 当前版本：**v1.2**（build 1）
- 最近更新：首个公开版本：图形界面版（三步操作、进度与取消、结果一键打开）、可选的加密记住授权码、单文件 exe，附完整使用手册。

## 下载

| 用途 | 文件 |
|---|---|
| 首次安装（推荐，双击即装） | [StudentNameAggregator-1.2-win-x64-Setup.exe](https://github.com/xmuhl-tools/StudentNameAggregator-updates/releases/download/v1.2/StudentNameAggregator-1.2-win-x64-Setup.exe) |
| 便携版（解压即用） | [StudentNameAggregator-1.2-win-x64.zip](https://github.com/xmuhl-tools/StudentNameAggregator-updates/releases/download/v1.2/StudentNameAggregator-1.2-win-x64.zip) |

## 安装与使用

- **安装包**：双击运行 → 确认或修改安装位置（默认 `%USERPROFILE%\学生姓名汇总工具`）→ 自动创建桌面快捷方式，
  装完双击桌面图标即可用。不需要管理员权限，不写注册表；卸载 = 删除安装目录与快捷方式。
- **便携版**：解压到任意文件夹，双击里面的 `StudentNameAggregator.exe`；
  首次使用在界面里填好邮箱账号与名单、点「保存设置」即可。

详细步骤（含 QQ 邮箱授权码怎么申请）见包内《使用手册.pdf》。

## 校验（sha256）

```text
StudentNameAggregator-1.2-win-x64.zip
  2f272be4bbe27f1bb60a28e3f49d233e32f172d5530751d1a04bad67ebfb6c05
StudentNameAggregator-1.2-win-x64-Setup.exe
  cbab4573ad2db87649dbd6d037528f44356c99619574b0254ce8183b5bd3ce97
```

---

本文件由发布流程自动生成/更新（portable-app-release 技能，2026-10-02），请勿手工改动。
