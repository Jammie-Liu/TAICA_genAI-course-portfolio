# Jammie 的生成式 AI 作品集

TAICA_生成式AI：文字與圖像生成的原理與實務 課程的作業作品集網站。每份作業一頁，說明用了什麼技術、為什麼這樣設計、怎麼運作。

## 收錄作品

| 編號 | 作品 | 技術 |
| --- | --- | --- |
| 01 | 互動網頁 × Live Coding｜偶像風格音樂實驗室 | Strudel、Web Audio |
| 02 | System Prompt｜大叔三人組諮詢室 | System Prompt、Few-shot |
| 03 | RAG｜MCP 課程助教 | RAG、Embeddings、FAISS |
| 04 | Planning Agent｜先規劃再回覆的諮詢室 | Planning、兩階段生成、Gradio |

## 專案結構

```
├── AGENTS.md      AI 的工作規則（新增作品前必讀）
├── index.html     首頁
├── ideas/         發想與原始素材
├── notes/         定稿文字（網頁內容來源）
├── assets/        CSS 與封面插圖
├── templates/     作品頁樣板
└── works/         作品頁
```

內容依 **ideas → notes → assets → works → index** 的順序產生，細節見 [AGENTS.md](AGENTS.md)。

## 如何新增作品

對 AI 說：

> 請依 AGENTS.md 新增作品：〈主題〉，素材如下……

AI 會依 AGENTS.md 第 6 節的流程，依序建立 `ideas/`、`notes/`、封面插圖、作品頁，並更新首頁卡片與上下頁連結；缺少的資訊（例如動機、測試結果）會先詢問作者，不會自行編造。

## 部署到 GitHub Pages

1. 在 GitHub 建立一個新的 public repository（例如 `genai-portfolio`）。
2. 把本資料夾的所有檔案上傳到 repository 根目錄。
3. 進入 repository 的 **Settings → Pages**，Source 選 **Deploy from a branch**，Branch 選 `main`、資料夾選 `/ (root)`，按 Save。
4. 等一兩分鐘，網站會出現在 `https://<你的帳號>.github.io/genai-portfolio/`。

全站都是靜態檔案，不需要安裝或建置。本機預覽時直接用瀏覽器打開 `index.html` 即可。
