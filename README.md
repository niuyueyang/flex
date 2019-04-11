# flex
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
      html,body{
        width: 100%;
        height: 100%;
      }
      *{
        margin: 0;
        padding: 0;
        list-style: none;
        box-sizing: border-box;
      }
      .wrap{
        display: flex;
        /*flex-direction: row;*/
        width: 100%;
        height: 100%;
        overflow: hidden;
        flex-wrap: wrap;
        padding: 20px;
        /*justify-content: space-around;*/
        /*justify-content: space-between;*/
        /*justify-content: flex-end;*/
        /*justify-content: flex-start;*/
        flex-direction: row;
        /*align-items: flex-start;*/
        /*align-content: flex-start;*/
        /*align-items: flex-end;*/
        /*align-content: flex-end;*/
        /*align-items: center;*/
        /*align-content: space-between;*/
        justify-content: space-around;    /*水平一行多个*/

        align-items: baseline;
        align-items: center;        /*竖直一行多个或者水平一行多个居中*/
        align-content: flex-start; /*竖直多行多个或者水平多行多个*/
        align-content: space-around;
        align-content: space-between;
        align-content: center;
      }
      .item{
        width: 19%;
        height: 100px;
        background-color: #00B7FF;
        text-align: center;
        line-height: 100px;
        font-size: 20px;
        color: #fff;
      }
      .item:nth-child(1){
        height: 200px;
      }
    </style>
</head>
<body>
  <div class="wrap">
      <div class="item">1</div>
      <div class="item">2</div>
      <div class="item">3</div>
      <div class="item">4</div>
      <div class="item">5</div>
      <!--<div class="item">6</div>-->

<!--      <div class="item">7</div>
      <div class="item">8</div>
      <div class="item">9</div>
      <div class="item">10</div>
      <div class="item">11</div>
      <div class="item">12</div>-->
  </div>
</body>
</html>

```
