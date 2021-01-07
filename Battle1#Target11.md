# Eye of Sauron
## Code:
```html
div class="halfc a"><div class="halfc1"></div></div>
<div class="halfc b"><div class="halfc1"></div></div><div class="circle1"><div class="circle"></div>
 </div>
<style>
  body{
    background: #191210;
  }
  .circle{
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background: #84271C;
    position: absolute;
    border: 25px solid #191210;
    left: 20px;
    top: 20px;
   position: absolute;
  }
  .circle1{
    width: 140px;
    height: 140px;
    background: #ECA03D;
    border-radius:50%;
    left: 125px;
    top: 75px;
    position: absolute;
  }
  .halfc{
    width: 100px;
    height:  50px;
    border-radius: 0 0 70px 70px;
    background: #ECA03D;
    position: absolute;
  }
  .halfc1{
    width: 60px;
    height: 30px;
    border-radius: 0 0 50px 50px;
    background: #191210;
    left: 20px;
    position: relative;
  }
  .a{
    top: 150px;
    left: 45px;
  }
  .b{
    top: 100px;
    left: 245px;
    transform:rotate(180deg)
  }
  ```
  ## Output:
  ![Imgur](https://i.imgur.com/DavBN9W.png)
