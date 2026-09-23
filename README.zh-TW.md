# Fate Ziwei (命運紫微) · 確定性高精度排盤引擎與多語言平台

<p align="center">
  <a href="README.md"><strong>English</strong></a> •
  <a href="README.zh-CN.md"><strong>简体中文</strong></a> •
  <a href="README.zh-TW.md"><strong>繁體中文</strong></a> •
  <a href="README.ja.md"><strong>日本語</strong></a>
</p>

<p align="center">
  <a href="https://fateziwei.com"><img src="https://img.shields.io/badge/官網直達-fateziwei.com-purple" alt="官網直達"></a>
  <a href="https://fateziwei.com/tw"><img src="https://img.shields.io/badge/支援語言-10大全球語系-blue" alt="支援語言"></a>
  <a href="https://fateziwei.com/zh/famous"><img src="https://img.shields.io/badge/計算精度-560%2F560%20全用例驗證-brightgreen" alt="精度測試"></a>
  <a href="https://fateziwei.com/zh/famous"><img src="https://img.shields.io/badge/歷史名人庫-11%2C669%20張星盤-gold" alt="名人庫"></a>
  <a href="https://fateziwei.com/zh/book/sample"><img src="https://img.shields.io/badge/匯出支援-雙遍法向量PDF-red" alt="PDF匯出"></a>
</p>

---

## 🌟 平台總覽 (Overview)

**Fate Ziwei (命運紫微)** 是一套融合嚴謹確定性天文曆法計算與十語系原生 AI 深度命書撰寫的現代化東方術數平台。平台將正統紫微斗數、八字四柱、易經周易卦象、奇門遁甲與現代前端工程學、天文星曆演算法及大語言模型深度結合，打造學術級、高可靠的命理分析服務。

