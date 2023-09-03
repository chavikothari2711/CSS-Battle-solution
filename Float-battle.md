# Float Battle

## [01 Sharingan](https://cssbattle.dev/play/101)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/1773f5c8-9701-449f-ad99-668ee5b5562c)

```html

<div></div>
<style>
  body{
    background:#161616;
  }
  div {
    width: 190px;
    height: 190px;
    border-radius:50%;
    border:5px solid #000000;
    margin:50px auto;
    background: #A22015;
    position:relative;
    overflow:hidden;
  }
  div::before{
    position: absolute;
    content: "";
    width: 50px;
    height: 50px;
    background: #000000;
    border-radius: 50%;
    top: 70px;
    left: 70px;
    box-shadow:0 0 0 10px #E96A23, 0 0 0 25px #000000, 74px -42px 0 10px #A22015, 74px -42px 0 25px #000000, -74px -42px 0 10px #A22015,-74px -42px 0 25px #000000,0 85px 0 10px #A22015,0 85px 0 25px #000000;
</style>

```

## [02 One Piece](https://cssbattle.dev/play/102)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/ed88c721-b3c8-4059-8527-e87d369f25c1)

```html

<div></div>
<p></p>
<style>
  body{
    background:#000000;
  }
  div{
    background:#ffffff;
    position:relative;
    width:150px;
    height:100px;
    border-radius:50px;
    top:102px;
    left:117px;
  }
  div::before,div::after{
    width:50px;
    height:40px;
    background:#000000;
    position:absolute;
    content:"";
    top:30px;
    left:20px;
    transform:rotate(-30deg);
    border-radius:50%;
  }
  div::after{
    transform:rotate(30deg);
    left:80px
  }
  body::before,body::after{
    width:25px;
    height:25px;
    background:#ffffff;
    position:absolute;
    content:"";
  }
  body::before{
    border-radius:50%;
    top:95px;
    left:94px;
    box-shadow:11px -11px #ffffff, 176px -11px #ffffff, 186px 0 #ffffff, 0 105px #ffffff, 11px 115px #ffffff, 176px 115px #ffffff, 186px 105px #ffffff;
  }
  body::after{
    width:15px;
    height:20px;
    top:220px;
    left:173px;
    box-shadow:20px 0 #ffffff, 40px 0 #ffffff;
  }
  p::before,p::after{
    content:"";
    position:absolute;
    width:24px;
    height:18px;
    background:#ffffff;
    transform:rotate(45deg);
    top:102px;
    left:109.5px;
    box-shadow: 180px -42.5px #ffffff;
  }
  p::after{
    transform:rotate(-45deg);
    left:266px;
    box-shadow: -180px -42.5px #ffffff;
  }
</style>

```

## [03 Super Saiyan](https://cssbattle.dev/play/103)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/f38a7629-e054-40de-9b22-bb330a932ecc)

```html

<div></div>
<p></p>
<style>
  body {
    background: #161616;
    position: relative;
  }
  body::after {
    position: absolute;
    content: "";
    background: #161616;
    width: 20px;
    height: 10px;
    border-radius: 0 0 10px 10px;
    top: 188px;
    left: 182px;
  }
  div {
    width: 80px;
    height: 70px;
    background: linear-gradient(to right, #ffffff 40px, #ffdeb9 25px);
    position: relative;
    top: 138px;
    left: 152px;
    border-radius: 0px 0px 50px 50px;
  }
  div::before,
  div::after {
    position: absolute;
    content: "";
    width: 55px;
    height: 30px;
    background: #ebae11;
    border-radius: 0px 0px 50px 50px;
    z-index: -1;
    top: 12px;
    left: 47px;
    transform: rotate(-10deg);
  }
  div::before {
    top: 13px;
    left: -22px;
    transform: rotate(15deg);
  }
  p {
    width: 60px;
    height: 60px;
    background: #ebae11;
    border-radius: 100% 0px;
    position: relative;
    z-index: 1;
    left: 162px;
    transform: rotate(-45deg);
    top: 2px;
  }
  p::before,
  p::after {
    content: "";
    position: absolute;
    width: 60px;
    height: 28px;
    background: #ebae11;
    border-radius: 0px 0px 50px 50px;
  }
  p::before {
    top: 52px;
    left: 3px;
    transform: rotate(-15deg);
  }
  p::after {
    top: 12px;
    left: -35px;
    transform: rotate(107deg);
  }
</style>

```

## [04 Amegakure](https://cssbattle.dev/play/104)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/4235e28b-f4b4-4593-b663-cb11e355edf7)

```html

<div></div>
<style>
 body {
    background: #000;
    display: grid;
    place-items: center;
    position: relative;
  }
  body::before,body::after {
    position: absolute;
    content: "";
    width: 240px;
    height: 120px;
    top: 82px;
    left: 72px;
    background: #37385a;
    border-radius: 20px;
  }
  body::after{
    width:200px;
    height:80px;
    top:102px;
    left:92px;
    border-radius:10px;
    background:#9897AE;
  }
  div{
    height:80px;
    z-index:1;
    width:52px;
    transform:skewX(-15deg);
    background:#C0C3DB;
    position:absolute;
    top:102px;
    left:166px
  }
  div::before,div::after{
    width:9.5px;
    height:9.5px;
    position:absolute;
    background:#000000;
    content:"";
    border-radius:50%;
    top:14px;
    left:-65px;
    transform:skewX(15deg);
    box-shadow:0 20px,0 40px,160px 0,160px 20px,160px 40px;
  }
  div::after{
    width:10px;
    height:50px;
    left:-9.5px;
    border-radius:5px;
    box-shadow:20px 0,40px 0, 60px 0;
  }
</style>

```

