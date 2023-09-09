# Pilot battle

## [01 Simply Square](https://cssbattle.dev/play/1)

![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/05ecb72c-feb1-4a65-9cea-cd73b27cc6e4)

```html
<div></div>
<style>
  *{
    margin:0;
   background:#5d3a3a;   
  }
  div {
    width: 200px;
    height: 200px;
    background: #b5e0ba;
  }
</style>
```

## [02 Carrom](https://cssbattle.dev/play/2)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/310b49b5-5958-497a-8035-a9139ff998a1)

```html

<div></div>
<style>
  body{background: #62374e;}
  div{
    position:absolute;
    width: 50px;
    height: 50px;
    background: #fdc57b;
    top:50px;
    left:50px;
    box-shadow:250px 0 #fdc57b, 0 150px #fdc57b, 250px 150px #fdc57b; 
  } 
</style>

```

## [03 Push Button](https://cssbattle.dev/play/3)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/9e65ad70-65eb-43ad-81bc-63876db1205e)

```html

<div class="rect"><div class="cir"></div></div>
<style>
  body{
    display: grid;
    place-items: center;
    background:#6592CF;
  }
  .rect{
    display:grid;
    place-items:center;
    width: 300px;
    height: 150px;
    background: #243D83;
  }
  .cir{
    width: 50px;
    height: 50px;
    background: #eeb850;
    border-radius: 50%;
    border: solid 50px #243d83;
    z-index: 1;
    box-shadow:0 0 0 50px #6592CF; 
  }
</style>

```

## [04 Ups and Downs](https://cssbattle.dev/play/4)

![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/96715b53-fa85-4ca1-bd1d-ce16be3adc77)

```html

<div></div><div></div>
<style>
  body{background:#62306D;}
  div{
    width: 100px;
    height: 100px;
    background: #F7EC7D;
    position:absolute;
    border-radius:50px 50px 0 0;
    top:50px;
    left:150px;
  }
  div:nth-child(2){
    border-radius:0 0 50px 50px;
    top:150px;
    left:50px;
    box-shadow:200px 0 #F7EC7D
  }
</style>

```

## [05 Acid Rain](https://cssbattle.dev/play/5)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/f13d9cb0-3fcd-41dc-82c9-32960b93b8fb)

```html

<div class="leaf"></div>
<div class="leaf-3">
<style>
  body{
    background: #0B2429;
  }
  div{
    width: 120px;
    height: 120px;
    background:#F3AC3C;
    position:absolute;
  }
  .leaf{
    bottom:30px;
    left:80px;
    border-radius:50% 0px 50% 50%;
    box-shadow: 60px -60px #998235;
  }
  .leaf-3{
    border-radius:50%;
    right:80px;
    top:30px;
    z-index:-2;
  }
</style>

```

## [06 Missing Slice](https://cssbattle.dev/play/6)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/3f223ab4-a9f5-4910-abd8-1a09dfd7ddfe)

```html

<div></div>
<style>
  body {
    background: #e3516e;
    display: grid;
    place-items: center;
  }
  div{
    box-sizing:border-box;
    border-radius:50%;
    border:100px solid;
    border-color:#51B5A9 #FADE8B #E3516E #F7F3D7;
    transform:rotate(-45deg)
  }
</style>

```

## [07 Leaf-trail](https://cssbattle.dev/play/7)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/c7c16f44-6dc2-450c-b71e-a0749201c631)

```html

<div></div>
<style>
  body{
    background:#0B2429;
  }
  div {
    position:absolute;
    top:75px;
    left:175px;
    width: 150px;
    height: 150px;
    background: #F3AC3C;
    border-radius:66% 0%;
    box-shadow:-50px 0 #998235, -100px 0 #1A4341;
  }
</style>

```

## [08 Forking crazy](https://cssbattle.dev/play/8)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/fe212c7f-0592-4353-9673-7a4e1125a9fb)

