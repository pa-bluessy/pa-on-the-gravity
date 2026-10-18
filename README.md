# pa-on-the-gravity（仮称）

Gravity企画用に作った4つのページ（YouTube再生数ランキング／セットリスト）を、1つのリポジトリにまとめたものです。リポジトリ名は仮のもので、あとで変更する予定です。

## 目的

これまで別々のリポジトリにあった4つの「gravity-ranking」ページを1か所に集め、管理しやすくします。

- 第1段階（今回）：元のファイルを**そのままコピー**しただけです。デザインや内容は一切変えていません（中身はバイト単位で同じです）。
- 今後：デザインを **ADELE ページの形式**（あらすじ・章ごとのナレーション・プレイリストボタン）に揃え、データ（曲・再生数）はアーティストごとのファイルに分ける予定です。

## 変更履歴

- 2026-10-18：smg / sia / metallica-srv の見た目と構成を adele の形式に揃えました（adele は変更なし）。smg の採用・保留・却下ボタンは削除しました。曲・順位・再生数などのデータは変えていません。

## フォルダ構成

```
index.html                 4ページへのリンク一覧
smg/index.html             SEX MACHINEGUNS 特集・YouTube再生数ランキング
sia/index.html             Sia 特集・2時間セットリスト
adele/index.html           ADELE 特集・30分セットリスト
metallica-srv/index.html   METALLICA／STEVIE RAY VAUGHAN 特集・2時間セットリスト
metallica-srv/metallica-srv-data.json  METALLICA／SRV の再生数データ（yt-dlp取得、2026-10-16）
```

## コピー元

元のリポジトリは、確認が済むまでそのまま残しています（変更・削除はしていません）。

| フォルダ | コピー元リポジトリ | コピー元のコミット |
|---|---|---|
| `smg/` | https://github.com/pa-bluessy/smg-gravity-ranking （master） | `71e50dd` |
| `sia/` | https://github.com/pa-bluessy/sia-gravity-ranking （main） | `9e53fdd` |
| `adele/` | https://github.com/pa-bluessy/adele-gravity-ranking （main） | `2defcf2` |
| `metallica-srv/` | https://github.com/pa-bluessy/metallica-srv-gravity-ranking （master） | `a38df94` |
