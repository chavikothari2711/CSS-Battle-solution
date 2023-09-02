# Zindex Battle

## [01 Notes](https://cssbattle.dev/play/77)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/55cce71e-5cfc-43a2-8337-e816a91c5fbb)

```html

<div></div>
<style>
  body{
    background: #191919;
  }
  div{
    position: relative;
    width:50px;
    height:40px;
    border-radius:50%;
    background:#FE5F55;
    top:162px;
    left:47px;
    box-shadow: 70px 0 #FE5F55, 140px 0 #A64942, 210px 0 #FE5F55;
  }
  div::before, div::after{
    content:"";
    position:absolute;
    background:#FE5F55;
  }
  div::before{
    top:-80px;
    left:40px;
    width:10px;
    height:100px;
    box-shadow:70px 0 #FE5F55, 140px 0 #A64942, 210px 0 #FE5F55
  }
  div::after{
    width:35px;
    height:10px;
    top:-80px;
    left:50px;
    box-shadow:30px 0 #FE5F55, 135px 0 #A64942, 205px 0 #FE5F55, 205px 20px #FE5F55;   
  }
</style>

```

## [02 Ukulele](https://cssbattle.dev/play/78)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/920a1c4a-5604-4ea9-af49-cbbf072613f4)

```html

<div></div>
<style>
  body{
    background: radial-gradient(
      circle at 165px 50%,
        #1a4341 20px,
        #f3ac3c 20px,
        #f3ac3c 25px,
        #998235 25px,
        #998235 50px,
        transparent 50px
    ), radial-gradient(circle at 105px 50%, #998235 60px, transparent 60px),linear-gradient(
      to right,
        #f3ac3c 50px,
        transparent 10px,
        transparent 325px,
        #f3ac3c 325px
      ), linear-gradient(#f3ac3c 140px, #1a4341 140px, #1a4341 160px, #f3ac3c
          160px);
  }
  div {
    width: 40px;
    height: 30px;
    background: #998235;
    border-radius: 10px;
    position: relative;
    left: 307px;
    top: 127px;
  }
  div::before,
  div::after {
    position: absolute;
    content: "";
    width: 20px;
    height: 4px;
    background: #1a4341;
    top: 8px;
    left: 10px;
    border-radius: 2px;
    box-shadow: 0 10px 0 0 #1a4341;
  }
  div::after {
    width: 40px;
    height: 10px;
    left: -245px;
    border-radius: 4px;
    top: 10px;
    box-shadow: none;
    transform: rotate(90deg);
  }
  
</style>

```

## [03 Tambourine](https://cssbattle.dev/play/79)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/0c91a3ff-6276-4d60-97f9-2b882c740191)

```html

<div></div>
<p></p>
<style>
  body{
    background: #6592CF
  }
  div{
     width: 150px;
    height: 150px;
    border: solid 10px #243D83;
    border-radius: 50%;
    margin: 75px auto;
    position: relative;
    clip-path: circle(85px);
  }
  div::before {
    content: "";
    position: absolute;
    width: 100px;
    height: 100px;
    background: #6592cf;
    border: solid 10px #243d83;
    border-radius: 50%;
    top: 115px;
    left: 15px;
  }
  body::after{
    content:"";
    position:absolute;
    width:10px;
    height:10px;
    background:#243D83;
    border-radius:50%;
    top:75px;
    left:195px;
    box-shadow:70px 40px #243D83, 70px 110px #243D83, -70px 40px #243D83, -70px 110px #243D83;
  }
  p{
    width:30px;
    height:30px;
    position:absolute;
    background:#6592CF;
    top:49px;
    border-radius:50%;
    left:185px;
    box-shadow: 70px 40px #6592CF, 70px 110px #6592CF, -70px 40px #6592CF, -70px 110px #6592CF;
  }
  p::before{
    content:"";
    width:50px;
    height:50px;
    position:absolute;
    background:#243D83;
    top:-10px;
    border-radius:50%;
    z-index:-1;
    left:-10px;
   box-shadow: 70px 40px #243D83, 70px 110px #243D83, -70px 40px #243D83, -70px 110px #243D83;
  }
</style>

```

## [04 Piano](https://cssbattle.dev/play/80)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/1a4c6cf8-45fb-41eb-9b00-e58f9de37832)

```html

<div></div>
<style>
  body{
    background: #998235;
    display:grid;
    place-items:center;
  }
 div{
   width:180px;
   height:100px;
   background:#191919;
   border-radius:10px;
   position:relative;
 }
  div::before{
    content:"";
    position:absolute;
    width:20px;
    height:70px;
    background:#ffffff;
    border-radius:5px;
    bottom:5px;
    left:5px;
    box-shadow: 25px 0 #ffffff, 50px 0 #ffffff, 75px 0 #ffffff, 100px 0 #ffffff, 125px 0 #ffffff, 150px 0 #ffffff;
  }
  div::after{
    content:"";
    position:absolute;
    width:15px;
    height:40px;
    background:#191919;
    top:20px;
    left:20px;
    box-shadow: 25px 0 #191919, 75px 0 #191919, 100px 0 #191919, 125px 0 #191919;
  }
</style>

```
