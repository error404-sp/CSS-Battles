# Wiggly Moustache
## Code: 
```html
<div class="halfcirc a"><div class="circ"></div><div class="semi d"></div></div>
<div class="halfcirc b"><div class="circ"></div></div></div>
<div class="halfcirc c"><div class="circ"></div><div class="semi e"></div></div>
<style>
  body{
   background: #F5D6B4;
  }
  .halfcirc{
    width: 100px;
    height: 50px;
    border-radius: 0 0 70px 70px;
    background:#D86F45;
   position: absolute
  }
  .circ{
    width: 60px;
    height: 30px;
    background: #F5D6B4;
    border-radius: 0 0 50px 50px;
    position: relative;
    left: 20px;
  }
  .a{
    left: 75px;
    top: 150px
  }
  .b{
    left: 155px;
    transform:rotate(180deg);
    top: 100px
  }
  .c{
    left: 235px;
    top: 150px;
  }
  .semi{
    width: 20px;
    height: 10px;
    border-radius: 20px 20px 0 0;
    background: #D86F45;
    position: relative;
  }
  .d{
    top: -40px
  }
  .e{
    top: -40px;
    left: 80px;
  }
  ```
  ## Output:
  ![Imgur](https://i.imgur.com/zbgRUd7.png)
