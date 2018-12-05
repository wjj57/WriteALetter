# WriteALetter

<p align="center">
<img src="https://img.shields.io/badge/language-JavaScript-red.svg">
<img src="https://img.shields.io/badge/platform-web-orange.svg">
<img src="https://img.shields.io/badge/version-1.0-blue.svg">
<img src="https://img.shields.io/badge/license-MIT-black.svg">
</p>

利用原生 JavaScript 实现动态打字写信（Writting a Dynamic Letter By JavaScript Without Libraries）
[立即使用](#usage)
## 介绍

<img src="https://github.com/Lvsi-China/WriteALetter/raw/master/images/logo.gif">

利用原生 JavaScript ，实现动态打字写信的效果。鄙人时间精力有限，而且毕竟不是做美工的，所以，样式做的比较粗糙，不过以后有新的想法的时候会不断的更新。

## <span id="usage">使用</span>

> 1. 下载项目到本地
> 2. 配置 ```config.js``` 文件，配置信息如下
```
var config = {

	dom  : "Letter", // 主体 DOM , 只支持 id = ""

	// 关于信的内容
	name : "You",
	from : "Yours sincerely",
	date : "2018-12-05 15:20:30",

	speed: 110, // 打字速度 , 100 - 120 之间比较适合

	sideBar: true, // 是否开启侧边栏


};
```
> 3. 配置完之后，直接运行 index.html 文件即可。

## 代码

其实，主要不容易解决的地方在于如何一个一个的输出文字，在使用多个 ```setInterval()```的时候，你还会发现输出的文字是乱序的，这就需要想办法去解决乱序问题，或者用其他方法替代，其实能实现的方法还是比较多的。而且，还能在输出的时候，控制每一行。

## 说明

仅为娱乐而已，不要较真。觉得样式不好看的朋友，可以自己 fork 下来，按照自己的意愿设计即可。

