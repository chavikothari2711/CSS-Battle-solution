# Pilot battle

## [01 Simply Square](https://cssbattle.dev/play/1)

![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/05ecb72c-feb1-4a65-9cea-cd73b27cc6e4)

```html
<div></div>
<style>
  *{
    margin:0;
   background:#5d3a3a;   
  }
  div {
    width: 200px;
    height: 200px;
    background: #b5e0ba;
  }
</style>
```

## [02 Carrom](https://cssbattle.dev/play/2)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/310b49b5-5958-497a-8035-a9139ff998a1)

```html

<div class="top-left-square"></div>
<div class="top-right-square"></div>
<div class="bottom-left-square"></div>
<div class="bottom-right-square"></div>
<style>
  *{
    margin:0;
    background: #62374e;
  }
  div{
    position:absolute;
    width: 50px;
    height: 50px;
    background: #fdc57b;
  }
  .top-left-square{
    left:50px;
    top:50px;    
  }
  .top-right-square{
    right:50px;
    top:50px;    
  }
  .bottom-left-square{
    left:50px;
    bottom:50px;    
  }
  .bottom-right-square{
    right:50px;
    bottom:50px;    
  }
</style>

```

## [03 Push Button](https://cssbattle.dev/play/3)
![image](https://github.com/chavikothari2711/CSS-Battle-solution/assets/61689704/9e65ad70-65eb-43ad-81bc-63876db1205e)

```html

<div class="rectange">
  <div class="circle"></div>
  <div class="circle-2"></div>
</div>

<style>
  body{
    display: grid;
    place-items: center;
    background:#6592CF;
  }
  .rectange {
    display:grid;
    place-items:center;
    width: 300px;
    height: 150px;
    background: #243D83;
  }
  .circle{
    width: 50px;
    height: 50px;
    background: #eeb850;
    border-radius: 50%;
    border: solid 50px #243d83;
    z-index: 1;
  }
  .circle-2{
    position: absolute;
    width: 50px;
    height: 50px;
    background: transparent;
    border-radius: 50%;
    border: solid 100px #6592cf;
  }
</style>

```