```html

<div class="stem"></div><div class="fork"></div><p></p><h1></h1>
<style>
  body{
    background:#6592CF;
  }
  .stem,.fork,h1{
    position:absolute;
    left:130px;
    height:100px;
  }
  .stem{
    background:#060F55;
    width:20px;
    bottom:0px;
    z-index:-1;
    left:190px
  }
  .fork{
    background:#060F55;
    bottom:50px;
    width: 140px;
    z-index:1;
    border-radius:0% 0% 69px 69px;
  }
  p,h1{
    width:20px;
    height:100px;
    background:#060F55;
    border-radius:20px 20px 0 0;
    margin:50px 122px;
    box-shadow:40px 0 #060F55, 80px 0 #060F55, 120px 0 #060F55
  }
  h1{
    z-index:2;
    transform:rotate(180deg);
    top:10px;
    background:#6592CF;
    left:108px;
    box-shadow:40px 0 #6592CF, 80px 0 #6592CF
  }
</style>

```

## [09 Tesseract](https://cssbattle.dev/play/9)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/c90b8e7b-36cd-4b6f-867d-2e4738f644c8)
```html

<div></div>
<style>
  body{
    background:linear-gradient(#222730 25%,#4CAAB3 2%, #4CAAB3 75%, #222730 50%);
  }
 div{
   width:150px;
   height:150px;
   transform:rotate(45deg);
   background:#4CAAB3;
   margin:75px auto;
   box-shadow:0 0 0 50px #222730;
 }
  div::after{
    content:"";
    position:absolute;
    width:50px;
    height:50px;
    border-radius:50%;
    background:#393E46;
    top:50px;
    left:50px;
  }
</style>

```
## [10 Cloaked Spirits](https://cssbattle.dev/play/10)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/11a2a360-662d-4f38-96c3-3e7eec48decd)

```html
<div></div>
<p></p>
<style>
  body{background:#62306D}
  div{
    width:100.5px;
    height:200px;
    background:#F7EC7D;
    margin:100px 142px;
    box-shadow:-100px 100px #F7EC7D, 100px 100px #F7EC7D;
  }
  p{
    width:60px;
    height:60px;
    border-radius:50%;
    background:#AA445F;
    margin:-330px auto;
    box-shadow:0 0 0 20px #E38F66, -100px 100px #E38F66, 100px 100px #E38F66, -100px 100px 0 20px #AA445F, 100px 100px 0 20px #AA445F;
  }
</style>

```

## [11 Eye of Sauron](https://cssbattle.dev/play/11)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/64e6f076-4762-47a3-92f8-2208544c23b0)

```html

<div class="disc"></div>
<div class="half"></div>
<div class="half right"></div>
<style>
  body{
    display:grid;
    place-items:center;
    background:radial-gradient(circle,#84271C 25px, #191210 10px);
  }
  .circle{
    width:50px;
    height:50px;
    background:#84271C;
    border-radius:50%;
  }
  .disc{
    width:100px;
    height:100px;
    border: 20.5px solid #ECA03D;
    border-radius:50%;
  }
  .half{
    position: absolute;
    width:60px;
    height:60px;
    border-radius:50%;
    border: 20px solid;
    left:50px;
    transform:rotate(-45deg);
    border-color:  transparent transparent #ECA03D #ECA03D;
  }
  .right{
    left:250px;
    transform:rotate(135deg);
  }  
</style>

```

## [12 wiggly Moustache](https://cssbattle.dev/play/12)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/c050e61e-7740-4778-aaa2-93313fc56757)

```html

<div class="disc"></div>
<div class="disc"></div>
<div class="disc"></div>
<style>
  body {
    background: #f5d6b4;
    position: relative;
    margin: 0;
  }
  * {
    box-sizing: border-box;
  }
  .disc {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    clip-path: polygon(0 0, 100% 0, 100% 50%, 0 50%);
    border: solid 20px #d86f45;
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
  }
  .disc:nth-child(1) {
    left: 70px;
    clip-path: polygon(0% 50%, 100% 50%, 100% 100%, 0% 100%);
  }
  .disc:nth-child(2) {
    left: 150px;
  }
  .disc:nth-child(3) {
    left: 230px;
    clip-path: polygon(0% 50%, 100% 50%, 100% 100%, 0% 100%);
  }
  body::after,
  body::before {
    content: "";
    width: 20px;
    height: 20px;
    background: #d86f45;
    position: absolute;
    border-radius: 50%;
    left: 70px;
    top: 50%;
    z-index: 1;
    transform: translateY(-50%);
  }
  body::before {
    left: 310px;
  }
</style>

```
