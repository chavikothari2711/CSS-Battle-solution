# Block Battle

## [01 Corona Virus](https://cssbattle.dev/play/47)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/9cef0a59-38a3-4d1b-a43b-512d52685520)

```html

<div class="circle">
  <div class="dark"></div>
  <div class="dark"></div>
  <div class="dark"></div>
</div>
<div class="stripes"></div>
<div class="stripes"></div>
<div class="stripes"></div>
<style>
  body{
    background:#1A4341;
    display:grid;
    place-items:center;
  }
  .circle{
    width: 100px;
    height: 100px;
    border-radius:50%;
    background: #F3AC3C;
  }
  .dark{
    width:30px;
    height:30px;
    background:#998235;
    border-radius:50%;
    position:absolute;
    top:120px;
    left:170px;
  }
  .dark:nth-child(2){
    top:120px;
    left:220px;
    width:10px;
    height:10px;
  }
  .dark:nth-child(3){
    top:165px;
    width:20px;
    height:20px;
    left:190px;   
  }
  .stripes{
    width:10px;
    height:180px;
    background:#F3AC3C;
    border-radius:5px;
    top:50px;
    z-index:-1;
    position:absolute;
  }
  .stripes:nth-child(2){
    transform:rotate(60deg);
    top:54px;
    left:205px;
  }
  .stripes:nth-child(3){
    transform:rotate(120deg);
    top:65px;
    left:205px;
    
  }
</style>

```

## [02 Wash your hands](https://cssbattle.dev/play/48)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/767c4c28-c7a7-4bb1-a137-830aebf81539)

```html

<div class="big">
  <div class="inner"></div>
</div>
<div class="big"></div>
<style>
  body{
    background:#293462;
  }
  .big{
    width: 200px;
    height: 100px;
    border-radius:20px;
    background: #FE5F55;
    position:absolute;
    top:90px;
    left:100px;
    display:grid;
    place-items:center;
  }
  .inner{
    width:140px;
    height:40px;
    background:#A64942;
    border-radius:50px; 
  }
  .big:nth-child(2){
    z-index:-1;
    top:110px;
    background:#A64942;
  }
</style>

```
## [03 Stay at Home](https://cssbattle.dev/play/49)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/00261fc3-bfbb-4867-8252-8ab3a277db3f)

```html

<div class="roof"></div>
<div class="house">
  <div class="window"></div>
  <div class="door"></div>
</div>
<style>
  body{
    background:#6592CF;
  }
  .roof{
    width: 0; 
    height: 0; 
    border-left: 100px solid transparent;
    border-right: 100px solid transparent;  
    border-bottom: 100px solid #243D83;
    position:absolute;
    top:50px;
    left:100px;
  }
  .house{
    position:absolute;
    bottom:50px;
    width: 150px;
    height: 110px;
    border-radius:10px;
    left:125px;
    background: #243D83;
  }
  .window{
    background:#EEB850;
    margin:5px auto;
    width:100px;
    height:10px;
    border-radius:10px;
  }
  .door{
    background:#EEB850;
    margin:45px auto;
    width:50px;
    height:50px;
    border-radius:10px 10px 0px 0px;
  }
</style>

```

## [04 Use Hand Sanitizer](https://cssbattle.dev/play/50)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/e1ca3f55-8f3b-4d46-8e34-ce8ad7f76158)

```html

<div class="handle-1"></div>
<div class="handle-2"></div>
<div class="base-1"></div>
<div class="base-2"></div>
<div class="bottle">
  <div class="fill"></div>
  <div class="wave"></div>
  <div class="wave"></div>
</div>
<div class="drops"></div>
<div class="drops two"></div>
<style>
  body{
    background:#1A4341;
  }
  .bottle{
    position:absolute;
    bottom:50px;
    left:150px;
    width: 100px;
    height: 140px;
    background: #998235;
    border-radius:20px;
    overflow:hidden;
  }
  .fill{
    width:100px;
    height:60px;
    position:relative;
    background:#F3AC3C;
    bottom:0px;
  }
  .wave{
    width:51px;
    height:51px;
    border-radius:50%;
    position:absolute;
    background:#998235;
    top:30px;
  }
  .wave:nth-child(2){
    left:50px;
    background:#F3AC3C;
  }
  .base-1,.base-2,.handle-1,.handle-2{
    position:absolute;
    top:50px;
    left:150px;
    width:50px;
    height:50px;
    background:#F3AC3C;
  }
  .base-1{ 
    border-radius:10px;
    top:90px;
    left:175px;
  }
  .base-2{
    width:20px;
    top:70px;
    left:190px;
  }
  .handle-1{
    width:150px;
    height:20px;
    border-radius:20px;  
  }
  .handle-2{
    width:20px;
    height:40px;
    border-radius:10px;
    left:280px;
  }
  .drops{
    width:20px;
    height:20px;
    border-radius:50%;
    background:#998235;
    position:absolute;
    top:100px;
    right:100px;
  }
  .two{
    top:130px;
  }
</style>

```

## [05 Wear a mask](https://cssbattle.dev/play/51)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/ecfa0d48-cbb5-42e1-8ebd-b9fe3df0aa71)

```html

<div class="handle"></div>
<div class="handle"></div>
<div class="mask">
  <div class="stripe"></div>
  <div class="stripe"></div>
  <div class="circle"></div>
</div>
<style>
  body{
    background:#293462;
    display:grid;
    place-items:center;
  }
  .mask{
    width: 150px;
    height: 100px;
    background: #FFF1C1;
    border-radius:0px 0px 50px 50px;
  }
  .stripe{
    width:40px;
    height:10px;
    background:#FE5F55;
    border-radius:10px;
    left:145px;
    position:absolute;
    top:120px;
  }
  .stripe:nth-child(2){
    top:140px;
  }
  .circle{
    background:#FE5F55;
    position:absolute;
    width:40px;
    height:40px;
    border-radius:50%;
    top:140px;
    left:215px;
  }
  .handle{
    position:absolute;
    width:70px;
    height:60px;
    box-sizing:border-box;
    border:10px solid #FFF1C1;
    top:100px;
    left:65px;
    border-radius:50px 0px 0px 50px;
  }
  .handle:nth-child(2){
    transform:rotate(180deg);
    left:265px;
  }
</style>

```
## [06 Break the Chain](https://cssbattle.dev/play/52)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/b5396e3c-9ed6-4d78-bd72-33d15a3b90dd)

```html

<div></div>
<style>
  body{
    background: #6592CF;
  }
  div{
    width: 10px;
    height: 45px;
    background: #243d83;
    position: relative;
    top: 137px;
    left: 37px;
    box-shadow: 45px 0 0 0 #243d83, 90px 0 0 0 #243d83, 165px 0 0 0 #243d83, 210px
        0 0 0 #243d83, 255px 0 0 0 #243d83, 300px 0 0 0 #243d83;
  }
  div::before{
    content:"";
    position:absolute;
    background: #243d83;
    z-index:-1;
    top: -15px;
    left: -5px;
    width: 20px;
    height: 20px;
    border-radius:50%;
    box-shadow: 0 0 0 10px #eeb850, 45px 0 0 0 #243d83, 45px -10px 0 20px #eeb850, 90px 0 0 0 #243d83, 90px 0 0 10px #eeb850, 165px 0 0 0 #243d83, 210px 0 0 0 #243d83,255px 0 0 0 #243d83,300px 0 0 0 #243d83;
  }
  
</style>

```
