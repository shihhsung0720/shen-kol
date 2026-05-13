# CLAUDE.local.md — Kai 個人 / 此 repo 專屬

## 是誰、做什麼

- Kai：台灣植萃保養品牌創辦人（個人 IP + 品牌一體）
- 此 repo 服務兩件事：
  1. **KOL 邀約管線**：找人 → 評估 → 邀約 → 紀錄（一個月 5-10 位合作）
  2. **品牌大腦**：給 AI 寫 IG Reels（30-60 秒）/ 邀約話術前讀

## 偏好

- 語言：繁體中文
- 語氣：直白、短句、不要顧問腔
- 長度：能一句不寫兩句、能列點不寫段落
- 我問「有沒有」「有哪些」「最近」這類問題、永遠以檔案為準、不要憑印象答

## 私密設定（只寫變數名稱、不寫真值）

- `IG_SESSION_COOKIE`（之後做爬蟲才會用）
- `OPENAI_API_KEY` / `ANTHROPIC_API_KEY`（之後做話術生成）
- 真實值放 `.env`（已 gitignore）或 GitHub Secrets

## 與 CLAUDE.md 的關係

CLAUDE.md = 任何接手者都該遵守的通用規則、可同步覆蓋更新。
CLAUDE.local.md = 只有我這個 repo 才適用的個人化、不會被覆蓋。
