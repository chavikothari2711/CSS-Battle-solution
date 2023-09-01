# Blend battle

## [01 Improv MX](https://cssbattle.dev/play/61)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/71a7e06b-1add-4e28-a286-632aa8f18c87)

```html

<div></div>
<p></p>
<style>
  body {
    background: #191919;
    margin: 0;
  }
  body::before,
  body::after {
    content: "";
    position: absolute;
    width: 200px;
    height: 10px;
    background: #5dbcf9;
    top: 204px;
    left: 100px;
  }
  body::after {
    top: 224px;
    left: 145px;
    width: 110px;
  }
  div {
    margin: 96px auto;
    width: 80px;
    height: 50px;
    border: solid 10px #5dbcf9;
    position: relative;
    border-bottom: 0;
  }
  div::before {
    content: "";
    position: absolute;
    top: -40px;
    left: 15px;
    width: 30px;
    height: 20px;
    border: solid 10px #5dbcf9;
  }
  div::after {
    content: "";
    position: absolute;
    width: 10px;
    height: 60px;
    background: #5dbcf9;
    top: 30px;
    left: 35px;
  }
  p {
    position: relative;
    width: 200px;
    height: 10px;
    background: #191919;
    top: -57px;
    left: 100px;
  }
  p::before,
  p::after {
    content: "";
    position: absolute;
    width: 80px;
    height: 35px;
    border: solid 10px #5dbcf9;
    border-bottom: 0;
    border-right: 0;
    top: -50px;
    left: 26px;
    transform: rotate(-30deg);
    z-index: -1;
  }
  p::after {
    border: solid 10px #5dbcf9;
    border-bottom: 0;
    border-left: 0;
    left: 82px;
    transform: rotate(30deg);
  }
</style>

```

## [02 Sunset](https://cssbattle.dev/play/62)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/c5f75c3a-dec5-42e4-be63-44f895c1cc7e)

```html

<div></div>
<style>
  body {
    background: #191919;
    display: grid;
    place-items: center;
  }
  div {
    width: 150px;
    height: 200px;
    background: #f2ad43;
    border-radius: 100px 100px 30px 30px;
    position: relative;
    overflow: hidden;
  }
  div::before {
    position: absolute;
    content: "";
    width: 200px;
    height:200px;
    border-radius: 50%;
    background:#824B20;
    top:100px;
    left:50px;
    z-index:2;
    box-shadow: -150px 0 0 0 #E08027;
  }
  div::after{
    position: absolute;
    content: "";
    width: 60px;
    height:60px;
    border-radius: 50%;
    background:#FFF58F;
    z-index:1;
    top:90px;
    left:45px;
  }
</style>

```

## [03 Command Key](https://cssbattle.dev/play/63)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/0188fac3-34ef-4c70-a032-4641efa0b0ec)

```html

<div></div>
<style>
 body {
    background: #191919;
    display: grid;
    place-items: center;
    margin: 0;
  }
  div {
    width: 50px;
    height: 50px;
    border: solid 10px #5dbcf9;

  }
  div::before,div::after,body::before,body::after{
    width: 50px;
    height: 50px;
    border: solid 10px #5dbcf9;
    position:absolute;
    content:"";
    border-radius:50px 50px 0px 50px;
    left:105px;
    top:55px
  }
  div::after{
    transform:rotate(90deg);
    left:225px;
  }
  body::before{
    transform:rotate(180deg);
    left:225px;
    top:175px;
  }
  body::after{
    transform:rotate(-90deg);
    left:105px;
    top:175px;
  }
</style>

```

## [04 Door Knob](https://cssbattle.dev/play/64)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/e271ca8e-c9f4-47e6-a4a1-2f4997970e14)

```html

<div></div>
<style>
  body {
    background: radial-gradient(
        circle at 150px 50%,
        #fff58f 10px,
        transparent 10px
      ), radial-gradient(circle at 250px 50%, #fff58f 10px, transparent 10px),
      radial-gradient(circle, #e08027 50px, #824b20 50px, #824b20 80px, #191919
          80px);
    display: grid;
    place-items: center;
  }
  div {
    width: 80px;
    height: 80px;
    border: solid 20px #fff58f;
    border-top-color: transparent;
    border-left-color: transparent;
    border-radius: 50%;
    transform: rotate(45deg);
  }
</style>

```

