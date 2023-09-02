# Clip Battle

## [01 Push Owl](https://cssbattle.dev/play/69)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/e6f831dc-d407-410b-ba98-6d5dafd1f89b)

```html

<div></div>
<style>
  body {
    background: linear-gradient(transparent 140px, #191919 140px),
      radial-gradient(
        circle at 146px 140px,
        #191919 6px,
        #e08027 6px,
        #e08027 15px,
        transparent 15px
      ), radial-gradient(circle at 254px 140px, #191919 6px, #e08027 6px, #e08027
          15px, #191919 15px);
  }
  div {
    position: relative;
    z-index: 1;
  }
  body::before {
    position: absolute;
    content: "";
    width: 40px;
    height: 50px;
    background: #e08027;
    top: 166px;
    left: 176px;
    z-index: -1;
    transform: rotate(-45deg);
  }
  div::before,
  div::after {
    position: absolute;
    content: "";
    margin: 76px auto;
    width: 115px;
    height: 115px;
    background: radial-gradient(circle, transparent 45px, #e08027 40px);
    border-radius: 0px 50% 50% 50%;
    left: 81px;
    top: -7px;
  }
  div::after {
    top: -17px;
    left: 179px;
    transform: rotate(90deg);
    border: solid 10px #191919;
    z-index: 2;
  }
</style>

```

## [02 Froggy](https://cssbattle.dev/play/70)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/2c2e5dda-3f67-4831-bc9c-faa114c0d4fa)

```html

<div></div>
<style>
  body {
    background:#293462;
  }
  body::after ,body::before{
    position: absolute;
    content: "";
    z-index: 1;
    background:#293462;
    width: 10px;
    height: 10px;
    border-radius: 50%;
    border: 11px solid #FFF1C1; 
    outline: 10px solid #FE5F55;
    top: 94px;
    left: 150px;
  }
  body::before{
    left:220px;
    box-shadow:-45px 55px 0 -10.5px #293462, -25px 55px 0 -10.5px #293462;
  }
  div{
    width: 150px;
    height: 100px;
    background: #a64942;
    border-radius: 50px;
    position: relative;
    margin: 110px auto;
    overflow: hidden;
  }
  div::after {
    position: absolute;
    content: "";
    background: #fe5f55;
    width: 435px;
    height: 435px;
    border-radius: 50%;
    top: -365px;
    left: -142px;
  }
</style>

```

## [03 Elephant](https://cssbattle.dev/play/71)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/719afe1c-d34c-4988-b307-f74f8a17ac40)

```html

<div></div>
<p></p>
  <style>
    body {
      background: #998235;
    }
    div {
      width: 180px;
      height: 180px;
      border-radius: 50%;
      margin: 60px auto;
      background: #1a4341;
      position: relative;
    }
    div::before,
    div::after,
    body::before,
    body::after,
    p::before,
    p::after {
      content: "";
      position: absolute;
    }
    div::before,
    div::after {
      width: 80px;
      height: 180px;
      background: #0b2429;
      border-radius: 50%;
      z-index: -1;
      left: -60px;
      box-shadow: inset 14px 0 0px 2px #1a4341;
    }
    div::after {
      left: 160px;
      transform: rotate(180deg);
    }
    body::before,
    body::after {
      width: 20px;
      height: 10px;
      background: #0b2429;
      border: solid 10px #998235;
      border-radius: 0px 0px 20px 20px;
      border-top: 0;
      top: 50%;
      left: 150px;
      z-index: 1;
    }
    body::after {
      left: 210px;
    }
    p::before {
      width: 40px;
      height: 120px;
      background: #0b2429;
      border-radius: 40px 40px 0 0;
      bottom: 0px;
      left: 180px;
      z-index: 1;
    }
    p::after {
      box-sizing: border-box;
      width: 120px;
      height: 60px;
      border: solid 20px #ffffff;
      border-bottom: none;
      border-radius: 60px 60px 0 0;
      bottom: 50px;
      left: 140px;
    }
  </style>

```

## [04 Sheep](https://cssbattle.dev/play/72)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/16c379a5-1093-4b57-8200-6612fa423ce4)

