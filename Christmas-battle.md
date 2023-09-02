# Christmas Battle

## [01 Snowman](https://cssbattle.dev/play/97)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/b42fc11c-456b-41c6-b376-beca7e1f3325)

```html

<div></div>
<span></span>
<style>
  body{
    background:#AC474B;
  }
  body::before, span, body::after,div::before,div::after{
    content:"";
    position:absolute;
    z-index:1;
  }
  body::before {
    top: 143px;
    left: 170px;
    width: 60px;
    height: 10px;
    background: #ffa63f;
    z-index: 2;
    border-radius: 10px;
  }
  body::after {
    top: 139px;
    left: 162px;
    width: 80px;
    height: 18px;
    background: #ac474b;
  }
  div{
    width:10px;
    height:10px;
    border-radius:50%;
    background:#0E1F2B;
    margin:113px 177px;
    box-shadow: 20px 0 #0E1F2B;
  }
  div::after{
    z-index:-1;
    width:60px;
    height:60px;
    border-radius:50%;
    background:#FFFFFF;
    top:95px;
    left:170px;
    box-shadow: 0 70px 0 20px #FFFFFF;
  }
  div::before{
    width:40px;
    height:45px;
    top:55px;
    left:180px;
    background:linear-gradient(
      to bottom,
      #0e1f2b 33%,
      #ffffff 33%,
      #ffffff 56%,
      #0e1f2b 56%
    );
  }
  span{
    width:60px;
    height:5px;
    background:#0E1F2B;
    top:95px;
    left:170px;
  }
</style>

```

## [02 Candle](https://cssbattle.dev/play/98)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/624589b6-0077-448f-ba7c-177d2e01bfa0)

```html

<div></div>
<style>
  body{
    background:#14313E;
  }
  body::before{
    content:"";
    position:absolute;
    width:30px;
    height:50px;
    top:60px;
    left:200px;
    background:#F3AC3C;
    border-radius:50px 0px;
    z-index:2;
  }
  div {
    position: fixed;
    top: 125px;
    left: 160px;
    width: 80px;
    height: 100px;
    background: #ba3e46;
  }
  div::before,div::after{
    width:80px;
    height:30px;
    background:#F3695A;
    content:"";
    border-radius:50%;
    position:absolute;
    top:-15px;
    box-shadow:0 100px #BA3E46;
  }
  div::after{
    width:60px;
    background:#14313E;
    top:-25px;
    left:10px;
  }
</style>

```

## [03 Gift Box](https://cssbattle.dev/play/99)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/57d3ced2-7235-40a7-8000-f2a790f6fa54)

```html

<div></div>
<style>
  body{
    background:#AC474B;
  }
  div{
    width:60px;
    height:60px;
    background:#ffffff;
    margin:110px 122px;
    box-shadow: 80px 0 #FFFFFF, 80px 80px #FFFFFF, 0 80px #FFFFFF;
  }
  body::before,
  body::after {
    position: fixed;
    content: "";
    width: 20px;
    height: 20px;
    background: #ac474b;
    border: solid 10px #ffffff;
    top: 50px;
    left: 165px;
    border-radius: 50px 50px 0 50px;
  }
  body::after {
    left: 195px;
    transform: rotateY(180deg);
  }
</style>

```

## [04 CSS Battle](https://cssbattle.dev/play/100)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/52bd64c8-d6ec-46e7-884c-d3ce8ec47a5a)

```html

<div></div>
<p class="one"></p>
<p class="two"></p>
<h1></h1>
<h2></h2>
<h3></h3>
<style>
  body {
    background: #14313e;
  }
  body::before,body::after,div::before,div::after {
    position: fixed;
    content: "";
  }
  div {
    position: fixed;
    top: 75px;
    left: 63px;
    width: 214px;
    height: 90px;
    border: solid 30px #ffdf00;
    border-radius: 20px;
  }
  div::before {
    top: 0;
    bottom: 0;
    left: 103px;
    right: 103px;
    background: #14313e;
    z-index: 1;
  }
  div::after {
    width: 294px;
    height: 40px;
    background: #ffdf00;
    top: 130px;
    left: 53px;
    border-radius: 5px;
  }
  body::before {
    width: 224px;
    height: 100px;
    background: #14313e;
    top: 100px;
    left: 88px;
    z-index: 1;
    border-radius: 10px;
  }
  p {
    position: relative;
    width: 148px;
    height: 30px;
    background: #ffdf00;
    z-index: 1;
  }
  .one {
    top: 110px;
    left: 107px;
    transform: rotate(45deg);
  }
  .two {
    top: 64px;
    left: 130px;
    transform: rotate(135deg);
  }
  p::before,p::after {
    position: absolute;
    content: "";
  }
  p::before {
    width: 20px;
    height: 80px;
    background: #ffdf00;
    left: 136px;
    top: -25px;
  }
  p::after {
    width: 50px;
    height: 20px;
    background: #ffdf00;
    border-radius: 8px;
    top: 5px;
    left: 145px;
  }
  h1 {
    position: fixed;
    z-index: 1;
    width: 50px;
    height: 10px;
    background: #14313e;
    transform: rotate(45deg);
    top: 132px;
    left: 160px;
    box-shadow: 0 -41px 0 0 #14313e;
  }
  h2,h3 {
    position: fixed;
    z-index: 1;
    width: 0px;
    height: 0px;
    border: solid 16px transparent;
    border-bottom-color: #ffdf00;
    transform: rotate(-45deg);
    top: 35;
    left: 110;
  }
  h3 {
    transform: rotate(45deg);
    top: 36;
    left: 259;
  }
</style>

```