## [05 Max Volume](https://cssbattle.dev/play/65)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/88e3e9f6-3457-4ce5-840e-ed7032f89377)

```html

<div></div>
<style>
  body {
    background: linear-gradient(to right, #191919 225px, transparent 225px),
      radial-gradient(circle at 225px 50%, #191919 40px, #5dbcf9 40px, #5dbcf9
          50px, #191919 50px, #191919 65px, #5dbcf9 65px, #5dbcf9 75px, #191919
          75px, #191919 90px, #5dbcf9 90px, #5dbcf9 100px, #191919 100px);
  }
  div {
    width: 0px;
    height: 0px;
    border: solid 100px transparent;
    border-right-color: #5dbcf9;
    margin: 50px -8px;
  }
  div::after {
    position: absolute;
    content: "";
    background: #5dbcf9;
    width: 50px;
    height: 50px;
    left: 75px;
    top: 125px;
    border-radius: 8px 0 0 8px;
  }
</style>

```

## [06 Batmicky](https://cssbattle.dev/play/66)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/c002e3d6-0294-4d8d-ab56-e08060283c3f)

```html

<div></div>
<p></p>
<style>
  body {
    background:#191919;
    display:grid;
    place-items:center;
  }
  div{
    width:240px;
    height:100px;
    background:#F2AD43;
  }
  div::before{
    position:absolute;
    content:"";
    width:100px;
    height:100px;
    top:100px;
    left:25px;
    border-radius:50%;
    background:#191919;
    box-shadow:70px 90px 0px 30px #191919,180px 90px 0px 30px #191919,250px 0px 0px #191919;  
  }
  div::after{
    position:absolute;
    content:"";
    left:160px;
    width:80px;
    height:50px;
    top:80px;
    border-radius:10px;
    background:#191919;
  }
  p{
    position:absolute;
    z-index:2;
    width:20px;
    height:25px;
    background:#F2AD43;
    top:94px;
  }
  p::before{
    content:"";
    position:absolute;
    width:10px;
    height:10px;
    border-radius:50%;
    background:#F2AD43;
    top:-6px;
    left:-5px;
    box-shadow: 20px 0px 0px #F2AD43;
  }
</style>

```

## [07 Video Reel](https://cssbattle.dev/play/67)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/5904e149-0e74-431b-bdee-b23b137b37db)

```html

<div></div>
<style>
  body{
    background: #191919;
    margin:0px;
  }
  div{
    height:500px;
    width:10px;
    background:#5DBCF9;
    margin:0px 45px;
    box-shadow: 150px 0 0 0 #5DBCF9, 300px 0 0 0 #5DBCF9;
  }
  div::before{
    position:absolute;
    content:"";
    height:40px;
    width:150px;
    background:#5DBCF9;
    top:80px;
    left:-100px;
    box-shadow:
      0 150px #5DBCF9, 150px -50px #5DBCF9, 150px 100px #5DBCF9, 300px 0 #5DBCF9, 300px 150px #5DBCF9, 450px -50px #5DBCF9,450px 100px #5DBCF9;
  }
</style>

```

## [08 Bell](https://cssbattle.dev/play/68)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/0f37bd98-a506-4eb5-a061-c7be1b22851f)

```html

<div></div>
<style>
  body{
    background: #191919;
    margin:0px;
    place-items:center;
    display:grid;
  }
  div{
    width:120px;
    height:120px;
    border-radius:60px 60px 10px 10px;
    background:#E08027;
  }
  div::before,div::after{
    position:absolute;
    background:#F2AD43;
    width:50px;
    height:50px;
    border-radius:50%;
    z-index:-1;
    top:66px;
    left:175px;
    content:"";
  }
  div::after{
    background:#824B20;
    top:185px;
  }
</style>

```
