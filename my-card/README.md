# 🌟 3D 鐳射卡牌網頁生成流程：從訪談到一鍵發布

> **作業題目**：本日作業：提供Prompt: 3D 鐳射卡牌網頁生成流程-從訪談到一鍵發布  
> **技術架構**：零依賴單一檔案 `index.html`（HTML5 + CSS3 + 原生 JavaScript + html2canvas）  
> **核心亮點**：動態 3D 視差傾角、高保真雷射全息箔膜、全卡面即時文字編修、180° 正反翻牌、300DPI 高畫質 PNG 匯出、GitHub Pages 零建置上線。

---

## 📂 專案檔案清單

- [`index.html`](file:///c:/Users/User/Desktop/my-card/index.html)：完整單一檔案網頁，雙擊即可在任何瀏覽器直接開啟與操作。
- [`prompt.md`](file:///c:/Users/User/Desktop/my-card/prompt.md)：作業所需之 **完整 3 階段 System Prompt**（可直接複製提交作業或給 AI 使用）。
- [`README.md`](file:///c:/Users/User/Desktop/my-card/README.md)：專案說明文件與 GitHub Pages 快速部署教學。

---

## 🚀 作業核心三階段流程 (Interactive Generator Workflow)

### 階段一：引導 ── 啟動卡牌鑄造訪談 (Interview)
1. **核心屬性與數值**：角色名稱、HP 能階、標籤類別、主題色系（科技金、創發紅、蒼穹藍、幽冥紫、翡翠綠）。
2. **視覺立繪與箔膜**：支援本地自訂上傳立繪圖片，動態切換宇宙彩虹、極光全息、黑金浮雕、銀翼幻影、星鑽炫彩等 5 種箔膜。
3. **技能與戰鬥機制**：規劃【特性】Trait、【普通招式】威力與消耗、【奧義絕招】大絕描述與破壞力。
4. **對抗與印記設定**：配置弱點、抗性、撤退能量、創作者署名認證（NO. 001/999 ✦ ILLUS. CHUCK）。

### 階段二：生成 ── 系統實作與規範 (Implementation)
1. **流體響應式佈局**：桌面端左右雙欄並排、行動端垂直堆疊，精準維持 TCG 63:88 黃金比例。
2. **3D 視差與雷射系統**：
   - 游標動態傾角（±14°）與即時鏡面高光（Specular Glare）
   - 行動裝置陀螺儀（DeviceOrientation 重力感應）
   - 多層次彩虹光斑、繞射折射光澤（`mix-blend-mode: color-dodge`）
3. **零依賴單一檔案**：純原生 HTML/CSS/JS，開箱即用，免安裝 npm/Node 套件。
4. **即時編輯與互動**：
   - 全卡面文字支援 `contenteditable="true"` 即時修改
   - 支援上傳立繪即時更換
   - 180° 3D 正反平滑翻牌
   - 內建 4 種角色預設範本（查研觀攝、創發烈焰、幽冥法師、蒼穹駭客）一鍵切換

### 階段三：發布 ── 成果輸出與部署 (Export & Deploy)
1. **一鍵高畫質匯出**：整合 html2canvas，以 3x 超取樣比例匯出 300DPI 印刷級透明背景 PNG 圖檔。
2. **GitHub Pages 零障礙發布**：無須任何 build 步驟，推送即可上線。
3. **專屬傳奇展示**：打造獨一無二的個人 3D 鐳射卡牌數位藏品網頁。

---

## 🌐 GitHub Pages 零障礙 1 分鐘發布步驟

1. 登入 [GitHub](https://github.com/) 並點擊 **New repository**。
2. 輸入儲存庫名稱（例如 `my-tcg-card`），設為 **Public**，點擊 **Create repository**。
3. 點擊 **Upload files**，將本專案的 `index.html` 拖曳上傳至根目錄並完成 Commit。
4. 點擊儲存庫上方的 **Settings** ➔ 側邊欄點選 **Pages**。
5. 在 **Build and deployment** 下方的 **Branch** 選擇 `main`（或 `master`），資料夾保持 `/ (root)`，點擊 **Save**。
6. 等候約 30 秒至 1 分鐘重新整理，即可在上方看見發布網址（例如：`https://<你的帳號>.github.io/my-tcg-card/`）！
