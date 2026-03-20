# gas_slip

LPガス計算をブラウザで入力・確認するためのシンプルな静的ページです。GitHub Pages へそのまま置けます。

## このプロジェクトの目的

今回指針と前回指針を入力して、合計金額を算出するシングルページ計算機を作成することです。

## 目指す方向

- 極力マウス操作なしで、今回指針と前回指針を入力しやすくする
- 計算式の確認を最重要事項として、とにかく見やすく、確認しやすくする

## ファイル

- `index.html`: GitHub Pages 公開用のエントリ
- `gas_slip.html`: 作業用のHTML本体

## できること

- 納品書を複数追加
- 今回指針と前回指針から使用量を計算
- m3 から kg への換算
- 単価、基本料金、消費税率を使った金額計算
- 共通設定値の一括変更

## 使い方

1. `index.html` か `gas_slip.html` をブラウザで開く
2. 必要に応じて共通設定を調整する
3. 各納品書の指針値を入力する
4. 計算結果を確認する

## GitHub Pages 公開

1. GitHub にこのリポジトリを push する
2. GitHub の `Settings > Pages` を開く
3. `Build and deployment` の `Source` を `Deploy from a branch` にする
4. Branch は公開したいブランチ、フォルダは `/ (root)` を選ぶ
5. 数分待って、払い出された Pages URL を開く

## iPhone Safari メモ

- 入力欄は 16px にして、フォーカス時の自動ズームを抑えている
- `viewport-fit=cover` と safe area 対応を入れて、ノッチ端末でも余白が詰まりにくい
- sticky ヘッダは iPhone Safari を意識して上端位置を補正している

## メモ

- ビルドは不要です
- 現状は単一HTMLで完結しています
