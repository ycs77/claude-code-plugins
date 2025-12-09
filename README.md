# Lucas 常用的 Claude Code Plugins

這裡是我常用的 Claude Code 插件倉庫，可能會有各種不同類型的插件。

## Plugins

| Name | Description | Contents |
|------|-------------|----------|
| [ycs77-dev](./plugins/dev) | 輔助開發的好用 AI 工具包 | **Command:** `/ycs77-dev:make-plan` - 搭配 Claude Code Plan Mode 來流暢地建立詳細的實作計畫<br />**Command:** `/ycs77-dev:commit-message` - 生成符合規範的 Git commit 訊息 |
| [notification-basic-win](./plugins/notification/basic-win) | 聲音通知插件 (Windows) | 當 Claude Code 執行結束或停止時，自動播放提示音通知用戶<br />**Hook:** `Notification` - 發送通知時播放音效<br />**Hook:** `Stop` - 停止執行時播放音效 |
| [notification-basic-mac](./plugins/notification/basic-mac) | 聲音通知插件 (macOS) | 當 Claude Code 執行結束或停止時，自動播放提示音通知用戶<br />**Hook:** `Notification` - 發送通知時播放音效<br />**Hook:** `Stop` - 停止執行時播放音效 |

## 在 Claude Code 中安裝

在 Claude Code 中執行以下命令，將此 repo 註冊為 Claude Code 插件市場：

```
/plugin marketplace add ycs77/claude-code-plugins
```

## 作者

Lucas Yang (yangchenshin77@gmail.com)

## 授權

[MIT License](LICENSE.md)
