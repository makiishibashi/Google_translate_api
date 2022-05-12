# バイリンガルチャットアプリ
[https://makiishibashi.github.io/Google_translate_api/]
## Firebaseを使ったチャットをGoogle翻訳のAPIで英訳をAlertに表示させる
# 苦労したところ
- 最初はHotpepperグルメのAPIや音声系のAPIにトライしようとしたが、参考サイトの情報が古いのかJavascriptに実装する際に上手くいかず、どのAPIにするかの選定に時間がかかってしまった
- Google翻訳のAPIがどうにか連携できたのだが、FirebaseのオブジェクトをGoogle翻訳にかけて、Alertに表示するとこで、詰んでしまった。
- 最終的に検証画面に表示されているエラーを調べて、参考サイトを頼りに何とか英訳を表示できるようになった。
# こだわったところ
詰んている時間が長くて、あまりこだわれなかったが、強いて挙げるならこれまで講義で習ったこと（Alert表示やFirebase）を盛り込んだこと