```html

<div></div>
<style>
  body {
    background: radial-gradient(
        circle at 190px 135px,
        #6592cf 5px,
        transparent 5px
      ), radial-gradient(circle at 210px 135px, #6592cf 5px, #243d83 5px);
    position: relative;
  }
  div {
    width: 60px;
    height: 75px;
    margin: 80px auto;
    border: solid 20px #6592cf;
    border-radius: 50px;
  }
  div::before,
  div::after,
  body::before,
  body::after {
    position: absolute;
    content: "";
    width: 60px;
    height: 50px;
    background: #6592cf;
    border-radius: 55%;
    top: 0;
    left: 0;
    z-index: 1;
  }
  div::before {
    top: -15px;
    left: 162px;
    box-shadow: 0 120px 0 0 #6592cf;
  }
  div::after {
    transform: rotate(45deg);
    top: 5px;
    left: 202px;
    box-shadow: 0 113px 0 0 #6592cf;
  }
  body::before {
    transform: rotate(90deg);
    top: 45px;
    left: 222px;
    box-shadow: 0 120px 0 0 #6592cf;
  }
  body::after {
    transform: rotate(-45deg);
    top: 5px;
    left: 122px;
    box-shadow: 0 113px 0 0 #6592cf;
  }
</style>

```

## [05 Happy Tiger](https://cssbattle.dev/play/73)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/80d46601-3d92-4c47-a0c5-c466ea26a25f)

```html

<div></div>
<p></p>
<style>
  body {
    background: radial-gradient(
        circle at 145px 95px,
        #1a4341 20px,
        #998235 20px,
        #998235 30px,
        transparent 30px
      ), radial-gradient(circle at 255px 95px, #1a4341 20px, #998235 20px, #998235
          30px, #f3ac3c 30px);
  }
  div::before,
  div::after,
  body::before,
  body::after,
  p,
  p::before,
  p::after {
    position: absolute;
    content: "";
  }
  div {
    width: 150px;
    height: 150px;
    margin: 75px auto;
    border-radius: 75px 75px 60px 60px;
    background: #998235;
    overflow: hidden;
    position: relative;
  }
  div::before {
    width: 100px;
    height: 40px;
    background: #ffffff;
    top: 95px;
    left: 25px;
    border-radius: 15px 15px 40px 40px;
  }
  div::after {
    width: 50px;
    height: 50px;
    background: #1a4341;
    transform: rotate(45deg);
    top: -35px;
    left: 50px;
  }
  body::before {
    width: 20px;
    height: 20px;
    background: #1a4341;
    border-radius: 50%;
    top: 135px;
    left: 150px;
    box-shadow: 80px 0 0 0px #1a4341;
    z-index: 1;
  }
  p::before,
  p::after {
    top: 0;
    left: 0;
    width: 20px;
    height: 50px;
    background: transparent;
    border: solid 10px #1a4341;
    border-radius: 50px;
    top: -30px;
    left: 0px;
    clip-path: polygon(0 50px, 100% 50px, 100% 100%, 0 100%);
  }
  p::after {
    left: -29.5px;
  }
  p {
    width: 10px;
    height: 33px;
    background: #1a4341;
    top: 144px;
    left: 195px;
  }
</style>

```

## [06 Danger Noodle](https://cssbattle.dev/play/74)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/37ee904b-ce5c-403e-8ba5-6e60a3627a10)

