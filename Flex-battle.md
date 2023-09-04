# Flex battle

## [01 Pawn](https://cssbattle.dev/play/151)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/1d5eb25d-7235-4490-a18f-dbb38ee3cf65)

```html

<div></div>
<p></p>
<span></span>
<style>
  body{
    background:radial-gradient(circle at 50% 80px, #D86F45 25px , #F5D6B4 25px)
  }
  div{
    margin:105px auto;
    background:#D86F45;
    width:80px;
    height:20px;
    border:5px solid #F5D6B4;
    border-radius:12px 12px 20px 20px;
  }
  div::before,div::after{
    content:"";
    position:absolute;
    width:90px;
    height:65px;
    border:5px solid #F5D6B4;
    background:#D86F45;
    top:130px;
    left:150px;
    z-index:-1;
  }
  div::after{
    width:140px;
    left:125px;
    top:200px;
    height:40px;
    border-radius:25px 25px 15px 15px
  }
  span{
    content:"";
    position:absolute;
    width:110px;
    height:120px;
    background:#F5D6B4;
    border-radius:50%;
    top:89px;
    left:70px;
    z-index:-1;
    box-shadow:150px 0 #F5D6B4
  }
</style>

```

## [02 Rook](https://cssbattle.dev/play/152)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/da397df0-e716-4639-8e0a-c81fad123b4e)

```html

<h1></h1>
<div></div>
<p></p>
<span></span>
<style>
  body{
    background:radial-gradient(circle at 160px 60px, #F7EC7D 5px,transparent 5px), radial-gradient(circle at 200px 60px, #F7EC7D 5px, transparent 5px),radial-gradient(circle at 240px 60px, #F7EC7D 5px, #62306D 5px);
  }
  h1::before,h1::after{
    content:"";
    position:absolute;
    background:#F7EC7D;
    width:90px;
    height:55px;
    top:60px;
    left:155px;
    border-radius: 0 0 10px 10px;
  }
  h1::after{
    width:30px;
    background:#62306D;
    top:45px;
    left:165px;
    border-radius: 0 0 5px 5px;
    box-shadow:40px 0 #62306D;
  }
  div,h1{
    margin:120px auto 74px ;
    background:#F7EC7D;
    width:61px;
    height:10.5px;
    border-radius:35px;
  }
  div{
    width:110px;
    margin:10px auto;
  }
  div::before,div::after{
    content:"";
    position:absolute;
    width:90px;
    height:65px;
    border:5px solid #62306D;
    background:#F7EC7D;
    top:130px;
    left:150px;
    z-index:-1;
  }
  div::after{
    width:140px;
    left:125px;
    top:215px;
    height:25px;
    border-radius:25px 25px 15px 15px
  }
  span{
    content:"";
    position:absolute;
    width:110px;
    height:120px;
    background:#62306D;
    border-radius:50%;
    top:89px;
    left:70px;
    z-index:-1;
    box-shadow:150px 0 #62306D
  }
</style>

```

## [03 Checkers](https://cssbattle.dev/play/153)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/63662d8c-6a6f-43f7-bfbb-d90d8c0f548f)

```html

<div></div>
<span></span>
<style>
  body{
    background:#E3516E
  }
  div{
    width:40px;
    height:40px;
    background:#FADE8B;
    margin:49.5px 92px;
    box-shadow:80px 0 #FADE8B, 160px 0 #FADE8B, 40px 40px #FADE8B, 120px 40px #FADE8B, 0 80px #FADE8B, 80px 80px #FADE8B, 160px 80px #FADE8B, 40px 120px #FADE8B, 120px 120px #FADE8B, 0 160px #FADE8B, 80px 160px #FADE8B, 160px 160px #FADE8B
  }
  span{
    width:20px;
    height:20px;
    border-radius:50%;
    background:#FADE8B;
    position:absolute;
    top:60px;
    left:150px;
    box-shadow: 80px 0 #FADE8B, -40px 40px #FADE8B, 40px 40px #FADE8B, 120px 40px #FADE8B, -40px 120px #FADE8B, 40px 120px #FADE8B, 120px 120px #FADE8B, 0 160px #FADE8B, 80px 160px #FADE8B;
  }
</style>

```

## [04 Poker Chip](https://cssbattle.dev/play/154)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/8749e7cf-edbc-4829-bec3-691458d1273e)

