# Fate Ziwei (命运紫微) · 确定性高精度排盘引擎与多语言平台

<p align="center">
  <a href="README.md"><strong>English</strong></a> •
  <a href="README.zh-CN.md"><strong>简体中文</strong></a> •
  <a href="README.zh-TW.md"><strong>繁體中文</strong></a> •
  <a href="README.ja.md"><strong>日本語</strong></a>
</p>

<p align="center">
  <a href="https://fateziwei.com"><img src="https://img.shields.io/badge/官网直达-fateziwei.com-purple" alt="官网直达"></a>
  <a href="https://fateziwei.com/zh"><img src="https://img.shields.io/badge/支持语言-10大全球语种-blue" alt="支持语言"></a>
  <a href="https://fateziwei.com/zh/famous"><img src="https://img.shields.io/badge/计算精度-560%2F560%20全用例验证-brightgreen" alt="精度测试"></a>
  <a href="https://fateziwei.com/zh/famous"><img src="https://img.shields.io/badge/历史名人库-11%2C669%20张命盘-gold" alt="名人库"></a>
  <a href="https://fateziwei.com/zh/book/sample"><img src="https://img.shields.io/badge/导出支持-双遍法矢量PDF-red" alt="PDF导出"></a>
</p>

---

## 🌟 平台总览 (Overview)

**Fate Ziwei (命运紫微)** 是一套融合严谨确定性天文历法计算与十语种原生 AI 深度命书写作的现代化东方术数平台。平台将传统紫微斗数、八字四柱、易经周易卦象、奇门遁甲与现代前端工程学、天文星历算法及大语言模型相结合，打造学术级、高可靠的命理分析服务。

