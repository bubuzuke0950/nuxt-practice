# これはなに
nuxtの練習と共同開発の練習用のリポジトリ
進め方とかここに書いときます

# 開発の進め方
## 手元に入れる
リポジトリをclone
```
git clone <このリポジトリ>
```

```
npm install
```

プレビュー
```
npm run dev
```

## ブランチを切る
現在のブランチを確認
```
git branch
```

新しくブランチを作成
```
git checkout -b <ブランチ名>
```

## 編集内容を現在のブランチに　push
全ての変更をpushする場合
```
gti add .
```

特定のファイルの変更のみの場合
```
git add  <path>
```

### コミット
コミットメッセージの書き方は以下を参照
https://qiita.com/itosho/items/9565c6ad2ffc24c09364
```
git commit -m "コミットメッセージ"
```

### originブランチにpush
```
git push origin <ブランチ名>
```
## プルリクエストを作成
こっからはGUIの方がよさそう
https://qiita.com/ysk91_engineer/items/f7676f2a7cde7251132b
