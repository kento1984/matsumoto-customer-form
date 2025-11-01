# マツモト産業 受付管理システム

お客様からの注文・見積もり依頼を受け付けるWebフォームシステム

## 機能

- カスタマーお問い合わせフォーム（注文・見積依頼・問い合わせ）
- 顧客マスタ（メールアドレスで検索）
- お気に入り商品機能（最大30件）
- CSV出力機能
- 自動確認メール送信

## 技術スタック

- Node.js + Express
- nodemailer（メール送信）
- ファイルベースのデータ保存（CSV + JSON）

## セットアップ
```bash
npm install
node server.js
```

## 環境変数

`.env`ファイルを作成：
```
EMAIL_USER=your-email@mac-exe.co.jp
EMAIL_PASS=your-password
PORT=3000
```
