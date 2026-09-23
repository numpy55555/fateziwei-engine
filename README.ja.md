# Fate Ziwei (紫微斗数・四柱推命) · 確定論的天文暦法エンジン＆多言語プラットフォーム

<p align="center">
  <a href="README.md"><strong>English</strong></a> •
  <a href="README.zh-CN.md"><strong>简体中文</strong></a> •
  <a href="README.zh-TW.md"><strong>繁體中文</strong></a> •
  <a href="README.ja.md"><strong>日本語</strong></a>
</p>

<p align="center">
  <a href="https://fateziwei.com/ja"><img src="https://img.shields.io/badge/公式サイト-fateziwei.com-purple" alt="公式サイト"></a>
  <a href="https://fateziwei.com/ja"><img src="https://img.shields.io/badge/対応言語-10言語ネイティブ-blue" alt="対応言語"></a>
  <a href="https://fateziwei.com/zh/famous"><img src="https://img.shields.io/badge/計算精度-560%2F560%20全テスト検証済-brightgreen" alt="精度テスト"></a>
  <a href="https://fateziwei.com/zh/famous"><img src="https://img.shields.io/badge/歴史上の偉人-11%2C669%20件の命盤-gold" alt="偉人命盤"></a>
  <a href="https://fateziwei.com/zh/book/sample"><img src="https://img.shields.io/badge/出力形式-ベクターPDF完全対応-red" alt="PDF出力"></a>
</p>

---

## 🌟 概要 (Overview)

**Fate Ziwei** は、厳密な確定論的天文暦法計算アルゴリズムと、10言語に対応したネイティブ AI 鑑定書生成エンジンを融合した最先端の東洋占術プラットフォームです。伝統的な紫微斗数（しびとすう）、四柱推命（しちゅうすいめい）、易経（周易）、奇門遁甲を、最新のフロントエンド工学、天文暦法モデル、大規模言語モデル（LLM）と融合させ、学術研究レベルの高精度な命理分析を提供します。

