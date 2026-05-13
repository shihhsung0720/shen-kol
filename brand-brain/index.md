# 品牌大腦 — 載入規則 SSoT

## 載入清單（AI 進入任務時讀這些）

| 場景 | 必讀 | 條件讀 | 不讀 |
|---|---|---|---|
| 寫 IG Reels 腳本 | `brand.md` [0][1][3][4] + `products.md` 對應產品 | `cases.md`（要舉例時） | `brand.md` 其他節 |
| 寫 KOL 邀約話術 | `brand.md` [0][1][3] | `cases.md`（KOL 過往合作） | `products.md` 細節 |
| 回答「我們做過 X 嗎」 | `cases.md` | — | — |

## 寫入分工

| 檔 | 誰寫 |
|---|---|
| `brand.md` | Kai 手填、AI 不可主動修改 |
| `products.md` | Kai 手填、AI 可在 Kai 口述後協助結構化 |
| `cases.md` | Kai 手填、AI 可在 Kai 提供連結後協助抓出關鍵字 |
| `brand-summary.md` | AI 從 `brand.md` 提煉、Kai 審核後鎖定 |
| `index.md` | Kai 寫、新增資料層時更新 |

## 更新觸發

- 每個檔頂端有 `last_updated: YYYY-MM-DD`
- 超過 **90 天**沒更新 → AI 在對話開頭提醒
- `brand.md [4] 法規邊界` 超過 **180 天**沒更新 → AI 拒絕生稿（法規會變）

## 拒絕生稿條件（硬規則）

`brand.md` 缺以下任一節、AI 不可生 Reels 或邀約話術：
- [0] 基本資料
- [1] 品牌哲學
- [3] 內容調性

---

## Stage Roadmap

**Stage 1（本週、目標：AI 寫得出第一支像樣的 Reels）**
- [ ] `brand.md [0]` 基本資料
- [ ] `brand.md [1]` 品牌哲學
- [ ] `brand.md [3]` 內容調性（voice + DO/DON'T 各 3 條）
- [ ] `products.md` — 3:7 雙層精華
- [ ] `brand.md [4]` 法規邊界

**Stage 2（下週、目標：AI 挑得到舊素材）**
- [ ] `cases.md` A 區 — 撈 10 支 IG Reels 表現好的、連結 + 一行說明
- [ ] `brand.md [2]` 受眾畫像（拆 2 個 persona）

**Stage 3（第 3-4 週、目標：AI 講得出創辦人故事）**
- [ ] `brand.md [5]` 創辦故事
- [ ] `cases.md` B 區 — 補 5-10 筆 KOL 合作案例

**Stage 4（之後再說）**
- [ ] `brand.md [6]` 季節節點
- [ ] `brand-summary.md` 提煉
- [ ] SessionStart hook 自動注入 summary
