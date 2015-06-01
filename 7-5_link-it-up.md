Link it up!
===========

但是有更好的方法。


你知道我們應該把 CSS 寫在一個完全分開的檔案裡，但是你知道怎麼做，才能讓 HTML 檔案讀到你的 CSS 敘述嗎？


首先，把一個 `<link>` tag 放在 `<head>...</head>` 之間，裡面要有3個 attributes：

1. `type`，值恆為 `text/css`
2. `rel`，值恆為 `stylesheet`
3. `href`，你的 CSS 檔案位址

在右邊的編輯器裡面，你會看見兩個檔案： `index.html` 跟 `stylesheet.css`。


說明
----
在 `index.html` 裡面插入一個指向 `stylesheet.css` 的 `<link>` tag。
 如果你需要一些協助的話，就看一下提示吧。
