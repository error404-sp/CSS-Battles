# Sitepoint Logo
## Code:
```html
<div class="a"><div class="b"></div></div>
<div class="a c"><div class="b d"></div></div>
<style>
  body{
    background: #222;
  }
  .a{
    width: 30px;
    height: 100px;
    background: #F2994A;
    transform: rotate(45deg);
    position: absolute;
    border-radius: 0 0 0 10px ;
    top: 60px;
    left: 155px;
  }
  .b{
    width: 30px;
    height: 55px;
    background: #F2994A;
    transform:rotate(90deg);
    position: absolute;
    top: 57px;
    left: 35px;
    border-radius:10px 0 0 0 
  }
  .c{
    transform: rotate(-135deg);
    background: #2D9CDB;
    top: 140px;
    left: 215px;
  }
  .d{
    background: #2D9CDB;
  }
</style>
```
## Output: 
![Imgur](https://i.imgur.com/MOEOols.png)
