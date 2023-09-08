# Initial Battle

## [01 Portal](https://cssbattle.dev/play/159)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/9d6b8f76-610d-4b33-bb6a-abe950aea609)

```html

<div></div>
<style>
  body{
    background:#F5D6B4;
  }
  div {
    width: 51px;
    height: 50px;
    background: #D86F45;
    margin:25px auto;
    box-shadow:49px 50px #D86F45, -49px 50px #D86F45, 0 50px #D86F45, -99px 100px #D86F45, -49px 100px #D86F45, 0 100px #D86F45, 49px 100px #D86F45, 99px 100px #D86F45, -49px 150px #D86F45,0 150px #D86F45, 49px 150px #D86F45, 0 200px #D86F45
  }
</style>

```

## [02 Donut](https://cssbattle.dev/play/160)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/63452787-071f-4252-9db1-3aef5f25151b)

```html

<div></div>
<style>
  body{
    background:#62306D;
  }
  div {
    width: 120px;
    height: 120px;
    border-radius:50%;
    border: 40px solid;
    margin:50px auto;
    transform:rotate(-45deg);
    border-color: #E38F66 #F7EC7D #F7EC7D;
  }
</style>

```

## [03 Converge](https://cssbattle.dev/play/161)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/83589063-37e7-4d25-ae83-3c8c55ad3f07)

```html

<div></div>
<style>
  body{
    background:#E3516E;
  }
  body::before{
    content:"";
    width: 184px;
    height: 184px;
    background:#FADE8B;
    position:absolute;
    top:58px;
    left:108px
  }
  div::before,div::after{
    position:absolute;
    z-index:1;
    width:29.5px;
    content:"";
    height:300px;
    background:#E3516E;
    transform:rotate(45deg);
    top:5px;
    left:180px;
  }
  div::after{
    top:-5px;
    transform:rotate(-45deg);
  }
</style>

```

## [04 Chevron](https://cssbattle.dev/play/162)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/d16f5ba5-11fc-46d6-b94c-13013b7b00eb)

```html

<div></div>
<style>
  body{
    background:#998235;
  }
  div::before,div::after{
    position:absolute;
    z-index:1;
    width:70px;
    content:"";
    height:140px;
    background:#0B2429;
    transform:rotate(45deg);
    top:80px;
    left:140px;
  }
 div::after{
   transform:rotate(-45deg);
   background:#FCBE5C;
   z-index:-1;
   left:189px
 }
</style>

```

## [05 Missing Piece](https://cssbattle.dev/play/163)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/37963edd-b766-4249-b5dd-b1d91c994450)

```html

<div></div><p></p><h1></h1><style>
  body{background:#D669EC}
  div::before{
    content:"";
    position:absolute;
    background:#FDFBF8;
    width:55px;
    height:55px;
    top:40px;
    left:89.5px;
    box-shadow:45px 45px #FDFBF8, 120px 45px #FDFBF8, 0 165px #FDFBF8, 45px 120px #FDFBF8, 165px 0 #FDFBF8;
  }p,h1{
    width:65px;
    height:76px;
    background:#FDFBF8;
    transform:rotate(45deg);
    position:absolute;
    top:35px;
    left:106px;
  }h1{
    transform:rotate(-45deg);
    top:30px;
    left:228px;
    box-shadow:-170px -0px #FDFBF8;
  }
</style>

```

## [06 Rangoli](https://cssbattle.dev/play/164)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/46dce1c7-e41a-45a9-a6ff-425e9a01ae97)

```html

<p></p>
<h1></h1>
<h2></h2>
<h3></h3>
<style>
  body{
    background:#66284A
  }
  p,h1,h2,h3{
    width:60px;
    height:60px;
    border-radius:50%;
    border:20px solid;
    border-color:#F0CD48 #66284A #F0CD48 #F0CD48;
    position:absolute;
    left:150px;
    top:78.5px;
    }
  p{    
    transform:rotate(135deg);
    top:24px;
  }
  h1{
    transform:rotate(45deg);
    left:90px;
    border-color:#D86F45 #66284A #D86F45 #D86F45;
  }
  h2{
    transform:rotate(-45deg);
    top:140px;
    border-color:#FDFBF8 #66284A #FDFBF8 #FDFBF8;
  }
  h3{
    transform:rotate(-135deg);
    left:210px;
    top:81px;
    border-color:#D669EC transparent #D669EC #D669EC;
  }
</style>

```
