# 福井県長期ビジョン県民アンケートデータ

[English](README.md)

福井県が公表している「福井県長期ビジョンの実現に向けた県民アンケート」の調査結果を、CSVデータとグラフ表示アプリとしてまとめたリポジトリです。

出典ページ: https://www.pref.fukui.lg.jp/doc/seiki/vision2019/pre_questionnaire.html

## ファイル

- `index.html`: ブラウザで見るグラフ表示アプリ
- `survey_overview.csv`: 年度別の調査概要
- `questionnaire_timeseries.csv`: 定期的に取られている設問の時系列データ

## データ

`survey_overview.csv` は令和元年度から令和7年度、つまり2019年度から2025年度までの調査概要を収録しています。

`questionnaire_timeseries.csv` には、以下のような継続・定期設問を収録しています。

- 福井県に暮らしてきて良かったと思うか
- 現在どの程度幸せか
- 住んでいる地域に自分の居場所があると感じるか
- 住んでいる地域に自己表現・活躍できる場があると感じるか
- 住んでいる地域に愛着や誇りを感じるか
- 仕事のWell-being 3指標

## ローカルで見る

`index.html` をブラウザで開くか、ディレクトリをローカルサーバで配信します。

```sh
python3 -m http.server 8765
```

次のURLを開きます。

```txt
http://localhost:8765/
```

## 補足

ダウンロードしたPDF、抽出テキスト、一時画像などの途中制作物は `.gitignore` で除外しています。

