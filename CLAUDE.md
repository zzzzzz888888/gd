# 作品集網站 — 平面設計版（gd）

鄭芯繻 Jheng Sin-Ru 的個人作品集，**投遞平面設計／視覺設計職缺用**。

- 網址：https://zzzzzz888888.github.io/gd/
- Repo：https://github.com/zzzzzz888888/gd（main 分支，GitHub Pages 直接發佈）
- 由 UIUX 版（`C:\Users\user\Desktop\pf`，https://zzzzzz888888.github.io/pf/）於 2026-11-07 複製而來。兩站各自獨立；使用者明講「兩個網站都要改」才同步修改兩邊。

## 定位
以平面設計（VI、社群／廣告圖、插畫、文字設計、編排印刷）為主軸。首頁介紹、技能標籤與作品排序都應以平面設計為優先。
UIUX 作品**保留但放在最後**（使用者 2026-11-07 決定）：導覽列順序為 關於 → 平面設計 → 動態圖像 → UIUX 設計；首頁作品分類同順序，疊卡以平面設計在最前。

## 結構
- `index.html` 首頁：關於我（照片、技能標籤）、工作經歷、自我介紹、作品分類（hover 換圖）。Hero 輪播目前隱藏。
- `graphic.html` 平面設計 masonry 圖牆，每張 `.shot` 用 `data-cat / data-title / data-client / data-images` 定義，點擊開 lightbox；加 `hidden` 屬性可暫時隱藏不刪除
- `motion.html` 動態圖像（影片在 `videos/`）
- `uiux.html`、`project-*.html` UIUX 專案（沿用自 UIUX 版）
- `assets/styles.css`、`assets/main.js` 全站共用（Lenis + GSAP）。改了 CSS/JS 要更新各頁的 `?v=` 版本號避免快取。
- 圖片在 `images/`

## 工作習慣
- 每次修改一個主題就 commit，訊息用「頁面: 改了什麼」格式，然後 push 到 main。
- 分頁標題格式：`頁名 — Jheng Sin-Ru`。
