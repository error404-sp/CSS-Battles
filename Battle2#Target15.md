# Overlap
## Code:
```html
<div class="circ a"></div>
<div class="circ b"></div>
<div class="circ1"></div>
<style>
  body{
    background: #09042A;
  }
  .circ{
    width: 150px;
    height: 150px;
    position: absolute;
    border-radius: 50%;
  }
  .a{
     background: #7B3F61;
    left: 75px;
    top: 75px;
  }
  .b{
    background: #E78481;
    left: 175px;
    top: 75px;
  }
  .circ1{
    width: 82.5px;
    height: 82.5px;
    position: absolute;
    background: #09042A;
    left: 158px;
    top: 110px;
    border-radius: 125px 0 125px 0;
    transform: rotate(-45deg)
  }
</style>
```
## Output: 
![Imgur](https://i.imgur.com/5IjpZIh.png)
