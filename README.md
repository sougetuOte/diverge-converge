# Diverge-Converge

AIとの対話で思考の発散・収束を構造化するClaude Codeスキル。

ブレインストーミング、企画立案、要件の洗い出しなど、「まだ形になっていないアイデア」を育てるプロセスを支援します。マンダラチャート・フィッシュボーン・SWOTなどの図法で思考を可視化し、空欄から新たな発見を得る二重ループ構造を提供します。

## 特徴

- **4つのモード**: 探索 → 反映 → 発散 → 図示化 を繰り返してアイデアを精錬
- **認知負荷の管理**: 質問は3問以下、情報はファネル式提示、判断はユーザーが決める
- **ドメインテンプレート**: ソフトウェア開発・授業設計・創作(小説/TRPG)・カスタム
- **Visualizer対応**: Claude.ai / Claude Desktopではインタラクティブなマンダラチャートとステートビューを表示
- **中断・再開**: Obsidian互換mdファイルでエクスポート/インポート

## インストール

### 方法1: Claude Codeのスキルインストールコマンド

```bash
claude skill install --from github:sougetuOte/diverge-converge
```

### 方法2: 手動インストール

1. このリポジトリをクローンまたはダウンロード:

```bash
git clone https://github.com/sougetuOte/diverge-converge.git
```

2. Claude Codeのスキルディレクトリに配置:

```bash
# グローバル（全プロジェクト共通）
cp -r diverge-converge ~/.claude/skills/diverge-converge

# プロジェクトローカル
cp -r diverge-converge .claude/skills/diverge-converge
```

## ディレクトリ構成

```
diverge-converge/
├── SKILL.md                          # スキル本体（Claude Codeが読み込むファイル）
├── README.md                         # このファイル
└── references/
    ├── visualizer-mandala.md         # マンダラチャートの描画仕様
    ├── visualizer-state.md           # ステートビューの描画仕様
    ├── onboarding.md                 # 使い方ガイドの仕様
    ├── roadmap.md                    # スキル発展計画
    └── bibliography.md              # 理論的背景・参考文献
```

## 使い方

スキルをインストールした状態で、Claude Codeに以下のように話しかけるだけです:

- 「アイデアを広げたい」
- 「ブレスト手伝って」
- 「壁打ちしたい」
- 「マンダラチャートで整理して」
- 「企画を練りたい」
- 「何から始めればいいか分からない」

セッション中のコマンド例:

- 「まとめてみて」「マンダラに落として」 → 図示化モードに移行
- 「フィッシュボーンに切り替えて」 → 図法変更
- 「エクスポートして」 → Obsidian互換mdファイルとして保存
- （保存したmdファイルを貼り付け） → 前回の続きから再開

## 対応環境

| 環境 | マンダラチャート | ステートビュー |
|------|----------------|--------------|
| Claude.ai (Web) | インタラクティブ図 | インタラクティブ図 |
| Claude Desktop | インタラクティブ図 | インタラクティブ図 |
| Claude Code (ターミナル) | Markdownテーブル | テキストインジケータ |

## ライセンス

MIT
