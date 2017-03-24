# CanvasLazyload
canvas 懒加载


JQ编写，适用于触屏设备。

## 使用示意
①. 引入JS文件，例如

``` html
<script src="CanvasLazyload.min.js"></script>
<div id="canbox">
     <canvas data-src='images\bkc.jpg'></canvas>
     <canvas data-src='images\jbs.png'></canvas>
</div>
```

``` css
 canvas {
      width: 100px;
      min-height: 100px;
      background: #fff url("images/01.gif") center center;
      /*background-size: 100%;*/
}
  ```      

②. 绑定

``` javascript
  $(function() {
     $('#canbox').myCanvas();
   })
```

## 语法
``` javascript
  $(ele).myCanvas({option});
```

