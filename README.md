我姓罗，大家都叫我罗仔

*我熟悉html，css，js

*同时我也有自己的爱好

1. 打羽毛球
2. 码代码
3. 码代码
4. 还是码代码

最近听到说闭包的问题我也写以前写过的一段闭包

```js
window.addEventListener('scroll', function(){
                var timer; //闭包
                var startTime = new Date();
                return function () {  
                    var curTime  = new Date();
                    if (curTime - startTime >=2000) {
                        timer = setTimeout(function () {
                                loadArticle();
                            }, 500);
                            startTime = curTime;
                        }
                    }
            }());
```

监听滚动事件，当超过2s则会执行一个0.5s定时器，内容是loadArticle()。



