# Kiro Account Manager

Kiro 账号管理器。源码闭源，本仓库仅发布安装包。

## 下载最新版

前往 [Releases](../../releases/latest) 下载对应平台安装包：

- **Windows**：`kiro-account-manager-<version>-x64-setup.exe`
- **macOS Apple Silicon**：`*-arm64.dmg`
- **macOS Intel**：`*-x64.dmg`

## macOS 首次运行

应用未签名，如遇 Gatekeeper 拦截（"无法打开，因为无法验证开发者"），安装后终端执行：

```bash
xattr -cr "/Applications/Kiro Account Manager.app"
```

再重新打开应用。

## 自动更新

v1.7.95 起应用内更新指向本仓库；更早版本请手动下载安装本仓库最新版一次，之后恢复自动更新。