- 🇯🇵 **日本語ポータル**: [https://fateziwei.com/ja](https://fateziwei.com/ja)
- 🌐 **公式グローバルサイト**: [https://fateziwei.com](https://fateziwei.com)
- 🌐 **English (Global)**: [https://fateziwei.com/en](https://fateziwei.com/en)
- 🇭🇰 **繁體中文 (台湾・香港)**: [https://fateziwei.com/tw](https://fateziwei.com/tw)
- 🇨🇳 **简体中文**: [https://fateziwei.com/zh](https://fateziwei.com/zh)

---

## ⚡ コアテクノロジーと特徴

### 1. 確定論的天文暦法と超高精度作盤エンジン
- **560/560 フィールド単位の全テストケース検証済み**：南半球・北半球の座標換算、うるう月、早子時・夜子時の境界処理など、極端なエッジケースを古籍原典基準で100%パス。
- **真太陽時（True Solar Time）リアルタイム補正**：世界各地の都市緯度経度データベースを内蔵し、均時差（Equation of Time）をミリ秒単位で算出。標準時との誤差を完全に補正。
- **学派・流派ルールの自由設定**：三合派・四化派ロジック、早子時/夜子時設定、うるう月の振り分け方式など、主要な流派アルゴリズムに柔軟対応。

### 2. 10言語ネイティブ AI 鑑定書＆ Two-Pass ベクター PDF パイプライン
- **機械翻訳に頼らないネイティブ生成**：各言語圏の文化的文脈や専門術語に基づき、AI がゼロから自然で格調高い鑑定文を書き下ろし。
- **全30ページ・5巻構成の「人生の取扱説明書」**：【運命の基盤】【5大領域の深層分析】【大限（10年運）】【年運（流年）】【古典文献の考察】を網羅。
- **Two-Pass（二段階）ベクター PDF レンダリングエンジン**：`jspdf + pdf-lib` ハイブリッド構成により、フチなし高解像度アート表紙、ベクターフォントの完全埋め込み、印刷品質のベクター出力を実現。

### 3. 東洋術数・総合プロダクトマトリクス
- **紫微斗数（Ziwei Dou Shu）**：本命盤、10年大限盤、年運（流年）、月運（流月）、日運（流日）、時運（流時）の多層解析と動的飛星。
- **四柱推命（Bazi）**：正確な節気移行、十神・蔵干解析、五行エネルギーバランスの定量化。
- **相性診断・結婚鑑定（Synastry）**：命宮・夫妻宮の多次元共鳴、星のエネルギー補完度をスコアリング。
- **伝統占術 6 大システム**：易経（周易六爻）、梅花心易、奇門遁甲、小六壬、観音百籤、河洛理数。
- **専門ツール群**：出生時間逆算ツール、風水九宮飛星レイアウト、運命の双子（同生年月日比較）。

### 4. 11,669 名の歴史上の偉人命盤データベースと古典文献集
- **膨大な歴史データ**：11,669 名の偉人データを収録。さらに正史（二十四史）に基づき精密に考証された 55 名の特選命盤を完備。
- **62 種類の古典的「大格（パターン）」ビッグデータ統計**：君臣慶会、石中隠玉、極向離明など名格の出現頻度と星配置を分析。
- **2,366 件の古典原典引用データベース**：『紫微斗数全書』『太微賦』『形性賦』など 13 部の元典と構造的に連携。

### 5. Canvas 2D Retina 級ポスター生成エンジン
- **2004×2985 @3x Retina 解像度**：印刷に対応可能な超高精細アートポスターをワンクリック出力。
- **動的幾何連線レンダリング**：三方四正のアスペクトライン、四化飛星のベクトル軌跡、カスタム落款印をダイナミック描画。

---

## 🌐 オンラインポータル一覧 (Global Portals)

- 🇯🇵 **日本語**: [https://fateziwei.com/ja](https://fateziwei.com/ja)
- 🌐 **English (Global)**: [https://fateziwei.com/en](https://fateziwei.com/en)
- 🇭🇰 **繁體中文 (台湾・香港)**: [https://fateziwei.com/tw](https://fateziwei.com/tw)
- 🇨🇳 **简体中文**: [https://fateziwei.com/zh](https://fateziwei.com/zh)
- 🇰🇷 **한국어**: [https://fateziwei.com/ko](https://fateziwei.com/ko)
- 🇻🇳 **Tiếng Việt**: [https://fateziwei.com/vi](https://fateziwei.com/vi)
- 🇫🇷 **Français**: [https://fateziwei.com/fr](https://fateziwei.com/fr)
- 🇪🇸 **Español**: [https://fateziwei.com/es](https://fateziwei.com/es)
- 🇩🇪 **Deutsch**: [https://fateziwei.com/de](https://fateziwei.com/de)
- 🇷🇺 **Русский**: [https://fateziwei.com/ru](https://fateziwei.com/ru)

---

## 📖 特設ページ＆サンプルへのダイレクトリンク

- **2027年 運勢特別特集**: [https://fateziwei.com/zh/liunian-2027](https://fateziwei.com/zh/liunian-2027)
- **歴史上の偉人命盤アーカイブ**: [https://fateziwei.com/zh/famous](https://fateziwei.com/zh/famous)
- **AI 鑑定書サンプル閲覧**: [https://fateziwei.com/zh/book/sample](https://fateziwei.com/zh/book/sample)
- **相性診断・相性鑑定**: [https://fateziwei.com/zh/hehun](https://fateziwei.com/zh/hehun)
- **紫微斗数ナレッジベース & FAQ**: [https://fateziwei.com/zh/wiki](https://fateziwei.com/zh/wiki) | [https://fateziwei.com/zh/qa](https://fateziwei.com/zh/qa)

---

## ⚖️ ライセンスおよび免責事項

本リポジトリの計算アーキテクチャおよび技術仕様書は、学術研究および技術紹介を目的として公開されています。詳細およびサービス利用は [fateziwei.com](https://fateziwei.com) をご覧ください。
