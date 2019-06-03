# article
@@ -32,7 +32,7 @@通过添加形状创建带有Zdog的3D模型。请参阅[入门]（https：//zzz.d
```js
让 isSpinning =  true ;
const  illo  =  new  Zdog.Illustration（{
让 illo =  new  Zdog.Illustration（{
  元素： '。 zdog-canvas '，
  zoom ： 4，
  dragRotate ： true，
@@ -86,7 +86,7 @@ Zdog v1是一个beta版本，各种各样。这是我第一次创建3D引擎，

### 其他Zdog回购

+ [ zdog-demos ]（https://github.com/metafizzy/zdog-demos） - 更多，更大，更狂野的Zdog演示
+ [ zdog-demos ]（https://github.com/metafizzy/zdog-demos） - 更大，更狂野的Zdog演示
+ [ zdog-docs ]（https://github.com/metafizzy/zdog-docs） -  [ zzz.dog ]（https://zzz.dog）的文档站点源代码

---
@@ -23,7 +23,7 @@ var orange ='＃E62';
var garnet =  '＃C25 ' ;
var eggplant =  '＃636 ' ;

// - 插图形状 --- //
// - --- model  - --- //

var hemi =  new  Zdog.Hemisphere（{
  addTo ： illo，
@@ -68,7 +68,7 @@ var colorWheel = [茄子，石榴石，橙子，金，黄，];
  }
}）;

// - 动画--- //
// - --- animate - --- //

var keyframes = [
  {x ： TAU  *  0，y ： TAU  *  0 }，
@@ -86,10 +86,6 @@ function animate（）{
  requestAnimationFrame（animate）;
}

animate（）;

// - 更新 -  //

function  spin（）{
  if（！ isSpinning）{
    回归 ;
@@ -104,3 +100,5 @@ function spin（）{
  illo。旋转。y  =  Zdog。线性插值（KEYA。ý，KEYB。ÿ，吐温）;
  ticker ++ ;
}

animate（）;
the second add
