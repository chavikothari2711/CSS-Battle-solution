# Transition Battle

## [01 Baby](https://cssbattle.dev/play/42)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/5478fdf1-e933-446b-b993-e85982e9e385)

```html

<div class="face">
  <div class="hair"></div>
  <div class="hair b"></div>
  <div class="eye"></div>
  <div class="eye two"></div>
  <div class="mouth"></div>
</div>
<style>
  body{
    background: #293462;
    display:flex;
    justify-content:center;
    align-items:center;
  }
  .face{
    background:#FE5F55;
    height:200px;
    width:200px;
    border-radius:100px 100px 50px 50px;
    overflow:hidden;
  }
  .eye{
    position:absolute;
    z-index:2;
    top:140px;
    left:120px;
    width:60px;
    height:60px;
    border-radius:50%;
    background:#FFF1C1;
  }
  .hair{
    background:#FFF1C1;
    height:50px;
    width:100px;
    border-radius:50px 50px 0 0;
    transform:rotate(135deg);
    margin-left:18px;
    margin-top:-8px;
  }
  .b{
    transform:rotate(-135deg);
    margin-left:83px;
    margin-top:-50px;
  }
  .two{
    left:220px;
  }
  .mouth{
    width:40px;
    height:10px;
    border-radius:5px;
    background:#FFF1C1;
    position:absolute;
    top:220px;
    left:180px;
  }
</style>

```

## [02 Wrench](https://cssbattle.dev/play/43)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/903ebfa1-815e-490b-8bca-e9981f04e5db)

```html

<div></div>
<div></div>
<style>
  body {
    background: #6592CF;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  div {
    width: 70px;
    height: 242px;
    box-sizing: border-box;
    border: 30px solid #243D83;
    border-left: 0;
    border-top-right-radius: 100px;
    border-bottom-right-radius: 100px;
    margin-top: 2px;
  }
  div:nth-child(2) {
    transform: scaleX(-1);
    margin-left: -30px;
  }
</style>

```

## [03 Stripes](https://cssbattle.dev/play/44)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/fb43173a-3901-4ce7-90e1-c8e370ee7f8b)

```html

<div class="circle"></div>
<div class="wrap">
  <div class="stripes"></div>
  <div class="stripes"></div>
  <div class="stripes"></div>
  <div class="stripes"></div>
  <div class="stripes"></div>
</div>
<div class="circle right"></div>
<style>
 body{
    background: #1A4341;
  }
  .wrap{
    display:flex;
    flex-direction:column;
    gap:20px;
    justify-content:center;
    align-items:center;
    width: 200px;
    height: 180px;
    margin: 60px auto;
  }
  .circle{
    background:#1A4341;
    width:300px;
    height:300px;
    border-radius:50%;
    position:absolute;
    top:0px;
    left:-150px;
  }
  .right{
    left:250px;
  }
  .stripes{
    background:#F3AC3C;
    width:1000;
    height:20px;
  }
</style>

```

