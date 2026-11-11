文末に半角スペースを2つ入れる
1行空白の行を入れる
--- <br> タグを使う

# 見出し1
## 見出し2
### 見出し3
#### 見出し4

ヘアラインは---を記述する。
---

>引用したい文章

https://www.jec.ac.jp 
[日本電子専門学校へリンク](https://www.jec.ac.jp)
[日本電子専門学校へリンク](https://www.jec.ac.jp "https://www.jec.ac.jp")

*ここがemタグで強調されます*  
_ここがemタグで強調されます_  

**ここがstrongタグで強調されます**  
__ここがstrongタグで強調されます__  

~~打ち消し線~~

<details><summary>要約をここに記述する</summary>
本文をここから書く。xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx</details>

文頭に-、+、*のいずれかを入れるとリストになる。
- HTML
- JAVA
- PHP

1. SQL
1. JavaScript
1. SQL

- [ ] タスク1
- [x] タスク2

テーブル（表）を表示する。
|A列|B列|C列|D列|E列|
|-|:-:|:-|-:|-|
|あ|い|う|え|お|
|かか|きき|くく|けけ|ここ|
|さささ|しし|すすす|せせせ|そそそ|

プログラムなどのコードをそのまま記述したい場合は、バッククォートで囲む
```
for(int i=0; i<10; i++){
    int rand = (int)(Math.random()*10);
    System.out.println("乱数[" + i + "]:" + rand);
}
```

![代替テキスト](画像のURL)
タイトル無しの画像を埋め込む

![代替テキスト](画像のURL "画像タイトル")
タイトル有りの画像を埋め込む

![H3ロケット](https://www.jaxa.jp/projects/rockets/h3/images/h3_main_001.jpg)
![H3ロケット](https://www.jaxa.jp/projects/rockets/h3/images/h3_main_001.jpg "H3ロケット22S形態)