## [05 Ryuk](https://cssbattle.dev/play/105)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/cc219dce-b6f4-4ac0-bada-bce22bbc6c03)

```html

<div></div>
<div></div>
<style>
body {
    background: linear-gradient(45deg, #bac7ce 289px, transparent 289px),
      linear-gradient(-45deg, #bac7ce 289px, #475862 289px);
  }
  body::before,
  body::after {
    content: "";
    position: fixed;
    width: 100px;
    height: 100px;
    border-radius: 50%;
    box-shadow: 0 -15px 0 0 #5a6042;
    z-index: 1;
    top: 155px;
    left: 40px;
  }
  p{
    width: 120px;
    height: 120px;
    background: radial-gradient(
      circle at center,
      #4e2b24 15px,
      #000000 15px,
      #000000 20px,
      #868a64 20px,
      #868a64 50px,
      #000000 50px
    );
    position: relative;
    border-radius: 0px 50%;
    top: 122px;
    left: 22px;
    transform: rotate(-15deg);
  }
  body::after {
    top: 155px;
    left: 260px;
  }
  div{
    width: 120px;
    height: 120px;
    background: radial-gradient(
      circle at center,
      #4e2b24 15px,
      #000000 15px,
      #000000 20px,
      #868a64 20px,
      #868a64 50px,
      #000000 50px
    );
    position: relative;
    border-radius: 0px 50%;
    top: 122px;
    left: 22px;
    transform: rotate(-15deg);
  }
  div:nth-child(2){
    top:2px;
    left:242px;
    transform:rotate(105deg)
  }
</style>

```

## [06 Ryuk's Apple](https://cssbattle.dev/play/106)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/258ee2f9-09a4-402e-bd24-6ab6595b6f37)

```html

<div></div>
<style>
body {
    background: #000;
  }
  div{
    width:10px;
    height:40px;
    background:#D4392D;
    margin:70px auto;
  }
  body::before,body::after{
    position: absolute;
    content: "";
    width: 87.5px;
    height: 115px;
    background: #d4392d;
    border-radius: 40px 44px 66px 23px;
    top:93px;
    left:194.5px;
  }
  body::after{
    left:120px;
    transform:rotateY(180deg);
  }
  div::before,div::after{
    position: absolute;
    content: "";
    width: 60px;
    height: 60px;
    background: #000;
    top: 96.5px;
    left: 91px;
    z-index: 1;
    border-radius: 50%;
  }

  div::after{
    top:135.6
  }
</style>

```

## [07 Sealing Wand](https://cssbattle.dev/play/107)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/eb10ceb5-faa8-4c16-abda-f486b272c457)

```html

<div></div>
<p></p>
<style>
body {
    background: #161616;
  }
  body::before,body::after{
    width:20px;
    height:100px;
    background:#E96A23;
    content:"";
    position:absolute;
    bottom:0px;
    left:190px;
    z-index:-1;
  }
  body::after{
    width:80px;
    height:40px;
    bottom:131px;
    left:200px;
    border-radius:0px 80px 10px 0px
  }
  div{
    position:relative;
    background:#000;
    width:20px;
    height:20px;
    border-radius:50%;
    top:132px;
    left:182px;
    box-shadow: 0 0 0 5px #A22015, 0 0 0 15px #FFFFFF, 0 0 0 19.5px #A22015;
  }
  div::after{
    background:#A22015;
    width:30px;
    height:30px;
    content:"";
    position:absolute;
    border-radius:0 0 10px 10px;
    top:33px;
    z-index:-1;
    left:-5px
  }
  p,p::before,p::after{
    position:absolute;
    content:"";
    width:55px;
    height:12px;
    border-radius:0 0 0 12px;
    background:#FFFFFF;
    top:116px;
    left:130px;
  }
  p::before{
    top:12px;
    width:35px;
    left:15.5px;
  }
  p::after{
    width:25px;
    top:24px;
    left:30.5px
  }
</style>

```

## [08 Clow Card](https://cssbattle.dev/play/108)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/034cf077-3837-48e7-9810-a3161e1ebca4)

```html

<div></div>
<style>
 body {
    background: linear-gradient(
        to left,#000000 50px,transparent 50px,
        transparent 350px,#000000 350px), linear-gradient(to top,#000000 75px,transparent 75px,
        transparent 225px,#000000 225px), linear-gradient(-75deg, #e96a23 187px, #ebae11 187px, #ebae11 212px, #e96a23 212px, #e96a23 226px, #ebae11 226px, #ebae11 276px, #e96a23 276px);
  }
  div {
    width: 240px;
    height: 120px;
    background: radial-gradient(circle at center, #ebae11 25px, #000000 25px);
    position: relative;
    top: 82px;
    left: 72px;
    border-radius: 13px;
  }
  div::before,div::after {
    position: absolute;
    content: "";
    border: solid 5px #ebae11;
    border-radius: 50%;
  }
  div::before {
    width: 120px;
    height: 60px;
    top: 25px;
    left: 55px;
  }
  div::after {
    width: 200px;
    height: 80px;
    top: 15px;
    left: 15px;
  }
  body::before {
    content: "";
    position: absolute;
    width: 270px;
    height: 90px;
    background: #000000;
    top: 105px;
    left: 65px;
    border-radius: 13px;
  }
</style>

```
