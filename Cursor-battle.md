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

<div class="circle-corner top one"></div>
<div class="circle-corner top two"></div>
<div class="circle three"></div>
<div class="circle-corner bottom one"></div>
<div class="circle-corner bottom two"></div>
<div class="circle"></div>
<div class="rectangle-1"></div>
<div class="rectangle-2"></div>
<style>
  body{
    background:#62306D;
    display:flex;
    justify-content:center;
    align-items:center;
  }
  .rectangle-1{
    width: 140px;
    height: 100px;
    background: #F7EC7D;
  }
  .rectangle-2{
    width:60px;
    height:100px;
    background:#E38F66;
  }
  .circle-corner,.circle{
    position:absolute;
    background:#62306D;
    border-radius:50%;
  }
  .circle-corner{
    width:40px;
    height:40px;
  }
  .circle{
    width:20px;
    height:20px;
  }
  .top{
    top:80px;    
  }
  .bottom{
    top:180px
  }
  .one{
    left:80px;
  }
  .two{
    right:80px;
  }
  .circle{
    top:90px;
    right:150px;
  }
  .three{
    top:190px;
  }
</style>

```
