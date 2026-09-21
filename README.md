# zh-skills-free｜繁中 Skill 免費試用

> **完整付費包（立刻購買）→ [Portaly](https://portaly.cc/TuringatHogwarts)**  
> Public repo：https://github.com/Evan1206/zh-skills-free  
> 語言：繁體中文（zh-TW）｜本週實驗市場：台灣／繁中

---

## 免費 vs 付費（3 行）

| | 內容 | 哪裡拿 |
|--|------|--------|
| **免費試用** | 客服回覆草稿**精簡版**（單次可跑：結構＋語氣＋1 則範例） | 本 repo |
| **付費 P1** | 客服回覆草稿**完整包**（風險升級／多範例／渠道約束）｜**US$5** | [Portaly](https://portaly.cc/TuringatHogwarts) |
| **付費 P2** | 會員成長營運**完整包**（診斷＋本週 3 實驗）｜**US$12** | [Portaly](https://portaly.cc/TuringatHogwarts) |

本 repo **不含**任何付費 ZIP、完整 `cs-reply`／`member-growth`，或其他完整 skills。

---

## 安裝 30 秒

詳見 [`INSTALL.md`](./INSTALL.md)。

1. **Claude.ai**：下載 [`cs-reply-free-trial.zip`](./cs-reply-free-trial.zip) → Customize → Skills → Upload → 啟用（ZIP 內須為資料夾 `cs-reply-trial/`＋`SKILL.md`；`description` ≤ 200 字）。
2. **Cursor**：把 `free/cs-reply-trial/` 複製到專案 `.cursor/skills/`（或 `~/.cursor/skills/`）；也可 Customize → Rules → **Remote Rule (GitHub)** 指向本 repo。
3. **可選一鍵**：`npx skills add Evan1206/zh-skills-free --agent cursor`（若你的環境支援 `skills` CLI；否則用上方手動路徑）。

裝好後丟一段真實客訴原文，應會依試用 skill 產出可貼草稿。完整版仍請走 Portaly。

---

## 目錄

```
.
├── free/cs-reply-trial/     # 可直接安裝的試用 skill
│   ├── SKILL.md
│   ├── INSTALL.md
│   └── LIMITS.md
├── cs-reply-free-trial.zip  # 給 Claude.ai／不熟 git 的人
├── releases/cs-reply-free-trial.zip
├── INSTALL.md
├── README.md
└── .gitignore
```

---

## Topics（建議）

`skill` · `claude` · `cursor` · `traditional-chinese`

---

## 免責

- 產出為**草稿**，請人工審核後再對外寄送；不構成法律、客服或營運承諾。
- 試用限制見 `free/cs-reply-trial/LIMITS.md`。
- 付費成交只在站外 Portaly；本公開 repo 僅免費試用與導流。
