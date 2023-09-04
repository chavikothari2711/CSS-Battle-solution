# Spacing battle

## [01 Curtain](https://cssbattle.dev/play/109)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/b1fa0036-e516-4030-a6b8-06f805e71434)

```html

<div></div>
<style>
  body{
    background: #191919;
  }
  div{
    width:40px;
    height:40px;
    background:#F6E59C;
    border-radius:50%;
    margin:20px 12px;
    box-shadow:60px 0 #F6E59C, 120px 0 #F6E59C, 180px 0 #F6E59C, 0 60px #F6E59C, 60px 60px #F6E59C, 120px 60px #F6E59C, 0 120px #F6E59C, 60px 120px #F6E59C, 0 180px #F6E59C;
  }
</style>

```

## [02 Sunrays](https://cssbattle.dev/play/110)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/1cc87ced-10e2-46bc-bfd6-359e3135d60b)


```html

<div></div>
<p></p>
<style>
  body {
    background: #d25b70;
  }
  div,div::before,div::after,p,p::before,p::after {
    width: 10px;
    height: 100px;
    background: #f2e09f;
    border-radius: 5px;
    margin: 80px auto;
    content: "";
    position: absolute;
  }
  div,p {
    position: relative;
  }
  div::before {
    transform: rotate(30deg);
    left: 35px;
    top: -71px;
  }
  div::after {
    transform: rotate(-30deg);
    left: -35px;
    top: -70px;
  }
  p {
    transform: rotate(90deg);
    top: -110;
    left: -70;
    box-shadow: 0 -140px 0 0 #f2e09f;
  }
  p::before {
    transform: rotate(30deg);
    left: -35px;
    top: -90px;
  }
  p::after {
    transform: rotate(-30deg);
    left: -35px;
    top: -210px;
  }
</style>

```

## [03 Raindrops](https://cssbattle.dev/play/111)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/197ab488-2d20-457b-8350-1dae670b410f)

```html

<div></div>
<style>
  body {
    background: #F3AC3C;
  }
  div,div::before,div::after{
    position:absolute;
    content:"";
    width:80px;
    height:80px;
    border-radius:50px 50px 50px 0px;
    background:#254241;
    transform:rotate(-45deg);
    top:40px;
    left:160px;
  }
  div::before{
    transform:rotate(-90deg);
    top:-7.5px;
    left:-106.5px
  }
  div::after{
    transform:rotate(-180deg);
    top:99px;
    left:-99px
  }
</style>

```

## [04 Chevron](https://cssbattle.dev/play/112)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/06b6f22b-2ba8-4c25-b9ac-2e4c1cec54f5)

```html

<div></div>
<p></p>
<style>
  body {
    background: #6592CF;
  }
  div,p{
   width: 130px;
    height: 24px;
    background: #293d7e;
    position: relative;
    transform: rotate(38.5deg);
    top: 79px;
    left: 82px;
    box-shadow: 30px 39px 0 #293d7e, 60px 78px 0 #293d7e;
  }
  p{
    transform: rotate(-38.5deg);
    top: 40px;
    left: 170px;
    box-shadow: -32px 39px 0 #293d7e, -63px 78px 0 #293d7e;
  }
  body::after,body::before,div::before,div::after,
  p::before,p::after {
    position: fixed;
    top: 50px;
    left: 78px;
    content: "";
    width: 37px;
    height: 17.5px;
    background: #293d7e;
    clip-path: polygon(0 0, 100% 0, 50% 100%);
    transform: rotate(-0.5deg);
  }
  body::after {
    transform: rotate(1.5deg);
    top: 51px;
    left: 283.5px;
  }
  div::before {
    top: 47.5px;
    left: 6px;
    transform: rotate(-38.5deg);
  }
  div::after {
    top: -78.8px;
    left: 167px;
    transform: rotate(-40deg);
    z-index: 1;
  }
  p::before {
    transform: rotate(40deg);
    top: 86.5px;
    left: 54px;
  }
  p::after {
    transform: rotate(40deg);
    top: -44;
    left: -105;
  }
</style>

```

## [05 Blacklight](https://cssbattle.dev/play/113)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/06f9f234-0709-4c96-8946-8aca03123e51)

```html

<div></div>
<style>
  body{
    background:#5776F6;
    margin:0px;
  }
  div {
   	width: 400;
	height: 300;
	clip-path: polygon(0% 41.6%, 0% 58.3%, 100% 66.6%, 100% 33.3%);
    background:#191919;
  }
</style>

```

## [06 Negative Box](https://cssbattle.dev/play/114)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/aa158d8f-f90e-4272-9621-b64a1fcfb3d5)

```html

<div></div>
<p></p>
<style>
  body{
    background:#172D2C;
    margin:0px;
  }
  div {
   	position:absolute;
    top:117px;
    width:180px;
    height:130px;
    transform:skewY(20deg);
    background:#E9AF53;
    left:20px
  }
  p{
    width: 180px;
    height: 130px;
    background: #e9af53;
    margin: 20px 200px;
    clip-path: polygon(0 0, 100% 50%, 0 100%);
  }
</style>

```

## [07 Broplet](https://cssbattle.dev/play/115)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/7711c457-3450-4c56-acc1-c44d319f293f)

```html

<style>
  body {
    background: linear-gradient(#c36271 50%, #f2e09f 50%);
    margin: 0;
  }
  body::before,body::after {
    position: fixed;
    content: "";
    width: 380px;
    height: 150px;
    border-radius: 0 0 100px 0;
  }
  body::before {
    background: radial-gradient(
      circle at 200px 100%,
      #c36271 50px,
      #f2e09f 50px
    );
  }
  body::after {
    top: 50%;
    left: 20px;
    transform: rotate(180deg);
    background: radial-gradient(
      circle at 200px 100%,
      #f2e09f 50px,
      #c36271 50px
    );
  }
</style>

```

## [08 Headphone](https://cssbattle.dev/play/116)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/d314eb3c-0769-487e-b0d9-a5f6db8c6a51)

```html

<div></div>
<style>
  body{
    background:#293D7E;
    margin:0px;
  }
  div{
    width:170px;
    height:150px;
    box-sizing:border-box;
    border: 20px solid #6E91CA;
    border-radius:100px 100px 0px 0px;
    border-bottom:0px;
    margin:45px auto;
  }
  div::before,div::after{
    content:"";
    position:absolute;
    background:#6E91CA;
    width:60px;
    height:80px;
    top:165px;
    left:115px;
    border-radius:0px 20px 30px 30px;
  }
  div::after{
    transform:rotateY(180deg);
    left:225px
  }
</style>

```
