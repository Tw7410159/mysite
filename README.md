# Wen's Personal Portfolio & Design Workspace (`Wen.Design`)

✨ **具備建築與室內設計、視覺設計與 3D 建模實務經驗的個人專業作品集與互動網站。**

---

## 🌟 專案亮點 (Features)

* **🎨 現代簡約美學 (Bento Grid Layout)**：採用 Tailwind CSS 打造的響應式 Bento 網格排版，兼具俐落的建築線條感與直覺的資訊呈現。
* **🔍 SEO / GEO / AEO 深度優化**：完整內建 Schema.org (`Person` 與 `FAQPage`) 結構化資料、Open Graph 社交分享標籤與語意化標籤，全面適應現代搜尋引擎與生成式 AI 檢索。
* **🎵 沉浸式多媒體互動**：整合 HTML5 Web Audio API 背景音樂播放器，伴隨動態音頻波動特效（Wave Animation）。
* **☁️ Serverless 雲端表單串接**：聯絡諮詢表單無縫結合 **Google Apps Script (GAS)** Web App 後端，採用 `no-cors` 與非同步 POST 機制，安全地將訪客留言即時寫入 Google 試算表。

---

## 🛠️ 核心技能與技術堆疊 (Tech Stack)

### 專業領域 (Domain Expertise)

* **空間與建築**：建築與室內設計、空間動線規劃、美國紐約室內設計專案歷練、工業技術研究院 (ITRI) 專案經驗。
* **視覺與多媒體**：視覺提案、高質感 3D 建模與擬真情境圖渲染、平面設計。

### 數位工具庫 (Digital Tools)

* **2D / 3D 建模**：`AutoCAD`, `3D Max`, `SketchUp`
* **視覺與版型**：`Adobe Photoshop`, `InDesign`
* **前端與自動化**：`HTML5`, `Tailwind CSS`, `JavaScript`, `Google Apps Script`

---

## 📂 專案結構 (File Structure)

```text
├── index.html       # 單一檔案完整實作 (HTML + Tailwind CDN + JS 互動邏輯)
└── README.md        # 專案說明文件

```

---

## 🚀 快速預覽與部署 (Quick Start)

本專案採用極致輕量化的 **Single-File Architecture**，無需複雜的建置工具（Bundler）或終端機指令：

1. **直接預覽**：將 `index.html` 下載至本機，並以任何現代瀏覽器（Chrome, Safari, Edge）開啟即可。
2. **部署上線**：
* 可直接部署至 **GitHub Pages**、**Vercel** 或 **Netlify**，幾秒鐘內即可公開上線。
* **Google 試算表後端設定（選填）**：若需啟用聯絡表單的雲端寫入功能，只需將 `index.html` 中的 `GAS_WEB_APP_URL` 替換為你自己的 Google Apps Script 部署網址。
