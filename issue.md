# 常见解决方案

### 1.  解决移动端开发 1px边框问题

* [使用 border.css] : https://github.com/tuoxiaozi/myTools/blob/master/myUtils/css/border.css

### 2. 300ms点击延迟问题(移动端使用click事件体验不好)

* [使用 `fastclick`]: https://github.com/ftlabs/fastclick

~~~js
yarn add fastclick --save

// main.js
import fastClick from 'fastclick'
fastclick.attach(document.body)  // 使用 fastclick
~~~

### 3. vue轮播插件vue-awesome-swiper

* [使用 vue-awesome-swiper]: https://github.com/surmon-china/vue-awesome-swiper

~~~js
yarn addd  vue-awesome-swiper@2.6.7 // 稳定版本， 避免bug

import Vue from 'vue'
import VueAwesomeSwiper from 'vue-awesome-swiper'

// require styles
import 'swiper/dist/css/swiper.css'

Vue.use(VueAwesomeSwiper, /* { default global options } */)
~~~



​          

