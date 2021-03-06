# Lesson

+ [task12-学习CSS 3的新特性](http://ife.baidu.com/course/detail/id/117)

# Requirements

+ 学习了解 CSS 3 都有哪些新特性，并选取其中一些进行实战小练习

# Task

+ [task12 preview](https://codepen.io/zhongshanxian/pen/MpVBEo)
+ [task12 source code](https://github.com/zhongshanxian/Baidu-IFE-2017/blob/master/codes/HTML%26CSS/task12-css3.html)

### html

```html
<body>
  <div class="container-fluid">
    <table>
      <tr class="class1">
        <td>排名</td>
        <td>网站</td>
        <td>热度</td>
      </tr>
      <tr class="class2">
        <td>1.</td>
        <td>百度前端技术学院</td>
        <td>13000</td>
      </tr>
      <tr class="class2 class3">
        <td>2.</td>
        <td>百度前端技术学院</td>
        <td>12000</td>
      </tr>
      <tr class="class2">
        <td>3.</td>
        <td>百度前端技术学院</td>
        <td>11000</td>
      </tr>
      <tr class="class3">
        <td>4.</td>
        <td>百度前端技术学院</td>
        <td>10000</td>
      </tr>
      <tr>
        <td>5.</td>
        <td>百度前端技术学院</td>
        <td>9000</td>
      </tr>
      <tr class="class3">
        <td>6.</td>
        <td>百度前端技术学院</td>
        <td>8000</td>
      </tr>
      <tr>
        <td>7.</td>
        <td>百度前端技术学院</td>
        <td>7000</td>
      </tr>
      <tr class="class3">
        <td>8.</td>
        <td>百度前端技术学院</td>
        <td>6000</td>
      </tr>
      <tr>
        <td>9.</td>
        <td>百度前端技术学院</td>
        <td>5000</td>
      </tr>
      <tr class="class3">
        <td>10.</td>
        <td>百度前端技术学院</td>
        <td>4000</td>
      </tr>
    </table>
    <div align="center">
      <input type="text" class="class4">
      <input type="text" class="class5">
    </div>
    <div class="class6">
      <div class="class7">1</div>
      <div class="class7">2</div>
      <div class="class7">3</div>
    </div>
    <div class="class8">
      <div class="class10">
        <div class="class7">1</div>
        <div class="class7">2</div>
        <div class="class7">3</div>
      </div>
    </div>
    <div class="class6" style="background:blue;">
      <div class="class7">1</div>
      <div class="class7">2</div>
      <div class="class7">3</div>
    </div>
  </div>
</body> 
```

### css

```css
<style type="text/css">
  table
  {
    width:95%;
    margin:0 auto;
    font-size:14px;
  }
  .class1
  {
    background:black;
    color:white;
    border:1px solid white;
  }
  .class2
  {
    color:red;
  }
  .class3
  {
    background:#ccc;
  }
  .class4
  {
    width:30%;
    transition:width 1s;
    margin-top:20px;
  }
  .class4:hover
  {
    width:70%;
  }
  .class5
  {
     border:1px solid #88f;
     box-shadow:0 0 3px 3px #44f;
     margin-top:30px;
     width:70%;
  }
  .class6
  {
    width:100%;
    height:100px;
    background:green;
    margin-top:20px;
    display:flex;
    justify-content:flex-end;
    align-items:flex-end;
  }
  .class7
  {
    width:22px;
    height:22px;
    background:rgba(255,255,255,0.4);
    margin-left:2px;
    text-align:center;
    color:white;
  }
  .class8
  {
    width:100%;
    height:100px;
    background:blue;
    position:relative;
    margin-top:20px;
  }
  .class10
  {
    width:50%;
    height:100px;
    background:green;
    display:flex;
    justify-content:flex-end;
    align-items:flex-end;
    position:absolute;
    right:0;
  }
</style>
```

# Notes

+ 移动端完全显示
   
```html
<meta content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0" name="viewport">
```
+ 响应式界面

```html
<div class="container-fluid">
</div>
```