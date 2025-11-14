# Project introduction
This project was built using HTML and CSS markup languages.
---
## Demo
click [here](https://fatemeh798.github.io/visit-card/) to see demo project
---
Program codes

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="./style/style.css">
</head>
<body>
    <div class="containar">
        <img class="logo" src="./images/logo.jpg" alt="تصویر لوگو">
        <p class="p1">Fatemeh Karimi</p>
        <p class="p2">please follow me on social media</p>
         <div class="social">
            <img src="./images/instagram.png" alt="لوگو اینستاگرام">
            <img src="./images/youtube.png" alt="لوگو یوتیوب">
            <img src="./images/facebook.png" alt="لوگو فیس بوک">
    </div>

    </div>
   
    
</body>
</html>

```

```css
body{
    background-color: lightgray;
    font-family: sans-serif;
}
.containar{
    width: 500px;
    height: 400px;
    background-color: #ffff;
    margin: auto;
    margin-top: 80px;
    border-radius: 10px;
    box-sizing: border-box;
    padding: 25px 0;
    border: 1px solid lightgray;
    box-shadow: 0 0 15px #827f7f;
}
.logo{
    width: 150px;
    border:2px dotted black;
    border-radius: 50%;
    display: block;
    margin: auto;
}
.p1{
    color: #4c4d4c;
    font-size: 25px;
    border-bottom: 5px solid lightgray;
    width: 180px;
    margin: 25px auto;
    
}
.p2{
    text-align: center;
    text-transform: capitalize;
    color:#4c4d4c;
}
.social{
    height: 60px;
    background-color: lightgray;
    text-align: center;
}
.social img{
    width: 40px;
    margin: 8px;
}
```