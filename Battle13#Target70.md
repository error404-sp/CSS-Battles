# Froggy
## Code:
```html
<div class="face">
  <div class="fr">
  <div class="eye a">
    <div class="nose c"></div></div>
  <div class="eye b">
    <div class="nose c"></div></div>
   <div class="nose d"></div>
    <div class="nose  d e"></div></div></div>
<style>
body{
background:#293462;
  display: flex;
  justify-content: center;
  align-items: center;
  }
.face{
  width: 150px;
  height: 100px;
  background: #FE5F55;
  border-radius: 50px;
  position: relative;
  top: 10px;
  display: flex;
  }
  .fr{
    width: 150px;
    height: 70px;
    border-radius: 130px;
    border-bottom: 30px solid #A64942;
    display: flex;
    
  }
  .eye{
    width: 30px;
    height: 30px;
    background: #FFF1C1;
    border-radius: 50%;
    position: relative;
    top: -25px;
    border: 10px solid #FE5F55;
  }
  .a{
    left: 15px
  }
  .b{
    left: 35px;
  }
  .nose{
    width: 10px;
    height: 10px;
    background: #293462;
    border-radius: 50%;
    position: relative;
  }
  .c{
    left: 10px;
    top: 10px;
  }
  .d{
    top: 50px;
    left: -20px;
  }
  .e{
    left: -50px;
  }
</style>
```
## Output
![Imgur](https://i.imgur.com/pEJPYR6.png)