- 🌐 **平台官網**: [https://fateziwei.com](https://fateziwei.com)
- 🇭🇰 **繁體中文主入口 (港澳台/海外)**: [https://fateziwei.com/tw](https://fateziwei.com/tw)
- 🇨🇳 **簡體中文入口**: [https://fateziwei.com/zh](https://fateziwei.com/zh)
- 🌐 **Global English**: [https://fateziwei.com/en](https://fateziwei.com/en)
- 🇯🇵 **日本語サイト**: [https://fateziwei.com/ja](https://fateziwei.com/ja)

---

## ⚡ 核心自研技術與工程特性

### 1. 確定性天文曆法與高精度排盤引擎
- **560/560 欄位級全用例驗證**：涵蓋南北半球推演、閏月換算、早子時與夜子時交界等極端邊界條件，與權威古籍標準案例 100% 吻合。
- **經緯度真太陽時校準 (True Solar Time)**：內建全球城市經緯度地理編碼庫，毫秒級計算均時差 (Equation of Time)，徹底消除平太陽時偏差。
- **流派與規則自由定製**：全面支援三合派、四化派排盤邏輯，相容早子時/夜子時劃分、閏月前/後半月或作下月起盤等多流派演算法切換。

### 2. 十語系原生 AI 命書撰寫與雙遍法向量 PDF 管線
- **原生語系深度生成**：杜絕生硬的機器翻譯，基於各語系本土術數文化與修辭習慣，原生生成 10 大語言的高品質命書解讀。
- **30 頁五卷人生說明書**：涵蓋【命運基石】、【五大維度深度解析】、【大限十年圖卷】、【流年逐年運勢】與【古籍文獻對照考訂】。
- **雙遍法 (Two-Pass) 向量 PDF 渲染管線**：自研 `jspdf 4 + pdf-lib` 混合渲染引擎，實現全出血零邊距藝術封面、中英日向量字型全子集嵌入與印刷級向量線條直出。

### 3. 東方術數大一統產品矩陣
- **紫微斗數 (Ziwei Dou Shu)**：本命盤、大限十年盤、流年運勢盤、流月、流日、流時全層級星盤與動態飛星。
- **八字四柱 (Four Pillars / Bazi)**：節氣精準交接、十神透藏分析、地支藏干、五行旺衰強弱量化。
- **雙人合盤與八字合婚 (Synastry)**：多維度命宮宮位共振、夫妻宮星曜互涉、能量互補與合婚評分模型。
- **周易問卦與占卜六法**：梅花易數、六爻納甲、奇門遁甲排盤、小六壬神算、觀音靈籤百籤、河洛理數卦象。
- **高階命理工具箱**：生辰時辰反推、九宮飛星風水方位佈局、命運雙生子（同八字不同命運）對照分析。

### 4. 11,669 歷史人物大數據命盤與 13 部古籍文庫
- **權威歷史人物庫**：收錄 11,669 位歷史人物生辰數據，包含 55 篇嚴格對照《二十四史》本傳考訂的精修命盤。
- **62 種大格局大數據分佈**：君臣慶會、石中隱玉、極向離明、機月同梁等經典格局的大數據頻次與星象特徵統計。
- **2,366 段古籍古文溯源**：深度結構化索引《紫微斗數全書》、《太微賦》、《形性賦》、《骨髓賦》等 13 部元典。

### 5. 純 Canvas 2D 離屏超清海報生成引擎
- **2004×2985 @3x Retina 級解析度**：生成可直接印刷的高畫質藝術星盤海報。
- **真盤幾何連線與印章渲染**：動態繪製三方四正對角連線、四化飛星向量軌跡與客製化書法印鑑。

---

## 🗂️ 全功能產品矩陣

| 核心模組 | 主要功能 | 演算法與技術亮點 |
| :--- | :--- | :--- |
| **紫微本命與運勢排盤** | 本命/大限/流年/流月/流日/流時 | 12 宮位精細推演、三方四正格局連線、真太陽時經緯度校準 |
| **八字與合婚引擎** | 八字排盤、五行喜忌、雙人合盤 | 節氣納音推算、天干地支藏干、十神格局評分與八字互補度 |
| **AI 原生人生說明書** | 30 頁五卷深度命書 | 10 語系原生提示詞工程、雙遍法向量 PDF 匯出 |
| **占卜與問卦六法** | 梅花易數 / 六爻 / 奇門 / 小六壬 / 觀音籤 | 經典演算法復刻、動爻變卦演算、吉凶斷語深度解析 |
| **歷史人物大數據** | 11,669 張歷史名人盤、62 種格局 | 大數據格局分佈檢索、2,366 段經典古籍文獻溯源 |
| **特色工具矩陣** | 時辰反推、風水九宮、命運雙生子 | 盲人推命邏輯建模、九宮飛星方位動態演算 |
| **每日老黃曆** | 今日宜忌、每日一籤 | 傳統神煞宜忌、彭祖百忌、每日靈感籤卡 |

---

## 🌐 多語言線上入口直達 (Global Portals)

- 🇭🇰 **繁體中文 (港澳台/海外)**: [https://fateziwei.com/tw](https://fateziwei.com/tw)
- 🇨🇳 **簡體中文 (大陸)**: [https://fateziwei.com/zh](https://fateziwei.com/zh)
- 🌐 **English (Global)**: [https://fateziwei.com/en](https://fateziwei.com/en)
- 🇯🇵 **日本語**: [https://fateziwei.com/ja](https://fateziwei.com/ja)
- 🇰🇷 **한국어**: [https://fateziwei.com/ko](https://fateziwei.com/ko)
- 🇻🇳 **Tiếng Việt**: [https://fateziwei.com/vi](https://fateziwei.com/vi)
- 🇫🇷 **Français**: [https://fateziwei.com/fr](https://fateziwei.com/fr)
- 🇪🇸 **Español**: [https://fateziwei.com/es](https://fateziwei.com/es)
- 🇩🇪 **Deutsch**: [https://fateziwei.com/de](https://fateziwei.com/de)
- 🇷🇺 **Русский**: [https://fateziwei.com/ru](https://fateziwei.com/ru)

---

## 📖 核心落地頁與樣張體驗 (Features & Samples)

- **2027 流年運勢專題頁**: [https://fateziwei.com/zh/liunian-2027](https://fateziwei.com/zh/liunian-2027)
- **歷史名人命盤庫 (Famous Charts)**: [https://fateziwei.com/zh/famous](https://fateziwei.com/zh/famous)
- **命書樣張線上預覽 (Sample Book)**: [https://fateziwei.com/zh/book/sample](https://fateziwei.com/zh/book/sample)
- **雙人合婚測試 (Compatibility)**: [https://fateziwei.com/zh/hehun](https://fateziwei.com/zh/hehun)
- **紫微斗數文庫與問答**: [https://fateziwei.com/zh/wiki](https://fateziwei.com/zh/wiki) | [https://fateziwei.com/zh/qa](https://fateziwei.com/zh/qa)

---

## ⚖️ 智慧財產權與免責聲明

本專案計算架構與技術文件面向公開學術研討與技術展示。如需商業合作或演算法介接，請訪問 [fateziwei.com](https://fateziwei.com)。
