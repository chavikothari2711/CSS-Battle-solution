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
