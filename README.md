# memoapp

## メモアプリ

メモを保存、更新、削除することができます。

## ダウンロード方法

```zsh
git clone url(後で入力)
```

## 起動方法

```ruby
bundle exec ruby app.rb
```

## 使い方、仕様

新規作成ボタンを押すとメモのタイトルと内容を入力をするフォームに移動します。

保存するタイトルと内容が決まったら保存ボタンを押します。（タイトルを入力しなかった場合、保存後のメモのタイトルは「タイトルがありません」に自動的になります。）

保存ボタンを押すとtopページに移動し、メモのタイトルが表示されます。

メモのタイトル、内容を変更、または削除したい場合はメモのタイトルをクリックします。(変更の保存は新規作成とほぼ同じです。)

削除は削除ボタンを押すと完了します。復元はできません。

変更したメモはページの一番下に移動します。
