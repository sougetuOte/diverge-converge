# 理論的背景・参考文献・検索キーワード

## 理論的背景

### 認知負荷理論（Cognitive Load Theory）
- **提唱者**: John Sweller
- **3分類**: 内在的負荷（問題の本質的な難しさ）/ 外在的負荷（提示方法の悪さ）/ 学習関連負荷（理解のための有益な負荷）
- **このスキルとの関係**: 外在的負荷をファネル式提示・ステートビュー・日本語ラベルで削り、学習関連負荷を空欄マスの発見・討論の観察で生む。内在的負荷はスキルでは制御できない

### ダブルダイヤモンド（Double Diamond）
- **提唱**: British Design Council
- **構造**: ◇発散→収束（問題定義）→ ◇発散→収束（解決策定義）
- **2019年改訂**: 「Framework for Innovation」としてデザイン原則とメソッドバンクを追加
- **このスキルとの関係**: 二重ループ構造はダブルダイヤモンドの反復版。ドメインテンプレートはメソッドバンクに相当

### Wallasの創造性4段階モデル
- **提唱者**: Graham Wallas (1926)
- **4段階**: 準備（Preparation）→ 孵化（Incubation）→ 啓示（Illumination）→ 検証（Verification）
- **このスキルとの関係**: 探索=準備、反映=孵化、発散=啓示、図示化=検証

### Guilfordの発散-収束フレームワーク
- **提唱者**: J.P. Guilford (1956)
- **概要**: 発散的思考（複数の可能性を生成）と収束的思考（選択肢を評価・選択）の区別
- **このスキルとの関係**: モードの分離（発散中に判断を迫らない）の理論的根拠

### Cognitive Fit Theory
- **提唱者**: Iris Vessey (1991)
- **概要**: 問題の表現形式が解決方法の表現形式と一致すると認知負担が下がる
- **このスキルとの関係**: 将来の図法自動推薦（空間的問題→マンダラ、因果関係→フィッシュボーン）の根拠

## インタビュー手法

### ファネル技法（Funnel Technique）
- 広く開けた質問から始めて、段階的に具体的な質問へ絞り込む
- **このスキルとの関係**: 探索結果の提示方法。デフォルト端的→興味があれば深掘り

### ラダリング（Laddering）
- 情報階層を下に掘る質問（「なぜそれが重要？」）と横に広げる質問の組み合わせ
- Means-End Chain Theory（属性→結果→価値の連鎖）に基づく
- **このスキルとの関係**: ユーザーが興味を示した項目の深掘り手法

## 直接的な先行研究

### CreativeDC (Nguyen & Singla, 2025)
- **論文**: arXiv:2512.23601
- **概要**: LLMの推論を発散フェーズと収束フェーズに明示的に分離する2フェーズプロンプティング手法
- **結果**: 51-63%の創造性向上（多様性・新規性の指標）、実用性を維持
- **このスキルとの関係**: 「発散中に判断を迫らない」設計の学術的根拠

### HAIExplore (Wen et al., 2025)
- **論文**: arXiv:2512.18388
- **概要**: 人間-AI共創におけるデザイン固着（premature convergence）を防ぐ構造化パラダイム
- **結果**: ChatGPTの線形チャットと比較して、固着軽減・制御性向上
- **このスキルとの関係**: 「構造化された発散→収束のイテレーション」の有効性の実証

### Kumar et al. (2024)
- **論文**: arXiv:2410.03703
- **概要**: 1,100人実験。LLM支援は短期的に創造性を向上させるが、支援なし時の独立した創造性を阻害し得る
- **結果**: 「コーチ型LLM」（ガイダンス提供）の方が「直接回答型」より長期的に良い結果
- **このスキルとの関係**: 「AIは提案のみ、判断はユーザーが決める」設計の根拠

### ペルソナ分離アプローチ (2025)
- **論文**: arXiv:2510.26490
- **概要**: 発散ペルソナ（temperature 0.8）と収束ペルソナ（temperature 0.3）を切り替え可能にしたチャットインターフェース
- **このスキルとの関係**: 将来の討論モード設計への参考

## 要求工学関連

- **RDRA**（神崎善司）: https://www.rdra.jp/ — 表形式の要求分析フレームワーク。Coding Agentとの相性が良い
- **IPA「ユーザのための要件定義ガイド 第2版」**: https://www.ipa.go.jp/archive/publish/tn20191220.html
- **IEEE RE 2026**: 「Sustainability and workforce transformation in the era of generative AI」がテーマ

## Obsidian + Claude Code エコシステム

- Mauricio Gomes「Teaching Claude Code My Obsidian Vault」
- Kyle Gao「Using Claude Code with Obsidian」(Anthropic社員)
- ZanderRuss/obsidian-claude (GitHub): 31コマンド、27エージェント
- HackerNews「Show HN: Skill for structured deep research with Claude Code and Obsidian」(2026-03)

## 検索キーワード

日本語: 要求工学、認知負荷理論、ダブルダイヤモンド、ラダリング、ファネル技法、発散的思考、収束的思考、デザイン思考、ブレインストーミング、マンダラチャート、特性要因図

英語: requirements engineering, cognitive load theory, double diamond, laddering, funnel technique, divergent thinking, convergent thinking, design thinking, CreativeDC, HAIExplore, premature convergence, design fixation, human-AI co-creation
