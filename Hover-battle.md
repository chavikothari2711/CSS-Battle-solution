# Hover battle

## [01 Arineo](https://cssbattle.dev/play/117)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/3b2d2bc3-f34b-498e-aa80-8c4ec54ec170)

```html

<div></div>
<style>
  body{
    background:radial-gradient(
      circle at center,
      #0088CA 11px,
      #FFFFFF 11px
    );
  }
  body::before,body::after{
    height:180px;
    width:44px;
    content:"";
    position:absolute;
    background:#2E2926;
    transform:skewX(-25deg);
    top:60px;
    left:134px;
  }
  body::after{
    transform:skewX(25deg);
    left:222px;
  }
  div::before,div::after{
    border-top:12px solid;
    border-bottom:12px solid;
    border-color:#fff;
    content:"";
    position:absolute;
    width:80px;
    height:27px;
    background:#0088CA;
    transform:skewY(45deg);
    top:138px;
    left:120px
  }
  div::after{
    transform:skewY(-45deg);
    width:120px;
    top:118px;
    z-index:1;
    left:200px
  }
</style>

```

## [02 Donket Kong](https://cssbattle.dev/play/118)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/975affa8-4137-443d-aa25-609ada669e5b)

```html

<div></div>
<style>
  body{
    background:#000000
  }
  body::before{
    content:"";
    background:#FFFFFF;
    width:20px;
    height:50px;
    position:absolute;
    top:100px;
    left:80px;
    box-shadow:220px 0 #fff, 220px 50px #fff, 110px 50px #fff;
  }
  div::after,div::before{
    content:"";
    position:absolute;
    height:20px;
    width:300px;
    background:#AF067C;
    border-radius:10px;
    top:90px;
    left:50px;
    box-shadow:0 100px #AF067C;
  }
  div::before{
    box-shadow:none;
    transform:rotate(-4deg);
    top:140px
  }
</style>

```

## [03 Pacman](https://cssbattle.dev/play/119)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/c68583c0-59e5-4bd4-9d93-89fbc29e6ceb)

```html

<div></div>
<style>
   body {
    background: radial-gradient(circle at center, #fff 5px, transparent 0),
      radial-gradient(circle at 170px 50%, #fff 5px, transparent 0),
      radial-gradient(circle at 230px 50%, #fff 5px, transparent 0),
      radial-gradient(circle at 90px 50%, #e0e246 30px, #000000 0);
  }
  div {
    width: 60px;
    height: 60px;
    background: #c74e4e;
    margin: 120px 272px;
    border-radius: 50% 50% 0 0;
  }
  div::before {
    content: "";
    position: absolute;
    width: 50px;
    height: 50px;
    background: #000;
    transform: translate(-182px, 5px) rotate(45deg);
    box-shadow: 155px -81px 0 0 #000, 170px -95px 0 0 #000,
      183px -108px 0 0 #000;
  }
  div::after {
    content: "";
    position: absolute;
    width: 50px;
    height: 50px;
  }
</style>

```

## [04 Tank](https://cssbattle.dev/play/120)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/681dcbb7-3d92-4711-aeaf-3084336fdb91)

```html

<div></div>
<style>
   body {
    outline: 20px solid #54c144;
    border: solid 40px #000;
    margin: 20;
    background: linear-gradient(to left, #c74e4e 100px, #000 0);
  }
  body::before,body::after {
    position: fixed;
    content: "";
  }
  body::before {
    background: #c74e4e;
    width: 80;
    height: 40;
    box-shadow: 120px 0 0 #c74e4e, 120px 80px 0 #c74e4e, 0px 80px 0 #c74e4e, 40px
        80px 0 #c74e4e;
  }
  div{
    width:40px;
    position:absolute;
    height:10px;
    background:#54C144;
    top:200px;
    box-shadow:10px 15px #54C144, 0 30px #54C144;
  }
  div::before,div::after{
    content:"";
    position:absolute;
  }
  div::before{
    background:#54C144;
    width:20px;
    height:30px;
    left:10px
  }
  div::after{
    width:10px;
    height:10px;
    background:#fff;
    left:60px;
    top:15px;
    box-shadow:20px 0 #fff;
  }
  </style>

```

