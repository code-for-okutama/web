# 計算問題生成システム(毎日自動生成）

## 概要

毎晩、新しい計算問題を生成するシステムです。

特定のURLをクリックするとPDFがダウンロードできます。

プリントアウトして、毎日の練習問題としてご活用ください。

## 仕様

- 問題の更新は、１日に１回です。
- 更新は、日本時間の深夜0時〜1時までの間に行われます。
- 問題用紙の日付は自動的に入力されます。
- 同じ問題が連続で並ばないようにしています。
- 同じ答えが連続する場合は、一定確率ではじきます。（でにくくなる）
- １枚に複数の種類の問題を含められます（復習問題などで使用中）

## PDFのダウンロード（毎日更新）

### 九九の練習（小学校２年）

- [2と3の段の九九](https://gift10.net/pdf/?t=daily_cal_19)
- [4と5の段の九九](https://gift10.net/pdf/?t=daily_cal_20)
- [6と7の段の九九](https://gift10.net/pdf/?t=daily_cal_21)
- [8と9の段の九九](https://gift10.net/pdf/?t=daily_cal_22)
- [ランダム九九(2以上)](https://gift10.net/pdf/?t=daily_cal_23)

### １１級（小学校１年）

[一般財団法人日本教科別能力検定協会](http://kyoken.or.jp/index.html)の計算能力検定の問題集です。

- [足し算	10まで](https://gift10.net/pdf/?t=daily_cal_0)
- [足し算	20まで（10といくつ）](https://gift10.net/pdf/?t=daily_cal_1)

- [足し算	20まで（くりあがり）](https://gift10.net/pdf/?t=daily_cal_2)
- [足し算	100まで（10単位）](https://gift10.net/pdf/?t=daily_cal_3)
- [足し算	100まで（くりあがらない）](https://gift10.net/pdf/?t=daily_cal_4)
- [引き算	10まで](https://gift10.net/pdf/?t=daily_cal_5)
- [引き算	20まで（くりさがり）](https://gift10.net/pdf/?t=daily_cal_6)
- [引き算	100まで（くりさがらない）](https://gift10.net/pdf/?t=daily_cal_7)
- [引き算	100まで（10単位）](https://gift10.net/pdf/?t=daily_cal_8)
- [足し引き算　100まで（ゾロ目_2桁と1桁）](https://gift10.net/pdf/?t=daily_cal_9)
- [足し引き算　100まで（ゾロ目_2桁と2桁）](https://gift10.net/pdf/?t=daily_cal_10)
- [引き算	10から引く](https://gift10.net/pdf/?t=daily_cal_11)
- [足し引き算	10からの差](https://gift10.net/pdf/?t=daily_cal_12)
- [足し引き算	30まで、答えが奇数（くりあがり、さがり）](https://gift10.net/pdf/?t=daily_cal_13)
- [足し算	10まで、３つの要素](https://gift10.net/pdf/?t=daily_cal_14)
- [足し算	20まで、３つの要素のうち２つが10になる](https://gift10.net/pdf/?t=daily_cal_15)
- [足し引き算	20まで、３つの要素、足し引き算が混合](https://gift10.net/pdf/?t=daily_cal_16)
- [20まで、３つの要素](https://gift10.net/pdf/?t=daily_cal_17)
- [足し引き算	復習（全１０種類）](https://gift10.net/pdf/?t=daily_cal_18)

## 技術資料

このプロジェクトは[github](https://github.com/TakashiHamada/DailyCal)で公開しています。[MITライセンス](https://github.com/TakashiHamada/DailyCal/blob/main/LICENSE)に沿って、自由に複製、改変が可能です。共同開発も歓迎しています。

問題生成の仕様を確認したい場合は、こちらの[ファイル](https://github.com/TakashiHamada/DailyCal/blob/main/SubjectDefine.js)をご参照ください。

ご意見ご要望、不具合の発見は[github Issues](https://github.com/TakashiHamada/DailyCal/issues)か、[お問い合わせ](https://docs.google.com/forms/d/e/1FAIpQLSc6VYzbGQHDt16gFmeK7rctmjfijtZQaCXdK36yW_CfN9T66w/viewform?usp=sf_link)よりご連絡ください。
