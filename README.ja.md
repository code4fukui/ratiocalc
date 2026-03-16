# ratiocalc
日本語のREADMEは[README.ja.md](README.ja.md)をご覧ください。

シンプルなウェブベースの比率計算機です。

## デモ
アプリは [https://code4fukui.github.io/ratiocalc/](https://code4fukui.github.io/ratiocalc/) にホストされています。

## 機能
- ユーザー入力に基づいて比率を計算します
- ブラウザのIndexedDBに最後に使用した値を保存します
- モバイルデバイスでの簡単なアクセスのためにQRコードを提供します

## 使い方
1. 入力フィールドに最初の数字と二番目の数字を入力します。
2. 3番目のフィールドは最初の2つの数字に基づいて自動的に比率を計算します。
3. 計算された値はreadabilityのためにカンマ付きで表示されます。
4. 最後に使用された値はブラウザのIndexedDBに自動的に保存され、ページの読み込み時に復元されます。

## ライセンス
このプロジェクトは [MIT License](LICENSE) のもとで公開されています。