- 🌐 **平台官网**: [https://fateziwei.com](https://fateziwei.com)
- 🇨🇳 **简体中文主入口**: [https://fateziwei.com/zh](https://fateziwei.com/zh)
- 🇭🇰 **港澳台繁体中文**: [https://fateziwei.com/tw](https://fateziwei.com/tw)
- 🌐 **Global English**: [https://fateziwei.com/en](https://fateziwei.com/en)
- 🇯🇵 **日本語サイト**: [https://fateziwei.com/ja](https://fateziwei.com/ja)

---

## ⚡ 核心自研技术与工程特性

### 1. 确定性天文历法与高精度排盘引擎
- **560/560 字段级全用例验证**：覆盖南北半球推演、闰月换算、早晚子时交界等极端边界条件，与权威古籍标准案例 100% 吻合。
- **经纬度真太阳时校准 (True Solar Time)**：内置全球城市经纬度地理编码库，毫秒级计算均时差 (Equation of Time)，彻底消除平太阳时误差。
- **流派与规则自由定制**：全面支持三合派、四化派排盘逻辑，兼容早子时/晚子时切分、闰月前/后半月或作下月起盘等多流派算法切换。

### 2. 十语种原生 AI 命书写作与双遍法矢量 PDF 管线
- **原生语种深度生成**：杜绝呆板的机翻转译，基于各语种本土术数文化与修辞习惯，原生生成 10 大语言的高质量命书解读。
- **30 页五卷人生说明书**：涵盖【命运基石】、【五大维度深度解析】、【大限十年图卷】、【流年逐年运势】与【古籍文献对照考订】。
- **双遍法 (Two-Pass) 矢量 PDF 渲染管线**：自研 `jspdf 4 + pdf-lib` 混合渲染引擎，实现全出血零边距艺术封面、中英日矢量字体全子集嵌入与印刷级矢量线条直出。

### 3. 东方术数大一统产品矩阵
- **紫微斗数 (Ziwei Dou Shu)**：本命盘、大限十年盘、流年运势盘、流月、流日、流时全层级星盘与动态飞星。
- **八字四柱 (Four Pillars / Bazi)**：节气精准交接、十神透藏分析、地支藏干、五行旺衰强弱量化。
- **双人合盘与八字合婚 (Synastry)**：多维度命宫宫位共振、夫妻宫星曜互涉、能量互补与合婚评分模型。
- **周易问卦与占卜六法**：梅花易数、六爻纳甲、奇门遁甲排盘、小六壬神算、观音灵签百签、河洛理数卦象。
- **高阶命理工具箱**：生辰时辰反推、九宫飞星风水方位布局、命运双生子（同八字不同命运）对照分析。

### 4. 11,669 历史人物大数据命盘与 13 部古籍文库
- **权威历史人物库**：收录 11,669 位历史人物生辰数据，包含 55 篇严格对照《二十四史》本传考订的精修命盘。
- **62 种大格局大数据分布**：君臣庆会、石中隐玉、极向离明、机月同梁等经典格局的大数据频次与星象特征统计。
- **2,366 段古籍古文溯源**：深度结构化索引《紫微斗数全书》、《太微赋》、《形性赋》、《骨髓赋》等 13 部元典。

### 5. 纯 Canvas 2D 离屏超清海报生成引擎
- **2004×2985 @3x Retina 级分辨率**：生成可直接印刷的高清艺术星盘海报。
- **真盘几何连线与印章渲染**：动态绘制三方四正对角连线、四化飞星矢量轨迹与定制化书法印鉴。

---

## 🗂️ 全功能产品矩阵

| 核心模块 | 主要功能 | 算法与技术亮点 |
| :--- | :--- | :--- |
| **紫微本命与运势排盘** | 本命/大限/流年/流月/流日/流时 | 12 宫位精细推演、三方四正格局连线、真太阳时经纬度校准 |
| **八字与合婚引擎** | 八字排盘、五行喜忌、双人合盘 | 节气纳音推算、天干地支藏干、十神格局评分与八字互补度 |
| **AI 原生人生说明书** | 30 页五卷深度命书 | 10 语种原生提示词工程、双遍法矢量 PDF 导出 |
| **占卜与问卦六法** | 梅花易数 / 六爻 / 奇门 / 小六壬 / 观音签 | 经典算法复刻、动爻变卦演算、吉凶断语深度解析 |
| **历史人物大数据** | 11,669 张历史名人盘、62 种格局 | 大数据格局分布检索、2,366 段经典古籍文献溯源 |
| **特色工具矩阵** | 时辰反推、风水九宫、命运双生子 | 盲人推命逻辑建模、九宫飞星方位动态演算 |
| **每日老黄历** | 今日宜忌、每日一签 | 传统神煞宜忌、彭祖百忌、每日灵感签卡 |

---

## 🌐 多语言在线入口直达 (Global Portals)

- 🇨🇳 **简体中文 (大陆)**: [https://fateziwei.com/zh](https://fateziwei.com/zh)
- 🇭🇰 **繁體中文 (港澳台/海外)**: [https://fateziwei.com/tw](https://fateziwei.com/tw)
- 🌐 **English (Global)**: [https://fateziwei.com/en](https://fateziwei.com/en)
- 🇯🇵 **日本語**: [https://fateziwei.com/ja](https://fateziwei.com/ja)
- 🇰🇷 **한국어**: [https://fateziwei.com/ko](https://fateziwei.com/ko)
- 🇻🇳 **Tiếng Việt**: [https://fateziwei.com/vi](https://fateziwei.com/vi)
- 🇫🇷 **Français**: [https://fateziwei.com/fr](https://fateziwei.com/fr)
- 🇪🇸 **Español**: [https://fateziwei.com/es](https://fateziwei.com/es)
- 🇩🇪 **Deutsch**: [https://fateziwei.com/de](https://fateziwei.com/de)
- 🇷🇺 **Русский**: [https://fateziwei.com/ru](https://fateziwei.com/ru)

---

## 📖 核心落地页与样张体验 (Features & Samples)

- **2027 流年运势专题页**: [https://fateziwei.com/zh/liunian-2027](https://fateziwei.com/zh/liunian-2027)
- **历史名人命盘库 (Famous Charts)**: [https://fateziwei.com/zh/famous](https://fateziwei.com/zh/famous)
- **命书样张在线预览 (Sample Book)**: [https://fateziwei.com/zh/book/sample](https://fateziwei.com/zh/book/sample)
- **双人合婚测试 (Compatibility)**: [https://fateziwei.com/zh/hehun](https://fateziwei.com/zh/hehun)
- **紫微斗数文库与问答**: [https://fateziwei.com/zh/wiki](https://fateziwei.com/zh/wiki) | [https://fateziwei.com/zh/qa](https://fateziwei.com/zh/qa)

---

## ⚖️ 知识产权与免责声明

本项目计算架构与技术文档面向公开学术研讨与技术展示。如需商业合作或算法接入，请访问 [fateziwei.com](https://fateziwei.com)。
