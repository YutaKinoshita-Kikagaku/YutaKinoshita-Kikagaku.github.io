# PMG Design Portal（YutaKinoshita-Kikagaku.github.io）

> PMG業務フローの内部向けマニュアル・運用ドキュメントを管理するリポジトリ

## GitHub Pages

- **ポータル**: https://yutakinoshita-kikagaku.github.io/
- **業務フロー**: https://yutakinoshita-kikagaku.github.io/pmg-flows/

## ディレクトリ構造

```
pmg-portal/
├── CLAUDE.md              ← このファイル
├── index.html             PMG Design Portal（トップ）
│
├── pmg-flows/
│   └── index.html         業務フロー一覧（メインタブ: P講師 / 正社員）
│
└── reference/             設計用MD・参照資料（HTMLから生成時の元ネタ）
```

## 業務フローの対象エリア

### パートナー講師
| エリア | 状態 |
|--------|------|
| 採用 | 準備中 |
| オンボーディング | 整備済み |
| 模擬講義 | 整備済み |
| 登壇テスト | 整備済み |
| 契約解除 | 整備済み |
| 発注・請求 | 準備中 |

### 正社員
| エリア | 状態 |
|--------|------|
| 採用 | 準備中 |
| オンボーディング | 整備済み（概要） |
| 模擬講義 | 準備中 |
| 登壇テスト | 準備中 |

## 作業ルール

- HTML は単一ファイル（`pmg-flows/index.html`）にタブ切り替えで集約
- **常に最新の現行フロー（As-Is）のみを掲載** — To-Be は掲載しない
- 用途: 新人メンバーのオンボーディング、既存メンバーの業務フロー再確認
- 月次でフローを見直し、最新状態を維持
- To-Be / 変革検討は `~/workspace/projects/ttt-instructor-training/ops_flow/` 側で行う

## 関連リポジトリ

| リポジトリ | 用途 |
|---|---|
| `kikagaku/ttt-instructor-training` | 講座設計・スライド制作（講義18本） |
| `YutaKinoshita-Kikagaku.github.io` | **このリポジトリ** — PMG業務フロー・マニュアル |
