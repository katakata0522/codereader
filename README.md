# codereader

このリポジトリは、`preview`からCodeReaderへ名称変更する途中で作成された**プレースホルダー**です。

## 実装本体

現在の実装・コミット履歴・Issue・ブランチは、次のリポジトリにあります。

- `katakata0522/preview`

`preview`には、HTML・CSS・JavaScript入力、iframeプレビュー、複数タブ、Undo / Redo、JSON Export / Import、共有URL、メモなどの機能が実装されています。

## 統合方針

空のこのリポジトリへコードをコピーして二重管理するのではなく、実装本体の`preview`リポジトリ自体を`codereader`へ改名し、履歴を維持します。

統合前に必要な作業は次のとおりです。

1. 現在利用中のCodeReader画面からJSON Exportする
2. 現在の公開URLとGitHub Pages設定を記録する
3. このプレースホルダーを一時改名または削除する
4. 実装本体の`preview`を`codereader`へ改名する
5. 新URLでJSON Importし、保存データと動作を確認する

localStorageは公開URLごとに分かれるため、JSON Export前にURLを変更しないでください。

## 注意

このリポジトリを新規実装の正本として使用しません。正式統合が完了したら、このREADMEは実装本体側のREADMEへ置き換えます。
