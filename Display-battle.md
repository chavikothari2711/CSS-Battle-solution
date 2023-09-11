# Dispaly Battle

## [01 Site Point Logo](https://cssbattle.dev/play/21)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/bdec184f-58f8-47fe-81ea-84d57143e869)

```html

<div class="yellow rectangle-1"></div>
<div class="yellow rectangle-2"></div>
<div class="blue rectangle-3"></div>
<div class="blue rectangle-4"></div>
<style>
  body{
    background: #222;
    margin:0;
  }
  div{
    position:absolute;
    width:30px;
    height:80px;
  }
  .yellow{
    background:#F2994A;
  }
  .blue{
    background:#2D9CDB;
  }
  
  .rectangle-1{
    top:110px;
    left:148px;
    transform:rotate(-45deg);
    border-radius:10px 0px 6px 0px;
  }
  .rectangle-2{
    transform:rotate(45deg);
    top:61px;
    left:163px;
  }
  .rectangle-3{
    top:109px;
    left:220px;
    transform:rotate(-45deg);
    border-radius:6px 0px 10px 0px;
  }
  .rectangle-4{
    transform:rotate(45deg);
    top:159px;
    left:205px;
  }
</style>

```

## [02 Cloud](https://cssbattle.dev/play/22)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/7ce35074-dbb2-40c1-bdce-6479c98462a7)

```html

<div></div>
<style>
  body{
    background:radial-gradient(circle at 230px 135px, #D86F45 50px,transparent 50px),radial-gradient(circle at 150px 165px,#D86F45 50px,#F5D6B4 50px);
  }
  div{
    width:180px;
    height:50px;
    border-radius:50px;
    background:#D86F45;
    margin:165px 112px;
  }
 </style>
```

## [03 Boxception](https://cssbattle.dev/play/23)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/af67bc7f-7d1d-48a5-9f80-22c2ebf2e41c)

```html

<h1></h1><h2></h2>
<style>
body{background:#F3AC3C;}
h1{
  width:100px;
  height:100px;
  background:#1A4341;
  margin:50px 92px;
  box-shadow:100px 0 #1A4341, 100px 100px #1A4341;
}
h2{
  width:50px;
  height:50px;
  background:#998235;
  margin:50px 92px;
  box-shadow:50px -50px #998235, 0 -50px #998235;
}
</style>
</style>


```

## [03 Switches](https://cssbattle.dev/play/24)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/b52371a7-dfb0-4423-adfc-560216f3a3ab)

```html

<div></div>
<style>
  body{background: #62306D;}
  div{
    width:100px;
    height:150px;
    background:#AA445F;
    border-radius:70px;
    margin:50px 72px;
    box-shadow:140px 50px #E38F66;
  }
  div::after{
    position:absolute;
    content:"";
    width:100px;
    height:100px;
    border-radius:50%;
    background:#F7EC7D;
    top:100px;
    box-shadow:140px 0 #F7EC7D;
  }  
</style>

```

## [04 Blossom](https://cssbattle.dev/play/25)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/64c9ac05-79e7-4481-a0ac-5004f654ccb4)

```html

<div class="leaf-one one"></div>
<div class="leaf-one two"></div>
<div class="leaf-two one"></div>
<div class="leaf-two two"></div>
<style>
  body{
    background: #998235;
  }
  .leaf-one{
    height:100px;
    width:80px;
    background:#1A4341;
    position:absolute;
    border-radius: 0 50px 0 50px;
  }
  .leaf-two{
    height:60px;
    width:80px;
    background:#F3AC3C;
    position:absolute;
    border-radius: 0 50px 0 50px;
  }
  .leaf-one.one{
    top:60px;
    left:110px;
  }
  .leaf-one.two{
    transform:rotateY(180deg);
    bottom:60px;
    right:110px;
  }
  .leaf-two.one{
    bottom:60px;
    left:110px;
  }
  .leaf-two.two{
    transform:rotateY(180deg);
    top:60px;
    right:110px;
  }
</style>

```

## [05 Smiley](https://cssbattle.dev/play/26)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/80967c8c-70e5-4de3-b93c-adeece578652)

```html

<div class="disc"></div>
<div class="disc"></div>
<div class="disc"></div>
<style>
   body{
    background: #6592CF;
  }
  .disc{
    width:80px;
    height:80px;
    border: 20px solid;
    border-radius:50%;
    transform:rotate(-45deg);
    border-color:#060F55 #060F55 #6592CF #6592CF;
    position:absolute;
    top:40px;
    left:40px
  }
  .disc:nth-child(2){
    left:240px;
  }
  .disc:nth-child(3){
    transform:rotate(135deg);
    top:140px;
    left:140px;
  }
</style>

```

## [06 Lock up](https://cssbattle.dev/play/27)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/c240cbf5-074f-4173-92a8-0309b1ecc505)

```html

<div class="circle">
  <div class="disc"></div>
</div>

<style>
  body{
    background: #E38F66;
    display:grid;
    place-items:center;
  }
  .circle{
    width:200px;
    height:200px;
    background:#AA445F;
    border-radius:50%;
    display:grid;
    place-items:center;
  }
  .disc{
    box-sizing:border-box;
    width:140px;
    height:140px;
    border-radius:50%;
    border: 30px solid;
    transform:rotate(45deg);
    border-color:#F7EC7D #AA445F;
  }
</style>

```

## [07 Cups & Balls](https://cssbattle.dev/play/28)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/e0d24110-84f2-41d3-95df-4719ca728f88)

```html

<div class="row">
  <div class="circle green"></div>
  <div class="shapes up yellow"></div>
  <div class="shapes up green"></div>
  <div class="circle yellow"></div>
</div>
<div class="row">
  <div class="shapes down  yellow"></div>
  <div class="circle green"></div>
  <div class="circle yellow"></div>
  <div class="shapes down green"></div>
</div>
<style>
  body{
    background: #1A4341;
    display:flex;
    flex-direction:column;
    gap:20px;
    margin:90px 50px;
  }
  .row{
    display:flex;
    flex-direction:row;
    gap:20px;
    justify-content:center;
    align-items:center;
  }
  .row div{
      width:50px;
      height:50px;
  }
  .green{
    background:#998235;
  }
  .yellow{
    background:#F3AC3C;
  }
  .circle{
    border-radius:50%;
  }
  .shapes{
    border-radius: 50% 50% 0% 0%;
  }
  .down{
    transform:rotate(180deg);
  }
</style>

```
