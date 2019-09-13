# 常见解决方案

  1.  解决移动端开发 1px边框问题
     
* 使用 border.css: 
     
        https://github.com/tuoxiaozi/myTools/blob/master/myUtils/css/border.css
     
  2. 300ms点击延迟问题(移动端使用click事件体验不好)
     
     * 使用 `fastclick`
     
       ~~~js
       yarn add fastclick --save
       
       // main.js
       import fastClick from 'fastclick'
       fastclick.attach(document.body)  // 使用 fastclick
       ~~~
     
       
     
       
     
       

   