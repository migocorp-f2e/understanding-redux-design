# Provider

-Context
* 用途：如果有一個層級很深的component，最深層的component會影響最外層的呈現，通常都會綁一個callback讓他一層一層的傳遞下去，進而達成目的，那這時候就可以用context來做，先在父層宣告，子層直接取用就好。

* 相關API：
<ul>
<li><b>childContextTypes - </b>用來定義父層要提供的props和types。</li>
<li><b>getChildContext - </b> getChildContext在父層用來設定要傳遞的值。</li>
<li><b>contextTypes - </b> 子層要用的時候，需要用contextTypes先定義出需要用到的context，透过this.context才能取得context中的屬性或方法。</li>
</ul>

* [Demo](https://jsbin.com/yomive/9/edit?js,output)
* [Todo]()

-Provider
(https://jsbin.com/puyuha/edit?js,output)

## 資源

[React 冷技巧 (3): Contexts](http://www.checkme.tw/wordpress/react-tips-contexts/)

[Context，React中隐藏的秘密！](https://github.com/brunoyang/blog/issues/9)
