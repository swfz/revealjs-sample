# reveal.js
## sample
### とりあえずサンプル

--

# 縦の移動
## foooooooo!!!!!

---

# 日本語
## ＼(^o^)／

---
- javascript

```.javascript
var a = 'hoge';

function hoge(a){
  console.log(a)
}

hoge(a);
```

- diff

```
+ aaa
- bbb
```

---
- shellscript

```.shellscript
#/bin/sh

echo_bar(){
  [ "$1" -gt 0 ] && printf '*%.0s' `seq "$1"`
}

while true
do
  hour=`date +%H`
  min=`date +%M`
  sec=`date +%S`

  tput cup 0 0
  tput clear
  printf "h: $hour: `echo_bar $hour`\n"
  printf "m: $min: `echo_bar $min`\n"
  printf "s: $sec: `echo_bar $sec`\n"
  sleep 1
done
```

---

# fragments
- item1 <!-- .element: class="fragment" data-fragment-index="1" -->
- item2 <!-- .element: class="fragment" data-fragment-index="2" -->
- item3 <!-- .element: class="fragment" data-fragment-index="3" -->

---
# style(動き)
- pdf変換も出来るよ <!-- .element: class="fragment grow" -->
- remarkにも付いて欲しいよ <!-- .element: class="fragment shrink" -->
- あんなに苦労したのに... <!-- .element: class="fragment current-visible" -->
- とりあえずrevealに移行しよう <!-- .element: class="fragment fade-out" -->
- mkdocsでも見れるようにする予定 <!-- .element: class="fragment highlight-current-blue" -->
- テンプレ化 <!-- .element: class="fragment highlight-red" -->
- からのLT系の資料作成時間削減 <!-- .element: class="fragment highlight-current-green" -->

---

# style(配置)

- 配置の設定(left) <!-- .element: style="text-align: left;" -->
- 配置の設定(bottom) <!-- .element: style="vertical-align: bottom;" -->

---
# 引用

> 引用です
> > 二重引用です
> > > 三重引用もあり？

---
# 引用2

> - list
> - list2
>     - list3

---
# 背景画像

パラメータを付与することで動的に背景画像をパララックス表示できる

```
http://192.168.100.11:8080/?parallaxBackgroundImage=https%3A%2F%2Fs3-ap-northeast-1.amazonaws.com%2Fswfz-slide-images%2Fbackground.png&parallaxBackgroundSize=2000px%201000px/
http://192.168.100.11:8080/?parallaxBackgroundImage=https%3A%2F%2Fs3-ap-northeast-1.amazonaws.com%2Fswfz-slide-images%2Fbackground_dark.png&parallaxBackgroundSize=2000px%201000px/
```

---
# 背景画像
## スライド全体の背景

```
<!-- .slide: data-background="/background01.jpeg" -->
```

## sectionの背景

```
<!-- .element: data-background="/background01.jpeg" -->
```

---
# テーブル

| a | b | c |
|:-|:-|:-|
| hoge | fuga | piyo |
| HOGE | FUGA | PIYO |
| 123  | 456  | 7890 |

Note: ノートのテスト

---
# リンク
- [mkdocsのサンプル0](http://swfz.github.io/mkdocs_sample )

---
# 画像
![text](http://swfz.github.io/darts/images/img.png ) <!-- .element: style="margin: auto;" -->

- センター寄せはなぜかこれ

```
![text](http://swfz.github.io/darts/images/img.png ) <!-- .element: style="margin: auto;" -->
```

---

** 終わり **




