# redblue

同人誌即売会のサークル管理・参加申込システム

## 開発環境導入

### 事前準備

Macなら下記を実行

- homebrew入れる
- rbenvを入れる
- `rbenv install 2.4.2`

### サーバ起動

```bash
git clone git@github.com:comiaca/redblue.git
cd redblue
gem install bundler
bundle install
bundle exec rails server # サーバを起動
# Webブラウザから localhost:3000 にアクセス
```