# Overflow battle 

## [01 Pastel Logo](https://cssbattle.dev/play/53)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/cdfd860b-8c3a-4ee4-8edc-dff42453c0ab)

```html

<div></div>
<style>
  body{
    background: #19191A;
  }
  div{
    width:75px;
    height:125px;
    background:#F9E492;
    position:relative;
    top:117px;
    left:117px;
  }
  div::before{
    position:absolute;
    width:0px;
    height:0px;
    content:"";
    box-sizing:border-box;
    border:75.5px solid;
    border-radius:50%;
    border-color:#4F77FF #4F77FF #4F77FF #9AD5FF;
    transform:rotate(-45deg);
    top:-75px;
  }
</style>

```

## [02 Black Lives Matter](https://cssbattle.dev/play/54)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/d65b974d-5224-4f6f-9b33-c0ce2a372f83)

```html

<div></div>
<style>
  body{
    background: #F9E492;
  }
  div{
    position:relative;
    width:50px;
    height:80px;
    background:#191919;
    border-radius:0px 0px 10px 10px;
    top:135px;
    left:167px;
  }
  div::before,div::after{
    position:absolute;
    content:"";
    top:-5px;
    left:-25px;
    border-radius:0px 0px 10px 10px;
    width:100px;
    height:40px;
    background:#191919;
  }
  div::after{
     width: 65px;
    height: 20px;
    border: solid 5px #f9e492;
    z-index: 1;
    border-radius: 20px;
    top: -16px;
    left: -45px;
    transform: rotate(-30deg);
  }
  body::before,body::after{
    position: absolute;
    content: "";
    top: 88px;
    left: 155px;
    width: 20px;
    height: 45px;
    background: #191919;
    border-radius: 12px;
  }
  body::before {
    box-shadow: 25px -10px 0 0 #191919, 50px 0 0 0 #191919;
  }
  body::after{
    height:35px;
    left:230px;
    top:98px;
  }
</style>

```

## [03 Windmill](https://cssbattle.dev/play/55)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/6c53f54a-dd14-4d69-a940-4aa1e70fb730)

```html

<div></div>
<style>
  body{
    background: #191919;
  }
  div{
    position:relative;
    top:92px;
    left:92px;
    width:100px;
    height:50px;
    border-radius:50px 50px 0px 0px;
    background:#F9E492;
  }
  div::before,div::after,body::before{
    content:"";
    position:absolute;
    width:100px;
    height:50px;
    border-radius:0px 0px 50px 50px;
    background:#F9E492;
    left:100px;
    top:50px;
  }
  body::before{
    transform:rotate(-90deg);
    background:#4F77FF;
    left:175px;
    top:75px;
  }
  div::after{
    transform:rotate(90deg);
    background:#4F77FF;
    left:25px;
    top:75px;
  }
</style>

```

## [04 Skull](https://cssbattle.dev/play/56)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/57937b97-58eb-438d-8a1e-6241717df125)

```html

<div></div>
<style>
  body{
    background: #191919;
  }
  div{
    width:120px;
    height:100px;
    background:#4F77FF;
    border-radius:60px 60px 10px 10px;
    margin: 85px auto;
  }
  div::before,div::after, body::after{
    content:"";
    position:absolute;
    width:40px;
    height:40px;
    border-radius:50%;
    background:#191919;
    top:138px;
    left:155px;
  }
  div::before{
    box-shadow: 50px 0px 0px #191919;
  }
  div::after{
    z-index:1;
    content:"";
    width:20px;
    height:20px;
    top:176px;
    left:190px
  }
  body::before{
    content:"";
    position:absolute;
    background:#4F77FF;
    width:80px;
    height:35px;
    top:180px;
    left:160px;
    border-radius:0px 0px 20px 20px;
  }
  body::after{
    width:10px;
    height:20px;
    border-radius:5px;
    top:205px;
    left:180px;
    box-shadow: 15px 0 0 0 #191919, 30px 0 0 0 #191919 ;
  }
</style>

```

## [05 Pillars](https://cssbattle.dev/play/57)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/b35ff979-f129-43b4-a2e6-05bde9a81443)

