# Rotate battle

## [01 Root Learn](https://cssbattle.dev/play/125)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/332394eb-3200-4432-8335-ce33633c963a)

```html

<div></div>
<p></p>
<span></span>
<style>
  body{
    background: #EFF2F1;
  }
  body::before, body::after,div::before, div::after, p::before,p::after,p,span{
    content:"";
    position:absolute;
  }
  body::before, body::after{
    width:130px;
    height:90px;
    background: #1C1C1C;
    border-radius: 0 50px 50px 0;
    top:60px;
    left:130px
  }
  body::after{
    background:#EFF2F1;
    width:50px;
    height:60px;
    top:75px;
    left:170px
  }
  div::before{
    background:#1C1C1C;
    width:58px;
    height:7px;
    top:233px;
    left:232px;
    box-shadow: -122px 0 #1C1C1C, -122px -2px #1C1C1C, -100px 0 #1C1C1C,-100px -2px #1C1C1C, -122px -173px #1C1C1C, -122px -170.5px #1C1C1C;
  }
  div::after,p{
    background:#1C1C1C;
    width:40px;
    height:90px;
    top:150px;
    left:130px;
  }
  p{
    height:92px;
    transform:skewX(30deg);
    top:131px;
    width:46px;
    left:203.9px
  }
  p::before,p::after{
    border-left: 30px solid transparent;
    border-right: 30px solid transparent; 
    border-bottom: 22px solid #1C1C1C;
    left:3px;
    top:64px;
  }
  p::after{
    border-left: 54px solid transparent;
    border-right: 30px solid transparent; 
    border-bottom: 25px solid #1C1C1C;
    left:-118px;
    top:60px
  }
  span{
    border-left: 35px solid transparent;
    border-right: 20px solid transparent;
    border-top: 20px solid #1C1C1C;
    top:69px;
    left:110px
  }
</style>

```

## [02 Letter A](https://cssbattle.dev/play/126)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/31a148c5-0e3d-4217-9641-0cdc430ae107)

```html

<div></div>
<style>
  body{
    background: #62306D;
  }
  body::after, body::before,div::before,div::after{
    position:absolute;
    width:42px;
    height:140px;
    content:"";
    background:#FEF9CA;
    transform:skewX(-20deg);
    top:80px;
    left:149px;
  }
  body::after{
    z-index:-2;
    transform:skew(20deg);
    background:#C5B732;
    left:209px
  }
  div::before,div::after{
    width:52px;
    height:50px;
    top:169.5px;
    left:150px;
    background:#E38F66;
    transform:skewX(-40deg);
  }
  div::after{
    z-index:-1;
    background:#AA445F;
    transform:skewX(40deg);
    left:198px
  }
</style>

```

## [03 Letter I](https://cssbattle.dev/play/127)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/124f06d6-443c-4fcc-ae79-f30660c7d781)

```html

<div></div>
<style>
  body {
    background: radial-gradient(
        circle at 125px 215px,
        #fade8b 15px,
        transparent 0
      ), radial-gradient(circle at 275px 85px, #fade8b 15px, #e3516e 0);
  }
  body::after,body::before,div{
    content:"";
    position:absolute;
    background:#FADE8B;
  }
  body::before{
    width:100px;
    height:30px;
    border-radius:15px;
    top:70px;
    left:150px;
    box-shadow:0 130px #FADE8B;
  }
  body::after{
    width:44px;
    height:102px;
    top:100px;
    left:177.5px;
  }
  div{
    height:100px;
    background:#E3516E;
    width:100px;
    border-radius:10px;
    top:100px;
    left:85px;
    z-index:1;
    box-shadow:130px 0 #E3516E;
  }
</style>

```

## [04 Letter N](https://cssbattle.dev/play/128)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/901f4a58-bedb-4515-8fb1-e5fe4f0f8ba8)

```html

<div></div>
<style>
  body {
    background:#998235;
  }
  body::after,body::before{
    content:"";
    position:absolute;
    background:#0B2429;
    bottom:0px;
    width:40px;
    height:230px;
    left:135px;
  }
 body::before{
   left:225px;
   bottom:70px;
   z-index:-1;
 }
  div{
    position:absolute;
    background:#FCBE5C;
    width:42px;
    height:160px;
    transform:skewX(20deg);
    top:70px;
    left:179.5px
  }
</style>

```

## [05 Letter B](https://cssbattle.dev/play/129)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/68dc5405-4727-45cb-aeb5-9678ef767435)

```html

<style>
  body {
    background:#6592CF;
  }
  body::after{
    content:"";
    position:absolute;
    background:#060F55;
    top:80px;
    width:100px;
    height:78px;
    left:110px;
    border-radius:0 40px 40px 0;
    box-shadow:0 62px #060F55, 40px 0 #2E3B9F, 40px 62px #2E3B9F, 80px 0 #515DBD, 80px 62px #515DBD;
  } 
</style>

```

## [06 Letter O](https://cssbattle.dev/play/130)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/260b03b6-ff1d-4201-a59e-f88edc02e135)


```html

<style>
  body {
    background:#926927;
  }
  body::after,body::before{
    content:"";
    position:absolute;
    background:#6D480A;
    top:70px;
    width:60px;
    height:120px;
    left:160px;
    border:20px solid #fff;
    border-radius:30px;
    box-shadow:-20px 0 #6D480A;
  } 
  body::after{
    box-shadow:none;
    border:0px;
    background:#926927;
    border-radius:10px;
    top:90px;
    width:40px;
    left:180px;
  }
</style>

```

## [07 Letter W](https://cssbattle.dev/play/131)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/6830bf39-4c9c-46e0-858f-d7bf1f08dece)

```html

<div></div>
<style>
  body {
    background:#E38F66;
  }
  body::before{
    content:"";
    position:absolute;
    top:70px;
    width:30px;
    height:100px;
    left:95px;
    background:#62306D;
    border-radius:30px 30px 0 0;
    box-shadow: 90px 0 #62306D, 180px 0 #FFFBDA;
  } 
  div::before,div::after{
    box-sizing:border-box;
    height:30px;
    width:60px;
    content:"";
    position:absolute;
    background:#E38F66;
    border-radius:0 0 30px 30px;
    top:170px;
    left:125px;
    box-shadow:90px 0 #E38F66
  }
  div::after{
    top:170px;
    left:95px;
    width:119px;
    height:60px;
    background:#62306D;
    border-radius:0 0 62px 62px;
    z-index:-1;
    box-shadow:90px 0 #FFFBDA;
  }
</style>

```

## [08 Letter S](https://cssbattle.dev/play/132)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/8e772568-69c5-40ae-9db9-13720e82b1c5)

```html

<div></div>
<style>
  body {
    background:#4F77FF;
  }
  body::before,div,div::before{
    content:"";
    position:absolute;
    top:69.5px;
    width:240px;
    height:50.5px;
    left:80px;
    background:#FFFFFF;
    border-radius:10px;
    box-shadow:20px -20px #1038BF, 0 110px #FFFFFF, -20px 130px #1038BF;
  } 
 div{
   width:240px;
   height:20px;
   background:#fff;
   top:140px;
   border-radius:10px;
   box-shadow:none;
 }
  div::before{
    top:-30px;
    left:0px;
    box-shadow:none;
    width:20px;
    height:40px;
    border-radius:0px;
    box-shadow:220px 40px #FFFFFF;
  }
</style>

```
