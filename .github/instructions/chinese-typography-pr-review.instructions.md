---
name: chinese-typography-pr-review
description: "Review Simplified_Chinese / Traditional_Chinese translations for game UI. Ensure optimal Chinese-English mixed typography, readability, and consistency."
applyTo: 
  - "Simplified_Chinese/**"
  - "Traditional_Chinese/**"
---

# 中文翻譯 UI 排版規範（遊戲最終顯示）

## 🎯 核心原則

本規範目標：

- 提升 遊戲 UI 可讀性
- 優化 中英混排視覺節奏
- 保持 一致性與專業感
- 避免因字型導致的 排版錯位

---

# 1. 全形 → 半形（強制）

以下符號一律使用半形：

| 全形 | 半形 |
|------|------|
| （ | ( |
| ） | ) |
| ： | : |

---

# 2. 中英混排空白規則（核心）

所有「中文 + 英文 / 數字 / 符號」之間必須有空白

正確：
技能 Level 5  
攻擊 +10%  
需要 Gold 100  
冷卻時間 5 sec  

錯誤：
技能Level 5  
攻擊+10%  
需要Gold100  

---

# 3. 括號排版

左括號前需空白：

技能 (Level 5)  
Fire Ball (強化)  

右括號後需空白（若後面是文字）：

完成) 任務  
Buff) Active  

標點例外：

(Level).  
(強化)，提升效果  

---

# 4. 中括號排版

中文前：

任務 [Quest]  

右側：

[Buff] Active  

---

# 5. 數值與單位

造成 100 傷害  
持續 5 秒  
10 HP  
5 sec  
+10%  

---

# 6. 技能名稱與英文

使用 Fire Ball  
啟動 Power Mode  

---

# 7. 行首清理

(技能描述)  
[Buff] 效果  

---

# ✔ PR 檢查清單

- 是否存在全形標點
- 中英是否有空白
- 括號是否正確
- 中括號是否正確
- 數值是否清楚
- 行首是否乾淨
- UI 是否自然

---

最後更新：2026-04-13