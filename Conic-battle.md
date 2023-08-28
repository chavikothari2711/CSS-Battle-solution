# Connic Battle

## [01 Equals](https://cssbattle.dev/play/31)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/080d7d98-79f3-4498-9cc9-4c772513eb83)

```html

<div></div>
<div></div>
<style>
  body{
    display:flex;
    gap:50px;
    background:#AA445F;
    justify-content:center;
    align-items:center;
  }
  div {
    width: 100px; /* half of width*/
    height: 200px; 
    border-radius: 100px 0 0 100px;
    background-color: #F7EC7D;
  }
  div:nth-child(2){
    transform:rotate(180deg);
    background:#E38F66;
  }
</style>

```

## [02 Band-aid](https://cssbattle.dev/play/32)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/fd02fee7-946e-4cc6-8ab6-1dcdd8e60f1b)

```html

<div class="center"></div>
<div class="box"></div>
<div class="box green"></div>
<style>
  body{
    background:#fff;
    display:grid;
  }
  .center{
    place-self:center;
    transform:rotate(45deg);
    width: 50px;
    height: 50px;
    background: #FBE18C;
  }
  .box{
    width:50px;
    height:200px;
    transform:rotate(-45deg);
    position:absolute;
    background:#F3AC3C;
    z-index:-1;
    top:50px;
    left:175px;
  }
  .green{
    transform:rotate(45deg);
    background:#A3A368;
  }
</style>

```
