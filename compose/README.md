# Redux Compose

## How to write compose
- curry 函數的柯里化
	* 就是把多個參數的函數切成很多只有一個參數的函數
	* [Demo](http://jsbin.com/tonapez/edit?js,console)

- compose (functional programing 的 compose)
    * 從左到右組合多個函數        
    * 複合函數
    * [Demo](http://jsbin.com/xifuge/edit?js,console)
	* [Todo](http://jsbin.com/quhofa/edit?js,console)

- compose + reduceRight
    * 用法同reduce
    * 與reduce 的執行方向相反
    * [錯誤的Demo](http://jsbin.com/sinuze/edit?js,console)
    * [Demo](http://jsbin.com/wisupif/edit?js,console)
    
- compose + for loop
	* [Demo](http://jsbin.com/zeqero/edit?js,console)

- [簡報PDF](https://github.com/migocorp-f2e/understanding-redux-design/blob/master/compose/redux-compose.pdf) 
- [compose 應用](http://scott.sauyet.com/Javascript/Talk/Compose/2013-05-22/#slide-18)
- [redux compose 應用](https://jsbin.com/tumozojoye/edit?js,console)
## 資源
- [函數式編程初探 - 阮一峰](http://www.ruanyifeng.com/blog/2012/04/functional_programming.html)
- [reduceRight](https://msdn.microsoft.com/zh-tw/library/ff679979(v=vs.94).aspx)
