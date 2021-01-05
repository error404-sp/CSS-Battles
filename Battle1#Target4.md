# Ups n Downs
##  Code:
```html
<div class="square a"></div><div class="square b"></div><div class="square a c"></div>
<style>
  body{
    background:#62306D;
  }
  .square{
    width: 100px;
    height: 100px;
    background: #F7EC7D;
    border-bottom-left-radius: 50%;
    border-bottom-right-radius: 50%;
    position: absolute;
  }
  .a{
    top: 150px;
    left: 50px;
  }
  .b{
    left: 150px;
    transform:rotate(180deg);
    top: 50px;
  }
  .c{
    left: 250px;
  }
  
</style>
```
## Output:
![Imgur](https://i.imgur.com/CwbXUj8.png)
