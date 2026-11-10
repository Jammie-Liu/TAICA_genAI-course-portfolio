# 03-rag-mcp-tutor｜MCP 課程助教

## 作業要求
- 選一份有興趣的文件當知識來源，打造自己的 RAG 對話機器人。
- 參考老師的示範資料集格式（每份 TXT 有標題、來源網址、教學摘要、測試問題，加上 sources.csv、問題集.csv）。

## 我想做什麼
- 用 Anthropic Academy「Introduction to Model Context Protocol」課程做 MCP 教學機器人。

## 動機（作者自己的話）
- 最近在 Anthropic 課程網站上學 MCP，概念全新、課程又是英文，想有個助教可以回答各種問題、幫助學習，所以把所有課程內容做成 RAG。

## 做法與技術
- 11 個有文字內容的單元改寫成中文摘要，加 1 份名詞對照表，共 12 份。
- 問題集 21 題，其中 3 題是知識庫外問題（講師名字、TypeScript 寫法、API 價格）。
- Colab：切塊、embeddings、FAISS，匯出 vector_db.zip；從 Google Drive 自動載入。
- System prompt「MCP 助教」：回答規則、教學方式、限制與提醒，共 13 條。

## 素材與連結
- Colab 筆記本：https://colab.research.google.com/drive/1wWkhHjGnnxIDvWxncjBJbro5c_tbD9Ez?usp=sharing

## 決定紀錄
- 課程影片、滿意度問卷、期末測驗不收錄。
- 資料集是課程內容改寫，不公開散布，所以作品頁不附資料集下載。

## 待確認
- （無）
