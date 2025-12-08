# Lucas 的 AI 輔助開發工具包

輔助開發的好用 AI 工具包，簡化我在 Claude Code 中的開發工作流程。

## 功能特色

此插件提供強大的指令來增強開發體驗：

- **📋 建立計畫**: 搭配 Claude Code Plan Mode 來流暢地建立詳細的實作計畫
- **💬 Commit 訊息**: 自動生成符合規範的 Git commit 訊息

## 安裝

在 Claude Code 中安裝插件：

```
/plugin install ycs77-dev@ycs77
```

## 指令說明

### `/ycs77-dev:make-plan`

流暢地為您的專案或功能建立詳細的實作計畫。與 Claude Code 的 Plan Mode 無縫整合，幫助您思考複雜的實作方案。

**使用方式：**

```bash
/ycs77-dev:make-plan [專案或功能描述]
```

**範例：**

```bash
/ycs77-dev:make-plan 使用 JWT tokens 新增使用者認證系統
```

**功能特點：**
- 強調避免過度設計
- 使用繁體中文生成計畫
- 需要時會使用 AskUserQuestion 進行確認
- 結構化的實作規劃方法

### `/ycs77-dev:commit-message`

生成符合慣例提交規範的專業 Git commit 訊息。

**使用方式：**

```bash
/ycs77-dev:commit-message [可選的上下文資訊]
```

**範例：**

```bash
/ycs77-dev:commit-message 修復了使用者無法使用含有特殊字元密碼進行認證的登入錯誤
```

**功能特點：**
- 使用英文生成 commit 訊息
- 遵循慣例提交格式
- 支援多種變更類型：Add、Update、Remove、Fix、Improve、Optimize
- 使用祈使語氣（"Add feature" 而非 "Added feature"）
- 未提供上下文時會自動分析 git diff
- 保持訊息簡潔明確（主旨在 72 字元以內）

**變更類型：**
- **Add**: 新增功能
- **Update**: 更新現有功能
- **Remove**: 移除功能
- **Fix**: 修復錯誤
- **Improve**: 改進功能（不包括效能）
- **Optimize**: 效能優化

## 使用技巧

### Make Plan 指令

1. **具體明確**：提供清晰的上下文說明您想要建立什麼
2. **相信流程**：必要時指令會提出後續問題
3. **仔細審查**：計畫應在實作前經過審查和調整

### Commit Message 指令

1. **先暫存變更**：在生成 commit 訊息前先執行 `git add`
2. **提供上下文**：如果變更較複雜，請添加簡短的上下文作為參數
3. **提交前審查**：使用前務必審查生成的訊息

## 作者

Lucas Yang (yangchenshin77@gmail.com)

## 授權

MIT
