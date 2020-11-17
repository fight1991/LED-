# LED-数字样式
## 使用led数字样式步骤
> 1. 在css中定义
```css
@font-face {
  font-family: 'UnidreamLED';
  src:url(../../lib/UnidreamLED/UnidreamLED.eot); /***兼容ie9***/
  src:url(../../lib/UnidreamLED/UnidreamLED.eot?#iefix)format('embedded-opentype'), /***兼容ie6-ie8***/
  url('../../lib/UnidreamLED/UnidreamLED.woff') format('woff'), 
  local('UnidreamLED'), url("../../lib/UnidreamLED/UnidreamLED.woff");/***默认使用本地的***/
}


> 2. 使用样式
```css 
span {
  font-family: 'UnidreamLED'
}
