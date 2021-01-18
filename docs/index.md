---
title: ホーム
---

## Workflow Meetup の GitHub Pages へようこそ

workflow Meetup は今や研究者が独学するには手に負えないほどに膨れ上がったワークフロー関連技術の学習をピアサポートで解決することを目的としたコミュニティです。

「ワークフロー」には基本的にバイオインフォマティクスのワークフローを想定しています。
「関連技術」は具体的に言うと「コンテナ、クラウド、ワークフロー記述言語」の3つになります。

これらの技術は「今」新たに学ぶ必要が生まれた技術であり、(繰り返しになりますが)研究者が「独学」するのは容易ではありません。
また容易ではありませんが「自分以外の人にワークフローを実行してもらう必要がある」場合は習得が必須の技術です。

Workflow Meetupはそのような習得が困難かつ必要性が高いワークフロー関連技術の学習をピアサポートで解決することを目的としたコミュニティです。
具体的な活動としては月1回のバーチャルミートアップを行っています。

興味を持たれた方は我々のSlack workspace https://workflow-meetup-jp.slack.com/ にご参加ください。
(招待リンクは https://join.slack.com/t/workflow-meetup-jp/shared_invite/zt-jzydjvsm-oDfLHKcTgpSK9SGUWdaWIg になります。)

## Workflow Meetup の Google Calendar

[この URL](https://calendar.google.com/calendar/embed?src=8n4altth1rb2fi2ig28ngkvnog%40group.calendar.google.com&ctz=Asia%2FTokyo
) を使用すると、ウェブブラウザからこのカレンダーにアクセスできるようになります。

## 情報リソース(おすすめのベストプラクティス情報)

「どのワークフローシステムを使ってよい(学んでよい)かわからない、教えてほしい」
と思われるかと思います。

私たちは「Snakemake」の「tutorial」を学ぶことをおすすめします。
その理由は

- 例が最も実用的
- 技術に使われるPythonは公用語
- ワークフロー記述についての自然言語説明が丁寧

だからです。

「Snakemakeに不足を感じたら他のワークフローシステムも試す」

のがベストプラクティスになると思います。

### Snakemake

#### [Snakemake tutorial 和訳](https://github.com/workflow-meetup-jp/snakemake-tutorial-jp)
https://snakemake.readthedocs.io/en/stable/tutorial/tutorial.html
を和訳したものです。

実用的な例がステップbyステップで学習できるようになっています。

#### @kokitsuyuzaki さんによる Snakemake の紹介 YouTube動画 from @biopackathon
[![](http://img.youtube.com/vi/j9l8u1w3840/0.jpg)](http://www.youtube.com/watch?v=j9l8u1w3840 "snakemakeの紹介@antiplastics")

### CWL

#### [CWL User Guide](https://www.commonwl.org/user_guide/)

これは...です。...を...風に学ぶことができます。

### Galaxy

#### [Galaxy Training!](https://training.galaxyproject.org/training-material/)

世界中のGalaxyコミュニティによって開発および保守されているチュートリアルのコレクションです。

下記の画像ように各トピック毎のトレーニングマテリアルへのリンクがまとめられています。

画像のテーブルの各列の意味は下記になります。
![galaxytable](galaxy.png)

- Slides: ...
- Hands-on: ...
- Input dataset: ...
- Workflows: ...
- Galaxy tour: ...
- Galaxy instances: ...

### Nextflow

Snakemakeのtutorial相当の(実例的かつ[自然言語的]説明が詳しい) トレーニングマテリアルはありません。

[自然言語的]説明は無い実例としては https://www.nextflow.io/index.html のメニューバーの"Examples"があります。

### レビュー論文

[Streamlining data-intensive biology with workflow systems](https://doi.org/10.1093/gigascience/giaa140)

をおすすめします。
