# Web Maker Logo
## Code:
```html
<div class="tri a"></div>
<div class="tri b"></div>
<div class="tri c"></div>
<div class="tri d"></div>
<style>
  body{
    background: #F2F2B6;
  }
  .tri{
    width: 150px;
    height: 130px;
clip-path: polygon(50% 0%, 0% 100%, 100% 100%);
    position: absolute;
  }
  .a{
    background: red;
    left: 80px;
    transform: rotate(180deg);
    top: 85px;
  }
  .b{
    background: #FF6D00;
    left: 60px;
    transform: rotate(180deg);
    top: 85px;
  }
  .d{
    background: red;
    left: 170px;
    top: 85px;
  }
  .c{
    background: #FF6D00;
    top: 85px;
    left: 190px;
    
  }
</style>
```
## Output
![Imgur](https://i.imgur.com/51Zvdr7.png)
