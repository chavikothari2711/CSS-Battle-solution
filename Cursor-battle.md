# Cursor Battle

## [01 Cube](https://cssbattle.dev/play/19)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/a46bdf31-f3dd-444e-b153-3de568a4f030)

```html

<div class="front"></div>
<div class="left"></div>
<div class="right"></div>
<style>
  body{
    background:#0B2429;
  }
  .front{
    width: 100px;
    height: 100px;
    background: #F3AC3C;
    transform:rotate(45deg);
    position:absolute;
    bottom:65px;
    left:150px;
  }
  .left{
    width: 70px;
    height: 70px;
    background:#998235;
    position:absolute;
    top:80px;
    left:130px;
    transform: skew(0,-45deg);
  }
  .right{
    width: 70px;
    height: 70px;
    background:#1A4341;
    position:absolute;
    top:80px;
    right:130px;
    transform: skew(0,45deg);
  }
</style>

```

## [02 Ticket](https://cssbattle.dev/play/20)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/22fa4c77-b323-40ba-a623-b79f534c7dba)

```html

<div></div>
<style>
  body{background:#62306D;}
  div{
    width:140px;
    height:100px;
    background:#F7EC7D;
    margin:100px 92px;
    box-shadow:60px 0 #E38F66;
  }
  div::before,div::after{
    position:absolute;
    content:"";
    width:40px;
    height:40px;
    background:#62306D;
    border-radius:50%;
    top:80px;
    left:80px;
    box-shadow:0 100px #62306D, 200px 0 #62306D, 200px 100px #62306D;
  }
  div::after{
    width:20px;
    height:20px;
    top:90px;
    left:230px;
    box-shadow:0 100px #62306D;
  }
</style>

```
