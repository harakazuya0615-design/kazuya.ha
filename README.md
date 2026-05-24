# 勤怠管理アプリ

シンプルなブラウザ完結型の勤怠管理アプリです。

## 機能
- 月間カレンダー / 年間ビュー
- 出勤・欠勤・遅刻・有給・休日の記録
- 実働時間・残業時間の自動計算
- **給与計算**（時給制・月給制、残業倍率、休日労働、交通費）
- **Google Drive 自動同期**（複数端末間でデータ共有）
- 手動エクスポート / インポート (JSON)

## 使い方
ブラウザで `index.html` を開くだけ。データはブラウザの localStorage に保存されます。

## Google Drive 同期を使う場合
[Google Cloud Console](https://console.cloud.google.com/) で OAuth Client ID を取得し、アプリの「同期」→「OAuth Client ID」欄に貼り付けてください。

承認済みの JavaScript 生成元には GitHub Pages のURL（例: `https://USERNAME.github.io`）を登録します。
