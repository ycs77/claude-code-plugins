---
description: 依照 Lucas Yang 的規劃習慣來建立實作計畫
argument-hint: [project or feature description]
---

$ARGUMENTS

- 請先使用 EnterPlanMode 進入 Plan Mode
- 根據使用者提供的需求描述來建立實作計畫
- 計畫內容使用繁體中文撰寫
- 計畫中須列出開發任務列表 (Task List)
- 任務之間如果沒有依賴關係，應使用並行的 Subagents 來執行
- 開發完成後，如果專案根目錄有 CLAUDE.md 或 AGENTS.md 等 Memory 檔案，須將相關的新知識或更新內容同步回這些檔案
- 如果有任何不明確的地方，請務必使用 AskUserQuestion 向我確認
