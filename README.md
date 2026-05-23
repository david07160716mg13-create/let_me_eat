# 🎰 餐廳轉轉樂

> 選擇縣市與行政區，即時抓取真實餐廳資料，用**轉盤**幫你決定今天吃什麼！  
> 純前端單頁應用，無需安裝，無需帳號，開啟即用。

🌐 **線上版本**：[siseat.com](https://pages.github.ibm.com/yuchen-chang/siseat.com/restaurant_roulette.html)

---

## ✨ 功能特色

| 功能 | 說明 |
|------|------|
| 📍 **全台縣市支援** | 涵蓋台灣本島 22 個縣市，所有行政區皆可選擇 |
| 🔍 **即時餐廳搜尋** | 透過 OpenStreetMap Overpass API 抓取真實餐廳資料 |
| 🎡 **動態轉盤** | Canvas 繪製的霓虹風格轉盤，最多顯示 20 家餐廳 |
| ⚡ **本地快取** | 搜尋結果快取 24 小時，重複查詢不需重新呼叫 API |
| 🔄 **自動重試** | API 忙碌時自動重試最多 6 次，穩定不中斷 |
| 🗺️ **Google 地圖整合** | 轉盤決定結果後，一鍵跳轉 Google 地圖搜尋 |
| 📱 **RWD 響應式設計** | 手機、平板、電腦皆可正常使用 |

---

## 🚀 使用方式

### 線上版（推薦）

直接點擊開啟，不需任何安裝：  
👉 [https://pages.github.ibm.com/yuchen-chang/siseat.com/restaurant_roulette.html](https://pages.github.ibm.com/yuchen-chang/siseat.com/restaurant_roulette.html)

### 本地執行

1. 下載或 clone 此 Repo：
   ```bash
   git clone https://github.com/david07160716mg13-create/let_me_eat.git
   cd let_me_eat
   ```

2. 直接用瀏覽器開啟 `restaurant_roulette.html`（雙擊即可）

> ✅ 無需安裝任何套件或執行伺服器，直接開啟 HTML 檔案即可使用。

---

## 🕹️ 操作步驟

1. **選擇縣市**：從下拉選單選擇目標縣市（例：臺北市）
2. **選擇行政區**：選擇對應的行政區（例：大安區）
3. **點擊「🔍 搜尋餐廳」**：系統自動抓取該區的餐廳資料
4. **點擊「🎰 開始轉！」**：轉盤旋轉後隨機決定今天的餐廳
5. **查看結果**：結果彈窗出現，可選擇「再轉一次」或「Google 地圖搜尋」

---

## 🏗️ 技術架構

```
restaurant_roulette.html   ← 單一 HTML 檔案，包含所有邏輯與樣式
```

| 技術 | 用途 |
|------|------|
| 原生 HTML / CSS / JS | 無框架，零依賴 |
| Canvas API | 繪製旋轉轉盤與霓虹色塊 |
| [Overpass API](https://overpass-api.de/) | 查詢 OpenStreetMap 餐廳資料 |
| localStorage | 快取搜尋結果（TTL 24 小時） |
| Google Fonts (Noto Sans TC + Orbitron) | 字型 |

---

## 🗺️ 支援縣市

台灣本島全部 22 縣市，包含：

臺北市、新北市、桃園市、臺中市、臺南市、高雄市、基隆市、新竹市、嘉義市、新竹縣、苗栗縣、彰化縣、南投縣、雲林縣、嘉義縣、屏東縣、宜蘭縣、花蓮縣、臺東縣、澎湖縣、金門縣、連江縣

---

## 📄 授權

MIT License — 自由使用、修改與散布。
