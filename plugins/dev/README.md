# Lucas 的 AI 輔助開發工具包

輔助開發的 AI 工具包，優化我在 Claude Code 中的開發工作流程。

## 功能特色

此插件提供以下指令來增強開發體驗：

- 📋 **建立計畫**: 搭配 Claude Code Plan Mode 來流暢地建立詳細的實作計畫

## 安裝插件

在 Claude Code 中安裝插件：

```
/plugin install ycs77-dev@ycs77
```

## 指令說明

### `/ycs77-dev:plan`

流暢地為您的專案或功能建立詳細的實作計畫。與 Claude Code 的 Plan Mode 無縫整合，幫助您思考複雜的實作方案。

**使用方式：**

```bash
/ycs77-dev:plan [專案或功能描述]
```

**範例：**

```bash
/ycs77-dev:plan 使用 JWT tokens 新增使用者認證系統
```

**功能特點：**
- 強調避免過度設計
- 使用繁體中文生成計畫
- 需要時會使用 AskUserQuestion 進行確認
- 結構化的實作規劃方法

## 使用技巧

### Plan 指令

1. **具體明確**：提供清晰的上下文說明您想要建立什麼
2. **相信流程**：必要時指令會提出後續問題
3. **仔細審查**：計畫應在實作前經過審查和調整

## 版本歷史

### v1.0.0
- 初始版本
- 支援 Make Plan 指令
- 支援 Commit Message 指令

### v1.0.1
- 優化 Commit Message 指令輸出格式說明

### v1.0.2
- 更新描述文字

### v1.1.0
- 將 `/ycs77-dev:make-plan` 指令更名為 `/ycs77-dev:plan`

### v1.2.0
- 移除 `/ycs77-dev:commit-message` 指令（可使用 [ycs77/skills](https://github.com/ycs77/skills) 的 commit-message skill 替代）

## 作者

Lucas Yang (yangchenshin77@gmail.com)

## 授權

MIT License