```html

<div></div>
<p></p>
<p></p>
<span></span>
<style>
  body {
    background: #191919;
  }
  div {
    width: 30px;
    height: 180px;
    margin: 60px 27px;
    border-radius: 50px;
    clip-path: polygon(
      -20px 10px,
      -20px 70px,
      0px 70px,
      0px 165px,
      -20px 165px,
      205px 165px,
      205px 110px,
      155px 110px,
      155px 10px
    );
    box-shadow: 50px 0 0 0px #191919, 50px 0 0 5px #e08027,
      50px 0 0 15px #191919, 50px 0 0 20px #e08027, 100px 0 0 0px #191919, 100px
        0 0 5px #e08027, 100px 0 0 15px #191919, 100px 0 0 20px #e08027,
      150px 0 0 0px #191919, 150px 0 0 5px #e08027, 150px 0 0 15px #191919, 150px
        0 0 20px #e08027, 200px 100px 0 0px #191919, 200px 100px 0 5px #e08027,
      200px 100px 0 15px #191919, 200px 100px 0 20px #e08027, 0 0 0 5px #e08027,
      0 0 0 15px #191919, 0 0 0 20px #e08027;
  }
  body::before,
  body::after,
  p::before,
  p::after,
  div::before {
    position: absolute;
    content: "";
    width: 30px;
    height: 15px;
    border: solid 5px #e08027;
    border-radius: 30px 30px 00 0;
    border-bottom: 0;
    top: 55px;
    left: 30px;
    box-shadow: 0 0 0 10px #191919, 0 0 0 15px #e08027;
    clip-path: polygon(-50px -30px, 100px -30px, 100px 20px, -50px 20px);
  }
  body::after {
    left: 130px;
  }
  p::before,
  p::after {
    top: 225px;
    transform: rotate(180deg);
    left: 80px;
  }
  p::after {
    left: 180px;
  }
  p:nth-child(2)::before {
    top: 125px;
    left: -20px;
  }
  p:nth-child(2)::after {
    width: 50px;
    top: 155px;
    left: 230px;
    transform: rotate(0deg);
  }
  span {
    display: inline-block;
    width: 50px;
    height: 30px;
    background: radial-gradient(
        circle at 35px 7px,
        #191919 5px,
        transparent 5px
      ), radial-gradient(circle at 35px 23px, #191919 5px, #e08027 5px);
    position: absolute;
    top: 135px;
    right: 85px;
    border-radius: 14px 20px 20px 14px;
    box-shadow: 0 12px 0 0 #191919;
  }

</style>

```

## [07 Hippo](https://cssbattle.dev/play/75)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/5e976234-0190-4a69-8c23-1b8e45f709ec)

```html

<div></div>
<p></p>
<style>
  body {
    background: #191919;
  }
  div {
    width: 130px;
    height: 145px;
    background: radial-gradient(
        circle at 30px 55px,
        #000000 5px,
        transparent 5px
      ), radial-gradient(circle at 100px 55px, #000000 5px, #fe5f55 5px);
    margin: 75px auto;
    border-radius: 60px;
    position: relative;
  }
  div::before,
  div::after,
  body::before,
  body::after,
  p::before,
  p::after,
  p {
    position: absolute;
    content: "";
  }
  div::before,
  div::after {
    z-index: -1;
    width: 11px;
    height: 30px;
    background: #000000;
    border: solid 5px #fe5f55;
    border-radius: 50%;
    top: -6px;
    left: 18px;
    transform: rotate(-45deg);
  }
  div::after {
    transform: rotate(45deg);
    left: 92px;
  }
  p {
    width: 150px;
    height: 100px;
    background: #a64942;
    top: 129px;
    left: 125px;
    border-radius: 55px 55px 45px 45px;
  }
  p::before,
  p::after {
    width: 30px;
    height: 20px;
    border-radius: 50%;
    background: #000000;
    top: 25px;
    left: 20px;
    transform: rotate(-45deg);
  }
  p::after {
    transform: rotate(45deg);
    left: 100px;
  }
</style>

```

## [08 Beeee](https://cssbattle.dev/play/76)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/cacdd8b9-a781-4d3f-a2b1-92284c9572fc)

```html

<div></div>
<style>
  body {
    background: #998235;
  }
  body::before,body::after{
    background:#ffffff;
    width:75px;
    height:75px;
    content:"";
    position:absolute;
    border-radius:50px 50px 0px 50px;
    top:75px;
    left:125px;
  }
  body::after{
    transform:rotate(90deg);
    left:200px;
  }
  div{
    position:relative;
    overflow:hidden;
    width:150px;
    height:75px;
    background:#EFF33C;
    border-radius:50px;
    top:142px;
    left:117px;
  }
  div::before{
    content:"";
    position:absolute;
    background:#191919;
    height:75px;
    width:25px;
    box-shadow: 35px 0 #191919, 70px 0 #191919;
  }
  div::after{
    content:"";
    position:absolute;
    background:#191919;
    width:15px;
    height:15px;
    border-radius:50%;
    right:20px;
    top:20px;
  }
</style>

```
