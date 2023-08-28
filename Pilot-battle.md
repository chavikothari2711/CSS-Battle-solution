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

<div class="top-left-square"></div>
<div class="top-right-square"></div>
<div class="bottom-left-square"></div>
<div class="bottom-right-square"></div>
<style>
  *{
    margin:0;
    background: #62374e;
  }
  div{
    position:absolute;
    width: 50px;
    height: 50px;
    background: #fdc57b;
  }
  .top-left-square{
    left:50px;
    top:50px;    
  }
  .top-right-square{
    right:50px;
    top:50px;    
  }
  .bottom-left-square{
    left:50px;
    bottom:50px;    
  }
  .bottom-right-square{
    right:50px;
    bottom:50px;    
  }
</style>

```

## [03 Push Button](https://cssbattle.dev/play/3)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/9e65ad70-65eb-43ad-81bc-63876db1205e)

```html

<div class="rectange">
  <div class="circle"></div>
  <div class="circle-2"></div>
</div>

<style>
  body{
    display: grid;
    place-items: center;
    background:#6592CF;
  }
  .rectange {
    display:grid;
    place-items:center;
    width: 300px;
    height: 150px;
    background: #243D83;
  }
  .circle{
    width: 50px;
    height: 50px;
    background: #eeb850;
    border-radius: 50%;
    border: solid 50px #243d83;
    z-index: 1;
  }
  .circle-2{
    position: absolute;
    width: 50px;
    height: 50px;
    background: transparent;
    border-radius: 50%;
    border: solid 100px #6592cf;
  }
</style>

```

## [04 Ups and Downs](https://cssbattle.dev/play/4)

![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/96715b53-fa85-4ca1-bd1d-ce16be3adc77)

```html

<div class="top-middle"></div>
<div class="bottom-left"></div>
<div class="bottom-right"></div>
<style>
  body{
    background:#62306D;
  }
  div{
    width: 100px;
    height: 100px;
    background: #F7EC7D;
    position:absolute;
  }
  .top-middle{
    top:50px;
    left:150px;
    border-radius: 50px 50px 0px 0px;
  }
  .bottom-left{
    bottom:50px;
    left:50px;
    border-radius: 0px 0px 50px 50px;
  }
  .bottom-right{
    bottom:50px;
    right:50px;
    border-radius: 0px 0px 50px 50px;
  }
</style>

```

## [05 Acid Rain](https://cssbattle.dev/play/5)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/f13d9cb0-3fcd-41dc-82c9-32960b93b8fb)

```html

<div class="leaf-1"></div>
<div class="leaf-2"></div>
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
  .leaf-1{
    bottom:30px;
    left:80px;
    border-radius:50% 0px 50% 50%;
  }
  .leaf-2{
    border-radius:50% 0px 50%;
    left:140px;
    top:90px;
    background:#998235;
    z-index:-1;
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

<div class="circle">
  <div class="quad-1"></div>
  <div class="quad-2"></div>
  <div class="quad-3"></div>
</div>
<style>
  body {
    background: #e3516e;
    display: grid;
    place-items: center;
  }
  .circle{
    width:200px;
    height:200px;
    border-radius:50%;
    overflow:hidden;
    display:flex;
    flex-wrap:wrap;
  }
  .quad-1{
    width:100px;
    height:100px;
    background:#51B5A9;
  }
  .quad-2{
    width:100px;
    height:100px;
    background:#FADE8B;
  }
  .quad-3{
    width:100px;
    height:100px;
    background:#F7F3D7;
  }
</style>

```

## [07 Leaf-trail](https://cssbattle.dev/play/7)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/c7c16f44-6dc2-450c-b71e-a0749201c631)

```html

<div class="leaf-1"></div>
<div class="leaf-2"></div>
<div class="leaf-3"></div>
<style>
  body{
    background:#0B2429;
  }
  div {
    position:absolute;
    top:75px;
    width: 150px;
    height: 150px;
    background: #1A4341;
    border-radius:69% 0%;
  }
  .leaf-1{
    left:75px;
    z-index:-2;
  }
  .leaf-2{
    left:125px;
    z-index:-1;
    background:#998235;
  }
  .leaf-3{
    background:#F3AC3C;
    right:75px;
    z-index:1;
  }
</style>

```

## [08 Forking crazy](https://cssbattle.dev/play/8)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/fe212c7f-0592-4353-9673-7a4e1125a9fb)

```html

<div class="stem"></div>
<div class="fork"></div>
<div class="stick">
  <div class="p"></div>
  <div class="p"></div>
  <div class="p"></div>
  <div class="p"></div>
  <div class="p"></div>
  <div class="p"></div>
  <div class="p"></div>
</div>
<style>
  body{
    background:#6592CF;
  }
  .stem,.fork,.stick{
    position:absolute;
    left:130px;
  }
  .stem{
    background:#060F55;
    width:20px;
    height:100px;
    bottom:0px;
    z-index:-1;
    left:190px
  }
  .fork{
    background:#060F55;
    bottom:50px;
    width: 140px;
    height: 100px;
    z-index:1;
    border-radius:0% 0% 69px 69px;
  }
  .stick{
    display:flex;
    top:50px;
    z-index:2;
  }
  .p:nth-child(2n+1) {
    width: 20px;
    height: 110px;
    background: #060F55;
    border-radius: 12px 12px 0px 0px;
  }
  .p:nth-child(2n) {
    width: 20px;
    height: 110px;
    background: #6592CF;
    border-radius: 0px 0px 12px 12px;
  }
  
</style>

```
