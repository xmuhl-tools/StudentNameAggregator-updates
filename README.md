# 学生姓名汇总工具

从 QQ 邮箱只读读取学生提交材料的附件名，与名单比对后汇总成 Excel 名单（Windows x64）。

- 当前版本：**v1.2.1**（build 2）
- 最近更新：修复：去掉界面上重复的标题；安装包改用 Inno Setup 图形向导（下一步/选择目录/完成页，并在「应用和功能」里提供卸载入口）。

## 下载

| 用途 | 文件 |
|---|---|
| 首次安装（推荐，双击即装） | [StudentNameAggregator-1.2.1-win-x64-Setup.exe](https://github.com/xmuhl-tools/StudentNameAggregator-updates/releases/download/v1.2.1/StudentNameAggregator-1.2.1-win-x64-Setup.exe) |
| 便携版（解压即用） | [StudentNameAggregator-1.2.1-win-x64.zip](https://github.com/xmuhl-tools/StudentNameAggregator-updates/releases/download/v1.2.1/StudentNameAggregator-1.2.1-win-x64.zip) |

## 安装与使用

- **安装包**：双击运行 → 确认或修改安装位置（默认 `%USERPROFILE%\学生姓名汇总工具`）→ 自动创建桌面快捷方式，
  装完双击桌面图标即可用。不需要管理员权限，不写注册表；卸载 = 删除安装目录与快捷方式。
- **便携版**：解压到任意文件夹，双击里面的 `StudentNameAggregator.exe`；
  首次使用在界面里填好邮箱账号与名单、点「保存设置」即可。

详细步骤（含 QQ 邮箱授权码怎么申请）见包内《使用手册.pdf》。

## 校验（sha256）

```text
StudentNameAggregator-1.2.1-win-x64.zip
  e7e4da92389c3de9e4116cdc659d191133ec4ca593af48bb6c0db3c06b9825d2
StudentNameAggregator-1.2.1-win-x64-Setup.exe
  fa7d7498749ce4580ab7db8a6e90925ff220b4a1f822da95cecb98a5cc8b4e96
```

---

本文件由发布流程自动生成/更新（portable-app-release 技能，2026-10-02），请勿手工改动。
