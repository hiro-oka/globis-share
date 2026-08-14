# globis-share

グロービス経営大学院 セクションG の共有資料置き場（**リンクを知る人のみ・noindex**）。

- 全ページに `<meta name="robots" content="noindex, nofollow">` を入れ、`robots.txt` で全体を `Disallow` にしている。検索エンジンには載らない。
- 閲覧にログインは不要。リンクを渡した相手だけが開ける前提。
- 公開したくなくなったらファイルを削除して push すれば即座に見られなくなる。

## ページ

| ページ | 内容 |
|---|---|
| [section-g-kickoff.html](https://hiro-oka.github.io/globis-share/section-g-kickoff.html) | 第4期支援団 キックオフ資料（2026年10月〜2027年3月） |

## 作り方

- 1ファイル完結のHTML（CSS・フォントすべて埋め込み。外部リクエストなし）
- 日本語フォントは Noto Sans JP のサブセットを woff2 + base64 で埋め込む
- ライト／ダーク両対応、スマホ対応
