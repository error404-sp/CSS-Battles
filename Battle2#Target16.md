# Eye of the tiger
## Code:
```html
<div class="circ"><div class="circ1"><div class="circ2"></div></div></div>
<style>
  body{
    background:#0B2429
  }
  .circ{
    width: 200px;
    height: 200px;
    position: absolute;
    background: #998235;
    border-radius: 0 50%;
    transform: rotate(-45deg);
    left: 100px;
    top: 50px
  }
  .circ1{
    width: 140px;
    height: 140px;
    background: #F3AC3C;
    border-radius: 50%;
    border: 20px solid #0B2429;
    position: relative;
    left: 10px;
    top: 10px;
  }
  .circ2{
    width: 50px;
    height: 50px;
    background: #0B2429;
    border-radius: 50%;
    position: relative;
    left: 45px;
    top: 45px
  }
</style>
```
## Output:
![Imgur](https://i.imgur.com/TPO48CA.png)