## [05 Duck Hunt](https://cssbattle.dev/play/121)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/abd44bf6-6b17-4c14-a0cf-58e075bdb6c2)

```html

<div></div>
<style>
   body {
    background: linear-gradient(#1E92FF 0px, #1E92FF 180px,#69D10A 180px, #69D10A 220px, #6F6100 220px);
  }
  body::before{
    content:"";
    position:absolute;
    width:20px;
    height:70px;
    background:#441A0A;
    top:110px;
    left:50px
  }
  div{
    width:40px;
    height:40px;
    background:#69D10A;
    border-radius:50%;
    position:absolute;
    top:60px;
    left:40px;
    box-shadow:0 20px #69D10A, -20px 20px #69D10A, 20px 20px #69D10A, 270px 70px #69D10A, 270px 90px #69D10A;
  }
  </style>

```

## [06 Tetris](https://cssbattle.dev/play/122)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/7e2d09a2-6cbe-480b-b2f7-06dcef181eca)

```html

<div></div>
<style>
   body {
    background: #173889;
  }
  div{
    width:45px;
    height:45px;
    position:absolute;
    background:#F8DA37;
    bottom:0px;
    left:50px;
    box-shadow:0 -51px #EE4F63, 0 -102px #F8DA37, 0 -153px #F8DA37, 51px 0 #2CE1EA, 51px -51px #EE4F63, 51px -102px #F8DA37, 51px -153px #F8DA37, 102px 0 #2CE1EA, 102px -51px #EE4F63, 102px -102px #EE4F63, 153px 0 #2CE1EA, 153px -51px #2CE1EA, 153px -153px #EE4F63, 153px -204px #EE4F63, 204px 0 #B069F7, 204px -51px #B069F7, 204px -102px #B069F7, 204px -204px #EE4F63, 204px -255px #EE4F63, 255px 0 #2CE1EA, 255px -51px #B069F7;
  }
  </style>

```  

## [07 Snake](https://cssbattle.dev/play/123)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/e3bea1a9-98eb-4704-945e-227b77e160f2)

```html

<div></div>
<style>
   body {
    background: radial-gradient(circle at 100px 100px, #fff 10px, #c74e4e 0);
  }
  div{
    width:20px;
    height:20px;
    border-radius:5px;
    position:absolute;
    top:90px;
    left:190px;
    background:#E0E246;
    box-shadow:25px 0 #E0E246, 50px 0 #E0E246, 75px 0 #E0E246, 100px 0 #E0E246, 100px 25px #E0E246, 100px 50px #E0E246, 100px 75px #E0E246, 100px 100px #E0E246, 75px 100px #E0E246, 50px 100px #E0E246, 25px 100px #E0E246, 0 100px #E0E246, -25px 100px #E0E246, -50px 100px #E0E246, -75px 100px #E0E246, -100px 100px #E0E246
  }
  </style>

```

## [08 Space Invaders](https://cssbattle.dev/play/124)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/f6576c25-fd5b-4e7a-a7c8-4e7057dfd82d)


```html

<style>
   body {
    background: linear-gradient(-135deg, #071945 339px, transparent 100px),
      linear-gradient(135deg, #071945 339px, #2ce1ea 100px);
  }
  body::before{
    content:"";
    position:absolute;
    width:50px;
    height:10px;
    background:#B069F7;
    top:40px;
    left:40px;
    box-shadow: 90px 0 #B069F7, 180px 0 #B069F7, 270px 0 #B069F7, 0 50px #F8DA37, 180px 50px #F8DA37,270px 50px #F8DA37; 
  }
  body::after{
    content:"";
    position:absolute;
    width:10px;
    height:10px;
    top:50px;
    left:30px;
    background:#B069F7;
    box-shadow:60px 0 #B069F7, 90px 0 #B069F7, 150px 0 #B069F7,180px 0 #B069F7, 240px 0 #B069F7, 270px 0 #B069F7, 330px 0 #B069F7, 0 50px #F8DA37, 60px 50px #F8DA37, 180px 50px #F8DA37, 240px 50px #F8DA37, 270px 50px #F8DA37, 330px 50px #F8DA37, 165px 160px #2CE1EA, 165px 190px #2CE1EA, 165px 219.5px  #2CE1EA, 165px 225px #2CE1EA;
  }
  </style>

```

