# 注释
1. html中的注释
```html
<!-- 这里是html的注释-->
```
2. css的注释
```css
/*这里写css的注释*/
```
3. js的注释
```javascript
单行注释
//这里写注释
/*
 *这里写注释
 */
```
---
# js的位置
1. js的位置分三种
    行间、内嵌、外链
2. 内嵌js的位置问题
    * 内嵌js在body中
        * 一般没有问题，但是页面代码一般按照从上到下的顺序执行
        * js脚本放在最后肯定没问题
    * 在head中 要想在js中获取body中的对象 需要添加window.onload
        ```javascript
        window.onload=function(){
            这里写页面加载完后执行的代码
        }
        ```
