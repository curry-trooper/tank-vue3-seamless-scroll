English | [中文](./README_zh.md)

# tank-vue3-seamless-scroll

## features

* This is a high-performance seamless scrolling plug-in
* Event monitoring will not fail


## preview

![](demo.gif)

## Quick Start

### install

```shell
npm install --save tank-vue3-seamless-scroll
```

### import

```js
import TankSeamlessScroll from "tank-vue3-seamless-scroll"
```

### use component

```html

<div style="height:300px;">
    <tank-seamless-scroll :step-length="25" :debug="true" :reverse="false">
        <div class="demo">
            <div v-for="i in 2" :key="i">测试{{ i }}</div>
        </div>
    </tank-seamless-scroll>
</div>
```

### api

#### step-length

* desc：Pixel height moved per second
* default: 60 (px/second)
* type: Number

#### reverse

* desc：The animation will play in reverse scrolling
* default: false
* type: Boolean

#### debug

* desc：Whether to display debugging information
* default: false
* type: Boolean



