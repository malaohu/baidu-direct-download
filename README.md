# 百度网盘(百度云)文件直连下载

支持pan.baidu.com  yun.baidu.com 域名下的文件下载。

该扩展特点：无任何多余的权限索取，精简无毒。

没什么技术含量 核心代码就4行。

```
var _d = document;
var _s = _d.createElement('script');
_s.textContent = "Object.defineProperty(navigator,'platform',{get:function(){return '';}});";
_d.documentElement.appendChild(_s);
```

扩展已经发布在：https://chrome.google.com/webstore/detail/iepjhhnlpojejcoepjeanhbgfaihonnf

