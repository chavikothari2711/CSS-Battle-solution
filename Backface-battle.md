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

<div></div>
<style>
    body{
      background:#1A4341
    }
    div{
      width:50px;
      height:250px;
      background:#998235;
      border-radius:30px;
      position:absolute;
      top:-50px;
      left:100.2px;
      box-shadow:150px 0 #998235,-75px 149.5px #F3AC3C,75px 149.5px #F3AC3C,225px 149.5px #F3AC3C}</style>

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

<div></div>
<style>
    body{
      margin:0;
      background:#293462
    }
    div{
      width:200px;
      height:200px;
      background:#FFF1C1;
      box-shadow:100px -50px #FE5F55, 100px 0 #A64942,-50px 100px #FE5F55,0 100px #A64942
    }
</style>

```
## [07 Sunset](https://cssbattle.dev/play/39)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/956ee20b-81e0-4d89-a457-756285b51196)

```html

<div></div>
<style>
  body {
    background: radial-gradient(circle at 50% 50%, #998235 100px, #1a4341 50px);
  }
  div::before {
    position: absolute;
    content: "";
    width: 250px;
    height: 250px;
    border-radius: 50%;
    background: linear-gradient(
      transparent 55px,
      #1a4341 55px, #1a4341 75px,#f3ac3c 75px,
      #f3ac3c 95px,#1a4341 95px,#1a4341 115px,
      #f3ac3c 115px,#f3ac3c 135px,#1a4341 135px,
      #1a4341 155px,#f3ac3c 155px,#f3ac3c 175px,
      #1a4341 175px,#1a4341 195px,transparent 195px
    );
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
  }
</style>

```
## [08 Letter B](https://cssbattle.dev/play/40)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/4d98a84c-e87c-4f27-938e-827bf3d029e0)

```html

<div class="circle"></div>
<div class="rectangle"></div>
<style>
  body{
    background:#6592CF;
  }
  .circle{
    position:absolute;
    top:50px;
    left:100px;
    box-sizing:border-box;
    border-radius:50%;
    border:50px solid;
    border-color: #6592CF #243D83 #243D83;
    transform:rotate(-45deg);
    width: 200px;
    height: 200px; 
    z-index:-1;
  }
  .rectangle{
    position:absolute;
    z-index:1;
    top:50px;
    left:100px;
    background:#243D83;
    height:100px;
    width:49.5px;
  }
</style>

```

## [09 Fox Head](https://cssbattle.dev/play/41)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/b3a3ca36-e6bf-4357-b299-ff237fb4f394)

```html

<p/><h1/><h2/>
<style>
    *{
        background:#293462
    }
    p,h2{
        width:50;
        height:140;
        -webkit-box-reflect:right;
        border-radius:0 40px 0 0
    }
    p{
        position:relative;
        background:#fe5f55;
        top:72;
        left:142
    }
    h2{
        position:absolute;
        top:160;
        left:150
    }
    h1{
        position:absolute;
        width:30;
        height:30;
        border-radius:50%;
        top:119;
        left:165;
        box-shadow:40px 0 #293462
    }
</style>
```
