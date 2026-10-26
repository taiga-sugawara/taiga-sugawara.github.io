# 菅原大雅のホームページ

GitHub Pages用の個人ホームページです。HTMLとCSSのみで構成し、外部ライブラリやビルド処理は使用していません。

## ページ構成と編集する場所

各ページは共通メニューから移動できます。JavaScriptは不要です。

| ファイル | 内容 |
| --- | --- |
| `index.html` | ホーム・各ページへの案内 |
| `about.html` | 自己紹介・所属・研究分野 |
| `research.html` | 研究テーマの説明 |
| `publications.html` | 学術誌論文・プレプリント・学会発表 |
| `career.html` | 学歴・受賞歴 |
| `links.html` | GitHub・Google Scholar・研究室 |
| `style.css` | 全ページ共通のデザイン（`:root`で配色変更） |

メニューを変更する場合は、各HTMLの `<nav>` を揃えて更新してください。

アイボリーとブルーを基調としたデザインです。画像・フォント・スクリプトの外部配信には依存せず、狭い画面では1列に切り替わります。OSの「視差効果を減らす」設定に合わせて登場アニメーションを停止します。

## 情報の出典（2026年10月27日確認）

- 本人提供の論文原稿 `paper.pdf` の著者略歴：2025年3月の学部卒業、修士課程在学、研究分野、2025年の2件の受賞。
- 学術誌論文の正式な掲載情報は、原稿内の仮の巻号・日付ではなく出版社の情報を使用。
- [システム制御情報学会論文誌](https://doi.org/10.5687/iscie.39.215)：39巻9号、215–223ページ、2026年。
- [Wiley](https://doi.org/10.1002/rnc.70119)：36巻1号、100–116ページ、2026年（早期公開は2025年8月）。
- [arXiv](https://arxiv.org/abs/2603.25139)：2026年3月のプレプリントとして掲載。
- [共著者の業績一覧](https://sites.google.com/view/sakuramakazunori/研究業績)：2025年の学会発表3件。
- [自動制御連合講演会の書誌情報](https://doi.org/10.11511/jacc.68.0_1963)。
- [SICE会議論文](https://controls.papercept.net/images/temp/SICE/files/0105.pdf)。
- [SCI学生発表賞](https://sci25.iscie.or.jp/award/)。
- [研究室の2025年度ページ](https://www.cis.sys.es.osaka-u.ac.jp/過去のページ/2025年度)：優秀発表賞ほか。

Google Scholarプロフィールは自動取得できなかったため、各公開元で確認できた6件を掲載しています。全件を網羅するものではありません。提供されたPDFはリポジトリにコピーしていません。

## 手元で確認

`index.html` をブラウザで開くと、メニューから各ページに移動できます。公開時は全HTMLファイルと `style.css`をまとめてアップロードしてください。

## GitHub Pages

公開時はリポジトリの **Settings → Pages** で **Deploy from a branch / main / (root)** を選びます。
非公開のまま編集を続ける場合は、PagesのBranchを **None** にしておきます。リポジトリがPublicならソースコード自体は公開されています。
