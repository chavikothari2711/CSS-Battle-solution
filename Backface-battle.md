# Backface battle

## [01 Birdie](https://cssbattle.dev/play/33)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/292bc3d0-dd1d-40cb-af21-d93c5c2a2782)

```html

<div></div>
<style>
  body {
    background: #1a4341;
    display: grid;
    place-items: center;
  }
  div {
    width: 150px;
    height: 150px;
    background: #998235;
    border-radius: 50%;
    position: relative;
  }
  div::before {
    content: "";
    position: absolute;
    width: 30px;
    height: 30px;
    border-radius: 50%;
    background: #0b2429;
    top: 30px;
    left: 30px;
  }
  div::after {
    content: "";
    position: absolute;
    width: 100px;
    height: 100px;
    border-top-right-radius: 100%;
    background: #f3ac3c;
    right: -25px;
    top: -25px;
    box-shadow: 10px 80px 0 10px #1a4341;
  }
</style>

```

## [02 Christmas tree](https://cssbattle.dev/play/34)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/6129848b-0fa4-404d-921d-8e10d3ad4267)

```html

<div class="tree"></div>
<div class="tree one"></div>
<div class="tree two"></div>
<style>
  body{
    background: #007065;
  }
  .tree{
    position:absolute;
    top:50px;
    left:75px;
    width: 0; 
    height: 0; 
    border-left:125px solid transparent;
    border-right:125px solid transparent;
    border-bottom:100px solid #FFEECF;
  }
  .one{
    border-bottom:100px solid #F5C181;
    top: 100px;
    z-index:-1;
  }
  .two{
    border-bottom:100px solid #00A79D;
    top: 150px;
    z-index:-2;
  }
</style>

```

## [03 Ice Cream](https://cssbattle.dev/play/35)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/4abea33d-db32-4bab-921e-222943073552)

```html

<div class="candy"></div>
<div class="stick-end"></div>
<div class="stick-start"></div>
<style>
  body{
    background:#293462;
  }
  .candy{
    position:absolute;
    top:50px;
    left:150px;
    width: 100px;
    height: 150px;
    background: #FFF1C1;
    border-radius:50px 50px 20px 20px;
  }
  .stick-start{
    width:30px;
    height:100px;
    background:#FE5F55;
    border-radius:50px 50px 30px 30px;
    position:absolute;
    z-index:-2;
    top:150px;
    left:185px;
  }
  .stick-end{
    width:30px;
    height:30px;
    background:#A64942;
    position:absolute;
    z-index:-1;
    top:180px;
    left:185px;
  }
</style>

```

## [04 Interleveled](https://cssbattle.dev/play/36)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/b156d7ac-d05e-4f37-9935-13c31f489835)

```html

<div class="one"></div>
<div class="two"></div>
<div class="three" ></div>
<div class="four"></div>
<div class="five"></div>

<style>
  body{
    background:#1A4341;
    margin:0;
  }
  div {
    width: 50px;
    height: 200px;
    background: #F3AC3C;
    position:absolute;
    border-radius: 25px 25px 0px 0px;
  }
  div:nth-child(2n){
    top:0px;
    background:#998235;
    border-radius: 0px 0px 25px 25px;
  }
  div:nth-child(2n+1){
    bottom:0px
  }
  .one{left:25px}
  .two{left:100px}
  .three{left:175px}
  .four{left:250px}
  .five{left:325px}
</style>

```

## [05 Tunnel](https://cssbattle.dev/play/37)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/d6b2d75b-e9e4-4bd0-86e4-93d5489a75e7)

```html

<div class="center">
  <div class="one">
    <div class="two"></div>
  </div>
</div>
<style>
  body{
    background:#6592CF;
    display:grid;
    place-items:center;
  }
  .center{
    width: 250px;
    height: 250px;
    background: #243D83;
    display:grid;
    place-items:center;
  }
  .one{
    width:150px;
    height:150px;
    transform:rotate(15deg);
    background: #6592CF;
    display:grid;
    place-items:center;
  }
  .two{
    width:75px;
    height:75px;
    transform:rotate(15deg);
    background: #243D83;
  }
</style>

```

## [06 Not simply square](https://cssbattle.dev/play/38)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/2e3c1be1-253e-4365-96a9-af4aab53591e)

```html

<div class="big-square"></div>
<div class="square"></div>
<div class="square one"></div>
<div class="square-two"></div>
<div class="square-two one"></div>
<style>
  body{
    margin:0;
    background: #293462;
  }
  .big-square{
    width:200px;
    height:200px;
    background:#FFF1C1;
  }
  .square{
    position:absolute;
    top:0px;
    width:100px;
    height:150px;
    left:200px;
    background:#FE5F55;
  }
  .square.one{
    height:50px;
    top:150px;
    background:#A64942;
  }
  .square-two{
    position:absolute;
    bottom:0px;
    width:150px;
    height:100px;
    left:0px;
    background:#FE5F55;
  }
  .square-two.one{
    width:50px;
    left:150px;
    background:#A64942;
  }
</style>

```