```html

<div></div>
<style>
  body{
    background: #191919;
    display:grid;
    place-items:center;
  }
  div{
    background:#4F77FF;
    width:110px;
    height:110px;
        position:relative;
  }
  div::after{
    position: absolute;
    content: "";
    width: 30px;
    height: 30px;
    border-radius: 50%;
    background: #4F77FF;
    top: -20px;
    left: -20px;
    box-shadow:
      8px 8px 0 7px #F9E492,
      14px 14px 0 16px #191919,
      120px 0 0 0 #4F77FF,
      112px 8px 0 7px #F9E492,
      106px 14px 0 16px #191919,
      0 120px 0 0 #4F77FF,
      8px 112px 0 7px #F9E492,
      14px 106px 0 16px #191919,
      120px 120px 0 0 #4F77FF,
      112px 112px 0 7px #F9E492,
      106px 106px 0 16px #191919
  }
</style>

```

## [06 Rose](https://cssbattle.dev/play/58)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/96da519c-60eb-4838-95e9-21e10440a3fd)

```html

<div></div>
<p></p>
<style>
  body{
    background: #191919;
  }
  div{
    width:20px;
    height:90px;
    border-radius:50px;
    background:#F9E492;
    position:relative;
    top:157px;
    left:182px;
  }
  div::before,div::after{
    content:"";
    position:absolute;
    width:40px;
    height:30px;
    border-radius:0px 0px 20px 20px;
    background:#F9E492;
    top:-10px;
    left:-10px
  }
  
  body::before{
    box-sizing: border-box;
    position: absolute;
    content: "";
    width: 120px;
    height: 50px;
    background: #4f77ff;
    top: 55px;
    left: 140px;
    border: solid 10px #191919;
    border-radius: 100px 100px 200px 200px;
    z-index:1;
  }
  body::after{
    box-sizing: border-box;
    position: absolute;
    content: "";
    width: 160px;
    height: 50px;
    background: #4f77ff;
    top: 75px;
    left: 120px;
    border: solid 10px #191919;
    border-radius: 100px 100px 200px 200px;
  }
  div::after{
    width:100px;
    height:50px;
    border-radius: 0px 0px 50px 50px;
    background:#4F77FF;
    top:-50px;
    left:-40px;
  }
  p{
    content: "";
    z-index:2;
    position: absolute;
    width: 30px;
    height: 30px;
    background: #4F77FF;
    border-radius: 50%;
    border:11px solid #191919;
    top: 18px;
    left: 175px;
  }
</style>

```

## [07 Earth](https://cssbattle.dev/play/59)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/23a9d4bb-fd21-4126-aca2-1f182b5f558f)

```html

<div></div>
<p></p>
<style>
  body{
    background: #191919;
    display:grid;
    place-items:center;
  }
  div{
    width:150px;
    height:150px;
    background:#4F77FF;
    overflow:hidden;
    border-radius:50%;
    position:relative;
  }
  div::before{
    content:"";
    position:absolute;
    top:30px;
    background:#191919;
    width:150px;
    height:10px;
    box-shadow:0 40px 0 0 #191919, 0 80px 0 0 #191919;
  }
  div::after{
    content:"";
    position:absolute;
    background:#191919;
    left:70px;
    width:10px;
    height:150px;
  }
  p{
    box-sizing:border-box;
    border:10px solid #191919;
    content:"";
    position:absolute;
    width: 125px;
	  height: 125px;
	  border-radius: 0 105px;
	  transform: rotate(45deg);
  }
</style>

```

## [08 Evil Triangle](https://cssbattle.dev/play/60)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/74e35472-aef4-4c97-b7bd-596341a6411e)

```html

<div></div>
<style>
  body {
    background: #191919;
    display: grid;
    place-items: center;
  }
  div {
    width: 200px;
    height: 150px;
    background: #4f77ff;
    position: relative;
  }
  div::after,
  div::before {
    content: "";
    position: absolute;
    width: 50px;
    height: 50px;
    background: #191919;
    top: 25px;
    transform: skewY(45deg);
  }
  div::before{
    box-shadow:100px -100px 0 0 #191919, 0 100px 0 0 #191919, 100px 0 0 0 #191919; 
  }
  div::after{
    transform:skewY(-45deg);
    left:50px;
    box-shadow:0 100px 0 0 #191919, 100px 100px 0 0 #191919,100px 200px 0 0 #191919;
  }
</style>

```

