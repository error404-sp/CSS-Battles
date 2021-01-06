# Missing Slice
## Code
```html
<div class="square a"></div>
<div class="square b"></div>
<div class="square c"></div>
<style>
  body{
    background:#E3516E;
  }
  .square{
    width: 100px;
    height: 100px;
    position: relative;
  }
  .a{
    background: #51B5A9;
    border-radius: 100px 0 0 0;
    left: 100px;
    top: 50px;
  }
  .b{
    background: #F7F3D7;
    border-radius: 0 0 0 100px;
    left: 100px;
    top: 50px;
  }
  .c{
    background: #FADE8B;
    border-radius: 0 100px 0 0;
    left: 200px;
    top: -150px;
  }
  
</style>
```
Output: 
![Imgur](https://i.imgur.com/fWIHGyO.png)
