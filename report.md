# レポート課題

## 課題1: Docker & ECS

まずは，自分のローカルのコンピュータで Docker を動かしてみよう．
- 自分のコンピュータに Docker をインストールせよ
- [講義資料8.3章](https://tomomano.github.io/learn-aws-by-coding/#_transformer_%E3%82%92%E7%94%A8%E3%81%84%E3%81%9F_question_answering_%E3%83%97%E3%83%AD%E3%82%B0%E3%83%A9%E3%83%A0) を参考に，本講義で提供している質問応答の Docker image (https://hub.docker.com/repository/docker/tomomano/qabot) を，**ローカルのコンピュータで**実行せよ．
- 自分で context と question の組み合わせを考え，プログラムがどのような答えを返したか，報告せよ．

つづいて，[講義資料8章](https://tomomano.github.io/learn-aws-by-coding/#sec_fargate_qabot) に書いてあるハンズオンを一通り自分自身の AWS アカウントを用いて実行せよ．
- そのうえで，[講義資料8.7章](https://tomomano.github.io/learn-aws-by-coding/#_%E3%82%BF%E3%82%B9%E3%82%AF%E3%81%AE%E5%90%8C%E6%99%82%E5%AE%9F%E8%A1%8C) に従い，複数の質問を同時に投げかけた時の ECS クラスターのスケールの様子を確認せよ．
講義資料の Figure 53 に示したように， AWS Console から ECS のクラスターの挙動を確認し，スクリーンショットを撮り，レポートに報告せよ．
- そのほか，自由課題として，プログラムの一部を改変するなどして自由に実験を行ってみよ．
行った実験とその結果を報告せよ．

**7/20: 訂正 Figure 49 -> Figure 53 の誤りでした．すみませでした🙇‍♂️**

## 課題2: Serverless architecture

* [講義資料10章，11章，12章](https://tomomano.github.io/learn-aws-by-coding) を読み， Serverless Architecture について自習せよ．
* [講義資料12.1章](https://tomomano.github.io/learn-aws-by-coding/#_lambda_%E3%83%8F%E3%83%B3%E3%82%BA%E3%82%AA%E3%83%B3) にある Lambda ハンズオンを自分自身の AWS アカウントを用いて実行せよ．多数のタスクを同時に Lambda で実行し，Lambda のコンソールからタスクの実行状況を確認し，スクリーンショットを撮りレポートに報告せよ (Figure 86 参照)．
* [講義資料12.2章](https://tomomano.github.io/learn-aws-by-coding/#sec:dynamodb_tutorial) にある DynamoDB ハンズオンを自分自身の AWS アカウントを用いて実行せよ．ハンズオンを行った証明として，Figure 91 を参考に，データの書き込みを行った後の DynamoDB のコンソールのスクリーンショットを撮り，報告せよ．
* [講義資料12.3章](https://tomomano.github.io/learn-aws-by-coding/#sec:s3_tutorial) にある S3 ハンズオンを自分自身の AWS アカウントを用いて実行せよ．ハンズオンを行った証明として， Figure 94 を参考に，アップロードを実行した後の S3 のコンソールのスクリーンショットを撮り，報告せよ．

## 選択課題

選択課題は，2つのうちから1つを選択して解答する．

## 選択課題1: Serverless Arhictecture (2)

- [Hellerstein et al., "Serverless Computing: One Step Forward, Two Steps Back
" arXiv (2018)](https://arxiv.org/abs/1812.03651) を読んで次の設問に答えよ．
- 著者らは，Serverless computing の利点と，MapReduceなど他の分散処理システムと比較した時の欠点や今後の課題を議論している．著者らの論点をまとめ，800文字以内で記述せよ．
- また，著者らの主張に対して，自分の意見や考えがある場合は，それも併せて記述せよ (その場合も，800文字以内の文字制限は変わらない)．

## 選択課題2: Serverless Application

* [講義資料13章](https://tomomano.github.io/learn-aws-by-coding/#sec_bashoutter) にあるハンズオンを一通り自分自身の AWS アカウントを用いて実行せよ．
* `client.py` を用いて，俳句を投稿する API を300回実行せよ．
Lambda のコンソールから，この時のタスクの実行状況を確認し，スクリーンショットを撮って報告せよ．
* ブラウザから，デプロイされた GUI にアクセスせよ．証明として，ブラウザの画面のスクリーンショットを撮って，報告せよ．
