# Ship
## Code
```html
<div class="color a"></div>
<div class="color b"></div>
<div class="color c"></div>
<div class="color d"></div>
<div class="line up left1"></div>
<div class="line up right1"></div>
<div class="line mid left2"></div>
<div class="line mid right2"></div>
<div class="line down"></div>
<div class="line e"></div>
<div class="line e f"></div>
<div class="line g"></div>
<div class="line h"></div>
<style>
  body{
    background:#191919;
  }
  
  .line{
    background: #5DBCF9;
     position:absolute; 
    width: 10px;
  }
  .up{
    height: 40px;
    top: 67px;
  }
  .mid{
    height: 62px;
    top: 97px;
  }
  .left2{
    left: 150px;
  }
  .right2{
    left: 243px;
  }
  .left1{
    left: 175px;
  }
  .right1{
    left: 215px;
  }
  .down{
    height: 60px;
    top: 135px;
    left: 195px
  }
  .color{
    background:#5DBCF9;
    position:absolute; 
    height: 10px;
  }
 
  .a{
    width: 200px;
    top: 205px;
    left: 100px
  }
  .b{
     width: 110px;
    top: 225px;
    left: 145px
  }
  .c{
    width: 103px;
    top: 97px;
    left: 150px;
  }
  .d{
    width: 50px;
    top: 67px;
    left: 175px;
  }
  .e{
    left: 160px;
    top: 110px;
    height:90px;
    
   transform: rotate(60deg);
  }
  .f{
    transform:rotate(-60deg);
    left: 232px;
  }
  .g{
    top:175px;
    left: 125px;
    height: 22px;
    width: 22px;
   
    clip-path: polygon(0 0, 48% 0, 100% 100%, 48% 100%);
  }
  .h{
    top:173px;
    left: 256px;
    height: 22px;
    width: 22px;
    clip-path: polygon(48% 0, 100% 0, 52% 100%, 0 100%);
  }
</style>
```
*********************************************
## Output:
![Imgur](https://i.imgur.com/bru9Htn.png)
