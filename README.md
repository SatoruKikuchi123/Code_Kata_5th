# Janken-Kata
ジャンケンを題材に、Code Kataにトライしてみましょう

## ジャンケンのルール

>勝敗に関しては、次のようなルールが定められている。
>グーは、チョキに勝ち、パーに敗れる。 
> パーは、グーに勝ち、チョキに敗れる。 
> チョキは、パーに勝ち、グーに敗れる。
2人のときは、以上に加えて両者が同じ手を出したときには「あいこ（引き分け）」となる。
> --<cite>[Wikipedia](https://ja.wikipedia.org/wiki/%E3%81%98%E3%82%83%E3%82%93%E3%81%91%E3%82%93)</cite>

## Kataの進め方

### Stage 1
両者が出した組み合わせで勝敗が決まるようにTDDでコードを書いていきましょう

 >例1) グー(Rock)はチョキ(Scissors)に勝つ  
 > 例2）両者ともにパー(Paper)を出したら引き分ける

全ての組み合わせを実装しましょう


### Stage 2
Stage1を早く終えたら、ルールを追加してやり直してみましょう

>例1）if,elseを使わない  
> 例2）マウスを使わない