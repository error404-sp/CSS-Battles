# Ticket
## Code:
```html
div class="a"></div>
<div class="b"></div>
<div class="c d"></div>
<div class="c e"></div>
<div class="c f"></div>
<div class="c g"></div>
<div class="i h"></div>
<div class="i j"></div>
<style>
  body{
    background: #62306D;
  }
  .a{
    width: 140px;
    height: 100px;
    background: #F7EC7D;
    position: absolute;
    top: 100px;
    left: 100px;
  }
  .b{
    width: 60px;
    height: 100px;
    background: #E38F66;
    position: absolute;
    left: 240px;
    top: 100px
  }
  .c{
    background:#62306D;
    width: 20px;
    height: 20px;
    border-radius: 0 0 20px;
    position: absolute;
  }
  .d{
   left: 100px;
    top: 100px;
  }
  .e{
    transform: rotate(-90deg);
    left: 100px;
    top: 180px;
    
  }
  .f{
    transform: rotate(90deg);
    left: 280px;
    top: 100px;
  }
  .g{
    transform: rotate(180deg);
    left: 280px;
    top: 180px;
  }
  .i{
    width: 20px;
    height: 10px;
    background: #62306D;
    border-radius:0 0 20px 20px;
   position: absolute;
  }
  .h{
    left: 230px;
    top: 100px
  }
  .j{
    transform:rotate(180deg);
    left: 230px;
    top: 190px
  }
</style>
```
## Output:
![Imgur](https://i.imgur.com/m2pi5n5.png)
