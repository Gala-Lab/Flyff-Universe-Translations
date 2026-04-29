---
name: cht-typography-pr-review
description: "Apply CJK typography and mixed-text spacing normalization for game UI translations."
applyTo: 
  - "Traditional_Chinese/**"
---

# Chinese Typography Rules for Game UI

## 🎯 Principles

This guideline applies **CJK Typography** and **Mixed Text Spacing** to ensure:

- High readability for game UI
- Consistent Chinese–English mixed layout
- Clean and professional visual presentation

---

## 🧩 Rules

### 1. Fullwidth → Halfwidth Punctuation Normalization

Convert fullwidth punctuation to halfwidth:

- `（ ） → ( )`

---

### 2. CJK Mixed Text Spacing (Core Rule)

Insert spaces between:

- Chinese characters and English words
- Chinese characters and numbers
- Chinese characters and symbols (excluding punctuation)

**Examples**
- `技能 Level 5`
- `攻擊 +10%`
- `需要 Gold 100`

---

### 3. Parentheses and Brackets Spacing

Apply consistent spacing:

- Insert a space before `(` when preceded by text
- Insert a space after `)` when followed by text
- Insert a space before `[` when preceded by Chinese text
- Insert a space after `]` when followed by text

Do NOT insert spaces when adjacent to punctuation.

---

### 4. Numbers and Units

Ensure readability:

- `100 傷害`
- `5 秒`
- `10 HP`
- `5 sec`

**Exception**
- No space before `%` → `+10%`

---

### 5. Line Start Normalization

Remove unintended leading spaces before brackets:

- ` (text)` → `(text)`
- ` [Buff] text` → `[Buff] text`

---

## ⚠️ Exceptions

Do NOT modify:

- punctuation adjacency, for example `).` and `],`
- already correctly formatted text
- structured data (e.g., CSV field alignment)

---

## 🧠 Priority Rule

When rules conflict:

> Prioritize **UI readability over strict grammar**

---

## ✔ Review Checklist

- fullwidth punctuation normalized
- correct CJK–Latin spacing
- proper parentheses and bracket spacing
- numbers and units are readable
- no unintended leading spaces
- overall UI readability is natural

---

## 🤖 Copilot Instruction Summary

Apply **CJK typography and mixed-text spacing normalization**:

- normalize fullwidth punctuation
- insert spacing between Chinese and Latin text
- normalize parentheses and bracket spacing
- preserve punctuation rules
- optimize for UI readability

---

Last updated: 2026-04-13
