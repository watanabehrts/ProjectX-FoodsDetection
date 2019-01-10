# ProjectX-FoodsDetection
料理の物体検出を行うソースコード

## 物体検出
料理最終.ipynbの環境リセットからバウンディングボックス通りにトリミングまでが物体検出のソースコード  
料理の画像から各料理を検出して各料理画像にトリミングを行う。  
実行内容が複雑な為詳しくは[こちら](https://qiita.com/tk-tkhs/items/eb74ea516cadfaa202a0)を参照(Qiitaの記事です)。  
フォルダの階層は個人によって違うため注意してください。  
## VGGNet,ResNetを用いての学習
料理最終.ipynbのから細かい料理認識から精度の確認までが学習のソースコード  
参考にさせていただいたサイト　[https://www.y-shinno.com/vgg16-finetuning-uecfood100/](https://www.y-shinno.com/vgg16-finetuning-uecfood100/)  
最初の自身のいる場所をcontent上にしたの後順に実行していけば動きます(クラス数を変更したりする場合書き換えなければいけない箇所あり)。  
学習はcontent上で実行するようにしてください。  
追加したいクラスがない場合は「UECFOOD100以外の分類したいクラスの追加」の部分は飛ばしてください。  
重みとcsvファイル、精度確認の為だけの精度確認.ipybファイルがグーグルドライブにあります。  
グーグルドライブのurlは[こちら](https://drive.google.com/open?id=1F8hbp5OGM5syGDQLpFPxbP1n9yFz804K)
