# 📋 MR693 AI 任務看板 (My Kanban)

> **Antigravity AI 自動化任務管理與對話萃取系統**  
> 透過 AI Agent 與 GitHub Issues / Projects 緊密整合，實現對話討論直接轉化為雲端任務卡片。

---

## 🧭 核心功能與入口

* 📊 **[GitHub Projects 專案看板](https://github.com/kevinz1979/my-kanban/projects)**：可視化拖曳式 Kanban 看板（待辦 / 進行中 / 已完成）。
* 📌 **[GitHub Issues 任務清單](https://github.com/kevinz1979/my-kanban/issues)**：AI 自動化建構的結構化任務卡片與行動清單。
* 🌐 **[線上儀表板 (GitHub Pages)](https://kevinz1979.github.io/my-kanban/)**：跨裝置免登入、支援搜尋與分類篩選之任務總覽。

---

## 🤖 AI 自動化工作流

在 Antigravity 任何對話中，只需輸入以下觸發語句：
* **「整理對話」**
* **「更新任務」**
* **「記錄為任務」**

AI 將自動執行：
1. 查詢當前倉庫既有 Issues，避免重複建立。
2. 萃取討論核心決策、背景說明與行動清單 (Checklist)。
3. 自動呼叫 API 於本倉庫建立對應業務領域的 Issue 任務卡片，並同步進入專案看板。

---

## 🗂️ 業務領域標籤規範

| 標籤 | 業務領域說明 |
| :--- | :--- |
| `[房產財務]` | 房產租售決策、銀行貸款評估、現金流防護網 |
| `[家庭教育]` | 浩浩六年學習規劃、PBL 專案導向學習、每週共學 |
| `[AI證照]` | iPAS AI 應用規劃師備考、核心高頻術語庫、教材改寫 |
| `[知識資產]` | MR693 檔案目錄結構重整、04_archives 活化、筆記庫維護 |
| `[系統工程]` | 雲端同步維護、自動化工作流、MCP 工具整合 |
