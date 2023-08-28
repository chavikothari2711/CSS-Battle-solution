# Visibility Battle

## [01 Totally Triangle](https://cssbattle.dev/play/13)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/da392bf8-cbb1-4d4b-a0cc-9b6f0edc36d0)

```html

<div></div>
<style>
  body{
    background:#0B2429;
  }
  div {
    position:absolute;
    left:-100px;
    top:-100px;    
    transform:rotate(45deg);
    width: 200px;
    height: 200px;
    background: #F3AC3C;
  }
</style>

```

## [02 web maker logo](https://cssbattle.dev/play/14)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/de0b6ef2-bab3-4251-8ead-86152cb28028)

```html

<div class="elem">
  <div class="triangle"></div>
</div>
<div class="elem">
  <div class="triangle"></div>
</div>
<style>
  body {
    background: #f2f2b6;
  }
  .elem {
    position: relative;
    top: 77px;
    left: 20px;
  }
  .triangle {
    width: 150px;
    height: 150px;
    background: #ff6d00;
    clip-path: polygon(0 0, 150px 0, 75px 130px);
    position: absolute;
    z-index: 1;
    left: 2rem;
  }
  .elem::after {
    position: absolute;
    content: "";
    width: 150px;
    height: 150px;
    background: #fd4602;
    clip-path: polygon(0 0, 150px 0, 75px 130px);
    left: 13.5%;
  }
  .elem:nth-child(2) {
    position: relative;
    top: 77px;
    left: 150px;
    transform: rotate(180deg);
    transform-origin: 107px 65px;
  }
  .elem:nth-child(2) .triangle {
    z-index: -1;
  }
</style>

```

## [03 Overlap](https://cssbattle.dev/play/15)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/8997448f-79aa-4960-b32d-68adef8c554e)

```html

<div class="circle-1"></div>
<div class="leaf"></div>
<div class="circle-2"></div>
<style>
  body{
    background: #09042A;
    justify-content:center;
    align-items:center;
  }
  .circle-1,.circle-2{
    position:absolute;
    background:#7B3F61;
    width:150px;
    height:150px;
    border-radius:50%;
    top:75px;
    left:75px;
  }
  .circle-2{
    left:175px;
    background:#E78481;
  }
  .leaf{
    position:absolute;
    z-index:10;
    top:110px;
    left:160px;
    border-radius:0 95%;
    transform:rotate(45deg);
    background:#09042A;
    width:80px;
    height:80px;
  }
</style>

```

## [04 Eye of the tiger](https://cssbattle.dev/play/16)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/0e2e638c-a359-45ac-b4e1-36c1e0b6339b)

```html

<div class="leaf"></div>
<div class="circle"></div>
<div class="eye"></div>
<style>
  body {
    background:#0B2429;
    display:grid;
    place-items:center;
  }
  .leaf{
    width:200px;
    height:200px;
    transform:rotate(135deg);
    background:#998235;
    border-radius:0 50%;
  }
  .circle{
    box-sizing:border-box; 
    width:180px;
    height:180px;
    position:absolute;
    background:#F3AC3C;
    border-radius:50%;
    border: 20px solid #0B2429;
    z-index:1;
  }
  .eye{
    background:#0B2429;
    width:50px;
    height:50px;
    border-radius:50%;
    position:absolute;
    z-index:2;
  }
</style>

```

## [05 Fidget Spinner](https://cssbattle.dev/play/17)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/e0e3aa9b-a514-4ace-8dd6-5e0f26e34308)

```html

<div class="bar"></div>
<div class="circle top light"></div>
<div class="circle left dark"></div>
<div class="circle bottom light"></div>
<div class="circle right dark"></div>
<style>
  body {
    background: #09042a;
    display: grid;
    place-items: center;
    position: relative;
  }
  .bar {
    background: #e78481;
    width: 160px;
    height: 55px;
  }
  .circle {
    width: 60px;
    height: 60px;
    position: absolute;
    border-radius: 50%;
  }
  .light {
    background: #f5bb9c;
    border: solid 10px #09042a;
  }
  .dark {
    background: #09042a;
    border: solid 10px #e78481;
  }
  .top {
    top: 49px;
  }
  .left {
    left: 92px;
  }
  .bottom {
    bottom: 49px;
  }
  .right {
    right: 92px;
  }
</style>

```
## [06 Matrix](https://cssbattle.dev/play/18)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/14552a34-a0a6-49e3-8ef1-9a40a4c5d926)

```html

<div class="quad"></div>
<div class="quad other"></div>
<div class="quad"></div>
<div class="quad other"></div>
<div class="quad other"></div>
<div class="quad"></div>
<div class="quad other"></div>
<div class="quad"></div>
<div class="quad"></div>
<div class="quad other"></div>
<div class="quad"></div>
<div class="quad other"></div>
<style>
  body{
    background:#5C434C;
    display:flex;
    flex-wrap:wrap;
    gap:20px;
    padding:10px;
    margin: 0;
  }
  .quad{
    width: 80px;
    height: 80px;
    border-radius: 80px 0 0 0;
    background: #F09462;
  }
  .other{
    background: #f5d6b4;
  }
</style>

```
