# 買う物リスト

iPhone と PC で同じ内容を見られる、買い物リストのWebページです。

公開ページ: https://p-15rin.github.io/kaimono-list/

## できること

- URL を貼り付けると、リンク先のページから商品名・画像・サイト名を読み込んで表示（[Microlink](https://microlink.io) の無料枠を利用、1日50回まで）
- 名前・金額・個数の入力と、合計金額の自動計算
- 発売日・購入予定日をカレンダーから選択（曜日は自動表示）
- 購入済みのチェック、絞り込み、並び替え

## データの保存先

リストの中身はこのリポジトリには保存されません。
各端末で入力した GitHub トークン（`gist` 権限のみ）を使い、あなたのアカウントの**非公開 Gist**（`kaimono-list.json`）に保存します。
トークンは各端末のブラウザ内にだけ保存されます。

## 最初の設定（端末ごとに1回）

1. https://github.com/settings/tokens/new?scopes=gist&description=kaimono-list を開く
2. 有効期限を選び、`gist` にだけチェックが入った状態で「Generate token」
3. 表示されたトークンをページの「トークン」欄に貼り付けて「つなぐ」
