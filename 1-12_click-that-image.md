按那個圖片
==========

做的好！現在你知道怎麼在你的網頁中加上圖片了。要不把個圖片變成連結吧？

例如：

```
  <a href="http://www.codecademy.com/">
      <img src="http://s3.amazonaws.com/codecademy-blog/assets/f3a16fb6.jpg"/>
  </a>
```

1. 首先我們開一個 `<a>` tag，然後再把 href 指到 http://www.codecademy.com/ 一次。
2. 但是這次，我們不在 `<a>` 裡面放文字，而是放一個 `<img>` tag。
3. 最後，我們要把 `</a>` tag 關起來。

現在你點那個黃色鴉子的時候，你就會被帶去 http://www.codecademy.com/ ！


在一個 HTML tag 裡面放另一個 HTML tag 這件事情，我們叫做 **nesting**.


說明
----

1. 在 `<body>` 區塊裡面，新增一個 `<a>` tag。
2. 找一個你的連結要指向的網頁，例如 `<a href="http://www.codecademy.com">`
3. 現在在你的 `<a>` 跟 `</a>` tag 之間新增一個 `<img>` tag。（不要忘了 `src` ！）
4. 最後，在你的 `<img>` 之後關閉你的 `</a>` tag.
