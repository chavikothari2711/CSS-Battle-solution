# Aspect Battle

## [01 Summit](https://cssbattle.dev/play/89)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/85c4b0c8-3ffd-4f7c-bb7b-c01db4e238e9)

```html

<div></div>
<style>
  body {
    background: radial-gradient(
      circle at 200px 150px,
      #f9e492 100px,
      #191919 100px
    );
  }
  div {
    width: 300px;
    height: 300px;
    background: radial-gradient(
      circle at 150px 141px,
      #191919 100px,
      #4f77ff 100px
    );
    margin: 9px auto;
    clip-path: polygon(50% 50%, 100% 100%, 0 100%);
  }
</style>

```

## [02 Eclipse](https://cssbattle.dev/play/90)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/0643ba27-a5a1-45c3-8e06-22da6cb2fb0e)

```html

<div></div>
<style>
  body {
    background: #F3AC3C;
  }
 div{
   width:200px;
   height:200px;
   margin:25px auto;
   background:#1A4341;
   border-radius:50%;
   border:25px solid #F3AC3C;
 }
  div::before,div::after{
    content:"";
    position:absolute;
    bottom:-250px;
    left:0px;
    border-radius:50%;
    width:400px;
    height:400px;
    background:#998235
  }
  div::after{
    bottom:150px;
    z-index:-1;
  }
</style>

```

## [03 Reflection](https://cssbattle.dev/play/91)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/346d1da2-7471-4ae4-a2ec-24bf06aceb21)

```html

<div></div>
<style>
  body {
    background: linear-gradient( 
    #D25B70 0%, 
    #D25B70 50%, 
    #6CB3A9 50%, 
    #6CB3A9 100%);
  }
 div{
   width:200px;
   height:200px;
   margin:50px auto;
   background:#F6DF96;
   border-radius:50%;
   position:relative;
 }
  div::after{
    content:"";
    position:absolute;
    width:200px;
    height:15px;
    background:#6CB3A9;
    top:100px;
    box-shadow: 0 25px #6CB3A9, 0 50px #6CB3A9, 0 75px #6CB3A9;
  }  
</style>

```

## [04 Squeeze](https://cssbattle.dev/play/92)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/9515b700-42fc-49f8-92cf-58a45709b79b)

```html

<div></div>
<style>
  body {
    background:linear-gradient(
      #6592CF 0%,
      #6592CF 44%,
      #243D83 44%,
      #243D83 56%,
      #6592CF 56%
    );
  }
  div{
    width:200px;
    height:200px;
    border-radius:50%;
    background:#243D83;
    margin:50px auto;
    box-shadow: -226px 0 #243D83, 226px 0 #243D83;
  }
  div::before{
    content:"";
    width:30px;
    height:200px;
    border-radius:20px;
    background:#6592CF;
    position:absolute;
    top:-60px;
    left:72px;
    box-shadow: 0 220px #6592CF, 226px 0 #6592CF, 226px 220px #6592CF;
  }
</style>

```

## [05 Great Wall](https://cssbattle.dev/play/93)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/0cddf2d6-3fbd-48ab-9c0d-60eec8f4baea)

```html

<div>
  <p></p>
</div>
<style>
  body {
    background: #4F77FF
  }
  div {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    margin: 50px auto;
    position: relative;
    overflow: hidden;
    background:#191919;
  }
  p{
    position:absolute;
    width:40px;
    height:40px;
    border-radius:50%;
    background:#F9E492;
    top:24px;
    left:40px;
  }
  p::before, p::after{
    content:"";
    position:absolute;
    height:16px;
    width:100px;
    background:#F9E492;
    top:82px;
    left:-40px;
    box-shadow:0 26px #F9E492, 0 52px #F9E492, 120px -13px #F9E492, 120px 13px #F9E492, 120px 39px #F9E492
  }
  p::after{
    box-shadow:0 26px #D6B73F, 0 52px #D6B73F;
    width:20px;
    top:75.5px;
    left:60px;
    background:#D6B73F;
    transform:skewY(-35deg);
  }
</style>

```

## [6 Ripples](https://cssbattle.dev/play/94)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/d4df6a48-133a-4710-9ab8-ab0152f9a9df)

```html

<style>
  body {
    background: radial-gradient(
      circle,
      #F3AC3C 20px,
      #0E2E2C 20px,
      #0E2E2C 28px,
      #F3AC3C 28px,
      #F3AC3C 40px,
      #0E2E2C 40px,
      #0E2E2C 50px,
      #998235 50px,
      #998235 60px,
      #0E2E2C 60px,
      #0E2E2C 72px,
      #F3AC3C 72px,
      #F3AC3C 80px,
      #0E2E2C 80px,
      #0E2E2C 93px,
      #F3AC3C 93px,
      #F3AC3C 100px,
      #0E2E2C 100px
    );
  }
</style>

```

## [07 Pokeball](https://cssbattle.dev/play/95)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/1c1c8707-269c-4cab-ab66-b0c5d0790e54)

```html

<div></div>
<style>
    body{
    background: radial-gradient(circle, #781728 90px, #6CB3A9 50px);
  }
  div {
    margin: 50px auto;
    width: 200px;
    height: 200px;
    border-radius: 50%;
    background: linear-gradient(#D25B70 90px, #781728 90px, #781728 110px,  #FFFFFF 110px);
    position: relative:
  }
  div::before, div::after{
    position: absolute;
    content: "";
    width: 10px;
    height: 20px;
    top: 140px;
    background: #6CB3A9;
    box-shadow: 190px 0 0 0 #6CB3A9;
  }
  div::after{
    width: 50px;
    height: 50px;
    background: #F6DF96;
    border-radius: 50%;
    border: solid 10px #781728;
    top: 115px;
    left: 165px;
  }
</style>

```

## [08 Mandala](https://cssbattle.dev/play/96)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/71ab0454-dff2-439d-a8bf-019a0f1ffa13)

```html

<div></div>
<style>
    body{
    background: radial-gradient(circle, #6592CF 100px, #243D83 50px);
  }
  div::before, div::after, body::before, body::after{
    content:"";
    position:absolute;
    width:130px;
    height:130px;
    border-radius:50%;
    border:20px solid #243D83;
    top:65px;
    left:40px;
  }
  div::after{
    left:190px;
  }
  body::before{
    top:-11px;
    left:115px
  }
  body::after{
    top:141px;
    left:115px;
  }
</style>

```