```html

<div></div>
<p></p>
<style>
  body{
    background:radial-gradient(circle, #0B2429 105px, #998235 105px);
  }
  body::before{
    content:"";
    position:absolute;
    width:160px;
    height:160px;
    border:15.5px solid #FCBE5C;
    border-radius:50%;
    top:55.5px;
    left:105.5px;
  }
  div,body::after,div::before,div::after{
    content:"";
    position:absolute;
    width:29px;
    height:200px;
    background:#0B2429;
    top:48px;
    left:185px;
  }
  body::after{
    transform:rotate(45deg);
    top:51px;
  }
  div::before{
    top:1.5px;
    left:0px;
    transform:rotate(90deg)
  }
  div::after{
    transform:rotate(-45deg);
    top:1px;
    left:0px
  }
  p{
    width:120px;
    height:120px;
    border:10px solid #FCBE5C;
    border-radius:50%;
    position:absolute;
    z-index:2;
    top:64.4px;
    left:130px;
  }
</style>

```

## [05 Snake and Ladders](https://cssbattle.dev/play/155)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/ffaf5262-e10d-46c8-bcb2-02242f9b38c4)

```html

<style>
  body{
    background:#6592CF;
  }
  body::before,body::after{
    content:"";
    position:absolute;
    width:30px;
    height:250px;
    border-radius:15px;
    background:#060F55;
    bottom:-10px;
    left:120px;
    box-shadow:130px 0 #060F55;
  }
  body::after{
    height:30px;
    width:150px;
    bottom:150px;
    box-shadow:0 60px #060F55, 0 120px #060F55;
  }
</style>

```

## [06 Chinese Checkers](https://cssbattle.dev/play/156)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/369ddc5f-21e8-434e-8504-f045766b5a5f)

```html

<style>
  body{
    background:#926927;
  }
  body::before{
    content:"";
    position:absolute;
    width:20px;
    height:20px;
    border-radius:50%;
    background:#F8B140;
    top:40px;
    left:190px;
    box-shadow:-15px 25px #F8B140, 15px 25px #F8B140, -90px 50px #F8B140, -60px 50px #F8B140, -30px 50px #F8B140, 0 50px #F8B140, 30px 50px #F8B140, 60px 50px #F8B140, 90px 50px #F8B140, -75px 75px #F8B140, -45px 75px #F8B140, -15px 75px #F8B140, 15px 75px #F8B140, 45px 75px #F8B140, 75px 75px #F8B140,-60px 100px #F8B140, -30px 100px #F8B140, 0 100px #F8B140, 30px 100px #F8B140, 60px 100px #F8B140, -75px 125px #F8B140, -45px 125px #F8B140, -15px 125px #F8B140, 15px 125px #F8B140, 45px 125px #F8B140, 75px 125px #F8B140, -90px 150px #F8B140, -60px 150px #F8B140, -30px 150px #F8B140, 0 150px #F8B140, 30px 150px #F8B140, 60px 150px #F8B140, 90px 150px #F8B140, -15px 175px #F8B140, 15px 175px #F8B140, 0 200px #F8B140;
  }
</style>

```

## [07 Monopoly](https://cssbattle.dev/play/157)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/00395880-5fe6-4d44-a84e-52765d3e08fb)

```html

<div></div>
<style>
  body{
    background:radial-gradient(circle at 170px 182px, #FFFBDA 10px, transparent 10px), radial-gradient(circle at 230px 182px, #E38F66 10px, transparent 10px), radial-gradient(circle at 230px 182px, #FFFBDA 20px, #E38F66 10px);
  }
  body::before{
    content:"";
    position:absolute;
    width:120px;
    height:90px;
    background:#FFFBDA;
    top:40px;
    left:140px;
    border-radius:60px 60px 0 0;
  }
  div{
    width:180px;
    height:20px;
    border-radius:10px;
    background:#FFFBDA;
    margin:130.5px auto;
  }
  div::before,div::after{
    width:40px;
    height:40px;
    background:#FFFBDA;
    content:"";
    position:absolute;
    border-radius:20px 20px 20px 0px;
    transform:rotate(45deg);
    top:220px;
    left:155px
  }
  div::after{
    transform:rotate(-135deg);
    left:205px;
  }
</style>

```

## [08 Clubs](https://cssbattle.dev/play/158)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/c91ba508-741e-40e8-9608-6a77423b67ed)

```html

<div></div>
<style>
  body{
    background:#4F77FF;
  }
 div{
   background:#1038BF;
   position:absolute;
   width:100px;
   height:100px;
   border-radius:50%;
   top:50px;
   left:150px;
   box-shadow:45px 70px #1038BF, -45px 70px #1038BF;
 }
  div::before{
    content:"";
    position:absolute;
    border-left: 25px solid transparent;
    border-right: 25px solid transparent; 
    border-bottom: 35px solid #1038BF;
    top:165px;
    left:25px;
  }
  div::after{
    width:11px;
    height:35px;
    content:"";
    position:absolute;
    background:#1038BF;
    top:140px;
    left:44px;
  }
</style>

```
