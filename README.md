# C# はじめの一歩

C#の基本文法を日本語で学ぶための、更新型のWeb資料です。

## 収録内容

全18章で、最初のコンソール出力から実用的なC#の入口までを扱います。

- プログラム構造、変数、データ型、文字列、型変換
- 演算子、条件分岐、繰り返し、メソッド
- 配列、リスト、辞書、集合、タプル
- クラス、オブジェクト指向、null安全性、例外処理
- LINQ、ジェネリック、ラムダ式、イベント
- async/await、ファイル操作、プロジェクト構成

## 公開ページ

`main` ブランチへ変更を反映すると、GitHub Actionsが
`public/csharp-basics.html` をGitHub Pagesへ自動公開します。

初回のみ、GitHubリポジトリの **Settings → Pages → Build and deployment** で
公開元を **GitHub Actions** に設定してください。

## Codexで改善する流れ

1. Codexへ「○○の説明を追加して」「このコード例を改善して」と依頼する
2. CodexがHTMLを更新し、表示とビルドを確認する
3. 変更内容をGitへ保存し、GitHubへ送る
4. GitHub Pagesが自動更新され、スマートフォンから同じURLで確認できる

## 編集するファイル

- `public/csharp-basics.html` — 教材本体（HTML・CSS・JavaScriptを1ファイルに収録）
- `.github/workflows/pages.yml` — GitHub Pagesへの自動公開設定

## ローカル確認

HTMLファイルをブラウザで直接開くか、開発用プレビューを起動します。

```bash
npm install
npm run dev
```

## 更新方針

- 1回の更新ではテーマを絞る
- コード例はそのまま実行できる形を優先する
- 初心者向けの用語説明を省略しない
- PCとスマートフォンの両方で読みやすく保つ
- 大きな変更はGitの履歴を分け、以前の版へ戻せるようにする
