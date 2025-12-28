# 🌈 最終任務 - 個人天氣 App 全端系統 (Level 2)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Google Fonts](https://img.shields.io/badge/Google%20Fonts-4285F4?style=flat&logo=googlefonts&logoColor=white)

## 專案概述

本專案是 **[六角學院 - 個人天氣 App 全端系統]** 挑戰的實作成果，旨在設計一個功能強大且視覺獨特的跨裝置氣象服務。

### 挑戰等級與目標

1. **Level 1：環境開發階段**
- 目標：** 專注於環境架設，包含申請氣象署 API 金鑰，並成功部署至 Zeabur 與 GitHub Pages，確保前後端資料連線正常運作。
2. **Level 2：個人風格改造**
- **目標：** 專注於前端風格改造，透過調整配色、字體、文案與圖示，將基礎版 App 轉變為具備個人化風格的「阿強全台氣象站」。

---

## 🛠️ 使用技術與工具

1. **前端 (Frontend):**
   - **核心技術：** HTML5, CSS3, JavaScript (ES6+)
   - **樣式與字體：** CSS Variables (實現動態配色), Klee One (個性化字型)
   - **特色功能：** Geolocation API (自動定位偵測)
   - **部署：**
2. **後端 (Backend):**
   - **核心技術：** Node.js, Express (API 框架)
   - **數據來源：** Axios (HTTP Client), CWA 交通部中央氣象署開放資料平臺
   - **部署：** Zeabur Cloud Service

---

## ✨ 網站頁面結構

本應用程式採用 **RWD (響應式網頁設計)** 的 **Mobile-First 流動佈局**，確保在所有裝置上（手機、平板、桌機）都能有最佳體驗。主要結構為垂直堆疊的區塊：

1.  **頂部狀態列 (`.status-bar`)**
    - 功能：顯示**縣市選擇下拉選單**、**今天日期**及**時間**。
    - 特色：兩個主要標籤皆為深色膠囊造型，保證白色文字對比度。
2.  **今日英雄卡 (`#heroCard`)**
    - 功能：顯示目前主要天氣狀態、溫度、和兩項快速建議（雨具/穿搭）。
    - 特色：天氣圖示具有獨特的 CSS **微動畫**。
3.  **稍後預報區 (`#futureForecasts`)**
    - 功能：顯示未來 36 小時的預報概況。
    - 特色：採用**水平滾動**的卡片列表，每張卡片的時段標籤（`.mini-time`）都獨立使用了動態配色與外框。

---

## 🚀 專案功能與優化亮點

* **動態配色主題：** 網頁背景由 JS 動態生成「上深下淺」的漸層色彩，並隨縣市主題切換。
* **增強動畫效果：** 所有天氣圖示（太陽、雲朵、雨、雷）設計了獨特的、加速的 CSS 動畫，使天氣狀態更具動感。
* **高對比度修正：** 統一所有膠囊標籤背景為深色，確保文字在任何主題色下都清晰可讀。
* **專業載入器：** 使用純 CSS 製作現代多層次旋轉環，優化載入體驗。

---

## 🔗 專案連結

| 項目 | 網址 |
| :--- | :--- |
| **前端 GitHub Repo** | https://github.com/kochang66/CwaWeather-frontend |
| **前端 GitHub Pages** | https://kochang66.github.io/CwaWeather-frontend/ |
| **後端 GitHub Repo** | https://github.com/kochang66/CwaWeather-backend |
| **後端 Zeabur API 網址** | https://archang-weather.zeabur.app/ |
