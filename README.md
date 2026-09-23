# Fate Ziwei (命运紫微) · Deterministic Astrology Engine & Multilingual Platform

[![Live Platform](https://img.shields.io/badge/Platform-fateziwei.com-purple)](https://fateziwei.com)
[![Languages](https://img.shields.io/badge/Languages-10%20Locales-blue)](https://fateziwei.com/en)
[![Accuracy Test](https://img.shields.io/badge/Engine%20Precision-560%2F560%20Verified-brightgreen)](https://fateziwei.com/zh/famous)
[![Historical Charts](https://img.shields.io/badge/Historical%20Figures-11%2C669%20Charts-gold)](https://fateziwei.com/zh/famous)
[![PDF Pipeline](https://img.shields.io/badge/Export-True--Mirror%20Vector%20PDF-red)](https://fateziwei.com/book/sample)

**Fate Ziwei** is an advanced Eastern astrology platform combining high-precision deterministic calendar calculation with native multilingual AI-written life readings. It covers the full spectrum of traditional Chinese forecasting and research tools, serving global users in 10 languages across web and mobile.

**命运紫微 (FateZiwei)** 是融合高精度传统历法确定性计算与十语种原生 AI 命书推演的综合性东方术数平台。排盘是确定性数学与天文学计算，解读基于传世文献与现代大模型原生撰写。

🔗 **Official Portal (官网总入口)**: [https://fateziwei.com](https://fateziwei.com)  
📖 **English Portal**: [https://fateziwei.com/en](https://fateziwei.com/en) | 🇭🇰 **港台繁中**: [https://fateziwei.com/tw](https://fateziwei.com/tw) | 🇨🇳 **大陆简中**: [https://fateziwei.com/zh](https://fateziwei.com/zh)

---

## 🚀 核心自研技术底座 (Core Technical Highlights)

### 1. 确定性高精度历法引擎 (Deterministic Charting Engine)
- **560/560 字段级测试用例全量验证**：覆盖极端历法边界，排盘精度达到字段级 100% 零误差一致性。
- **地理经纬度真太阳时校正**：内置全国与全球城市经度数据库，自动补偿平太阳时与真太阳时时差，彻底解决跨时区与地方时生辰偏差。
- **复杂流派与历法配置**：
  - 支持农历闰月智能分界与平月对齐；
  - 早子时（00:00–01:00）与晚子时（23:00–24:00）归属流派切换；
  - 中州派、三合派等四化飞星、月干推算法与虚岁计算灵活配置。
- **4×4 宫格交互与六层运限穿透**：本命盘、大限（十年）、流年（一年）、流月、流日、流时六层盘面毫秒级联动，三方四正穿心连线与人生 K 线态势图直观呈现。

### 2. 十语种原生 AI 命书系统 (Native Multilingual AI Life Books)
- **原生母语生成（非机械翻译）**：支持 10 种语言原生输出（英语 EN、繁体中文 TW、简体中文 ZH、日语 JA、韩语 KO、越南语 VI、法语 FR、俄语 RU、西班牙语 ES、德语 DE）。日语严格遵循现代假名文体，韩语采用纯正谚文，欧美语系对标西方占星术语（Sun sign / 12 Houses / Planetary transits），避免机翻生硬感。
- **30 页五卷个人命书与 2027 流年年书**：
  - 卷一：本命格局总览与核心星曜特质
  - 卷二：大限十年运势起伏轨迹
  - 卷三：十四主星庙旺平陷逐星详解
  - 卷四：十二宫位（事业、财帛、夫妻、田宅等）逐宫详批
  - 卷五：流年四化引动、风水调理建议与人生曲线走势
- **真镜像双遍法矢量 PDF 渲染管线 (True-Mirror 2-Pass PDF Pipeline)**：
  - 基于 `jspdf 4 + pdf-lib`：Pass 1 零边距覆满紫金典雅封面，Pass 2 毫米级页眉页脚（12mm/10mm）与版面规整；
  - 思源宋体、霞鹜文楷子集 CID 矢量嵌入（零 Type 3 字体），放大百倍字迹边缘依旧锐利，直出 9 语样张 PDF。

### 3. 11,669 历史人物命盘库与 13 部古籍文献库
- **大规模历史人物实库**：整理收录自唐代诸帝、宋代文人、明清缙绅等 11,669 位历史名人的真实命盘数据；
- **55 篇深度精修史实考证**：针对苏轼、朱元璋、王阳明、曾国藩等历史一线人物，结合正史本传史料锚点逐宫复盘人生起伏；
- **62 种大格局实库大数据分布**：破除“吉凶绝对论”，通过万人实库大数据揭示“禄逢冲破”、“化忌入命”在历史成功人物中的真实占比；
- **13 部古典文献 2,366 段古籍检索**：集成《紫微斗数全书》《全集》《太微赋》《形性赋》等经典古文献，实现解读与古籍原文精准溯源。

### 4. 纯 Canvas 2D 超清社交分享卡 (ShareCard)
- 告别传统 `html2canvas` 跨浏览器乱序与字体变形缺陷，全链路基于 Canvas 2D 手绘单源渲染；
- 离屏导出 2004×2985 @3x 印刷级超清海报，深空星夜背景、鎏金双线外框、太极图徽、四柱八字与三方四正高亮连线一键成图。

---

## 🛠️ 东方术数大一统功能矩阵 (Comprehensive Suite)

| 模块类别 | 核心功能 | 说明与特色 |
|---|---|---|
| **紫微斗数** | `/pan` · 十二宫与六层运限 | 4×4 经典盘、四化飞星、大限旅程、人生 K 线、真太阳时 |
| **四柱八字** | `/bazi` · 八字命盘 | 四柱天干地支、藏干十神、大运流年、五行生克旺衰 |
| **双人合盘** | `/hepan` · `/compatibility` | 夫妻、合伙、人际五维契合度评分、流年婚恋动点分析 |
| **易卦纳甲** | `/wengua/liuyao` · 六爻预测 | 铜钱摇卦、纳甲世应、六亲六神变卦与卦证倾向分析 |
| **梅花心易** | `/wengua/meihua` · 梅花易数 | 时间起卦、数字起卦，本卦、互卦、变卦体用断法 |
| **奇门遁甲** | `/wengua/qimen` · 奇门排盘 | 时家转盘拆补法、九宫八门九星三奇六仪飞布 |
| **诸葛小六壬**| `/wengua/xiaoliuren` · 小六壬 | 掐指六宫（大安/留连/速喜/赤口/小吉/空亡）即时简断 |
| **观音灵签** | `/wengua/lingqian` · 观音百签 | 经典观音灵签 100 签全解，签诗断语与古人典故 |
| **河洛理数** | `/wengua/heluo` · 河洛命卦 | 天地数配卦，先后天命卦与流年运数推演 |
| **姓名学** | `/xingming` · 测名与起名 | 繁简汉字笔画、五格三才数理配置与生辰喜用神智能候选 |
| **工具箱** | `/gongju` · 辅助推演 | 出生时辰盲反推、风水方位九宫布局、命运双生子对比 |
| **每日黄历** | 今日宜忌与每日一签 | 传统天干地支吉凶、神煞宜忌、彭祖百忌与每日灵感签卡 |

---

## 🌐 多语言在线入口直达 (Global Portals)

- 🌐 **English (Global)**: [https://fateziwei.com/en](https://fateziwei.com/en)
- 🇭🇰 **繁體中文 (港澳台/海外)**: [https://fateziwei.com/tw](https://fateziwei.com/tw)
- 🇨🇳 **简体中文 (大陆)**: [https://fateziwei.com/zh](https://fateziwei.com/zh)
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
- **紫微斗数文库与 Q&A**: [https://fateziwei.com/zh/wiki](https://fateziwei.com/zh/wiki) | [https://fateziwei.com/zh/qa](https://fateziwei.com/zh/qa)
