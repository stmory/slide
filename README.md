## slide ##

一个简单的轮播，100行代码实现了移动端和pc端兼容的滑动。
纯原生JS，练手写了个轻量级的轮播图插件，无第三方依赖，开箱即用，没有过多的繁杂配置。

### demo ###

https://stmory.github.io/html/slide.html

### Usage ###

```html
    <div id="slide">
        <div class="slide-page" style="background-color: #234767">1</div>
        <div class="slide-page" style="background-color: #322454">2</div>
        <div class="slide-page" style="background-color: #4df3e2">3</div>
        <div class="slide-page" style="background-color: #dfe233">4</div>
        <div class="slide-page" style="background-color: #645723">5</div>
    </div>
```
```js

    let a = new Slide('slide')      //输入轮播的id
    a.initSlide()               //初始化
    //todo 可以添加配置参数
```

