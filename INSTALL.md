# 安裝｜客服回覆草稿（免費試用）· 約 30 秒

完整付費包（P1 US$5／P2 US$12）→ https://portaly.cc/TuringatHogwarts

## A. Claude.ai（ZIP 上傳）

1. 下載本 repo 的 [`cs-reply-free-trial.zip`](./cs-reply-free-trial.zip)。
2. Claude.ai → **Customize** → **Skills** → **＋／Upload**。
3. 確認 ZIP 根下是資料夾 `cs-reply-trial/`（內含 `SKILL.md`），不要把 `SKILL.md` 直接丟在 ZIP 根。
4. 上傳後**啟用**該 skill；用一段客訴原文測是否被叫出。

> 注意：claude.ai 上傳＝個人私有，不會自動同步 Claude Code／API。`description` 宜 ≤ 200 字（本試用已符合）。

## B. Cursor（資料夾／Remote Rule）

1. Clone 本 repo，或只下載 ZIP 解壓。
2. 將 `free/cs-reply-trial/`（或解壓後的 `cs-reply-trial/`）複製到：
   - 專案：`.cursor/skills/cs-reply-trial/`
   - 或全域：`~/.cursor/skills/cs-reply-trial/`
3. 也可：Customize → Rules → **Remote Rule (GitHub)** → 填 `Evan1206/zh-skills-free`。
4. 新開對話，貼客訴原文測試觸發。

## C. 可選：`npx skills`

若你的環境已有官方／社群 `skills` CLI：

```bash
npx skills add Evan1206/zh-skills-free --agent cursor
```

若指令不存在或失敗，改用 **B** 手動複製即可——不影響試用。

## 限制與升級

- 試用範圍：見 `free/cs-reply-trial/LIMITS.md`。
- 需要完整風險升級／多範例／渠道約束，或會員成長完整包 → [Portaly](https://portaly.cc/TuringatHogwarts)。
