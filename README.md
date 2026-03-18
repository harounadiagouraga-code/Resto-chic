<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<title>Menu Restaurant carré </title>
<style>

body{
    margin:0;
    font-family: "Georgia";
    background-image: url("https://c8.alamy.com/compfr/ae2456/centre-ville-dakar-senegal-ae2456.jpg");
    background-size:cover  ;
    background-position: center;
    background-attachment: fixed;
}

.overlay{
    background: rgba(0,0,0,0.7);
    min-height: 100vh;
    padding:50px;
}

.menu{
    max-width:700px;
    margin:auto;
    text-align:center;
    color: white;
}

h1{
    font-size:50px;
    color:white;
    letter-spacing:30px;
}

h2{
    margin-top:30px;
    color:yellow;
    border-bottom:1px solid #d4af37;
    padding-bottom:6px;
}

.item{
    display:flex;
    justify-content:space-between;
    margin:15px;
    font-size:20px;
}

.item span{
    color:yellow;
}

</style>
</head>
<body>

<div class="overlay">
<div class="menu">

<h1>
<span style="color: blue;">Resto</span>
<span style="color:white;">Carré</span>
</h1>

<h2>Entrées</h2>
<div class="item">
<p><b>Salade de fruit</b></p>
<span>1 000 f</span>
</div>

<div class="item">
<p><b>cappuccino</b></p>
<span>1 000 f</span>
</div>
<div class="item">
<p><b> Thé vert de chine</b> </p>
<span>500 f</span>
</div>

<h2>Plats</h2>
<div class="item">
<p><b>maffé</b></p>
<span>1 500f</span>
</div>

<div class="item">
<p><b>tiébou yap</b></p>
<span>1 500f</span>
</div>

<h2>Desserts</h2>
<div class="item">
<p><b>Tiakri</b></p>
<span>500 f</span>
</div>

<div class="item">
<p><b>guertté tiaff</b></p>
<span>50f</span>
</div>

</div>
</div>

</body>
</html>
