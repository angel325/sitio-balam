<!DOCTYPE html>
<html lang="es">
<head>
<title>Compra Venta de autos de lujo</title>
<meta charset="UTF-8">
<meta name="description" content="Sitio de ejemplo Chester Airport"/>
<meta name="keywords" content="Chester,Aeropuerto,HTML,CSS"/>
<meta name="author" content="Balam"/>


<meta name="copyright" content="ICCHF"/>

<meta name="robots" content="noindex"/>

<meta http-equiv="cache-control" content="no-cache"/>


<link rel="stylesheet" type="text/css" href="style.css"/>


<link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">


<style>

*{
    margin: 0px;
    padding: 0px;
}

body{
    color:#000;
    font-size: 3vh;
    font-family: 'Roboto', sans-serif;
    background-color: #004990;
}
.menu{
width: 100%;
    height: 60px;
    background-color: #0b2343;
    display: inline-block;   
    position: fixed;
    cursor: pointer;
    top: 0px;
    }

.boton{
    width: 25%;
    float: left;
     text-align: center;
    line-height: 60px;
    color: #fff;
    text-decoration: none;
}

.boton:hover{
    background-color: #3e8e41;
}
.boton:active{
    background-color: #04152c;
    color: #3e8e41;
}

.columna1Promo1 {
    width:75%;
    float:left;
    margin-top: 60px;
}
.columna2Promo1 {
    width:25%;
    float: right;
    margin-top: 60px;
    color: white;
}
.llegoTour{
    font-family: 'Times New Roman', Times, serif;
    font-weight: bold;
    margin: 30% 0% 10% 10%;
    font-size: 3.5vw;
}
.ver{
    background-color: #f44336; 
    border: 2px solid #f44336;
    cursor: pointer;
    margin:  0% 0% 10% 10%;
    padding: 2vh 3vw;
    border-radius: 6%;
    font-family: 'Roboto', sans-serif;
    color: white;
    font-size: 1.2vw;
    font-weight: lighter;
    text-decoration: none;
    transition-property: background-color;
    transition-duration: .7s;
}
.ver:hover {
    background-color: white;
    color: black;
}
.lugaresTour{
    margin: 10% 0% 0% 10%;
    font-family: 'Times New Roman', Times, serif;
    font-size: 2vw;
}
.desdeTour{
    margin: 5% 0% 0% 10%;
    font-size: 1.3vw;
}

/*-----INICIA PROMO2-----*/

.columna1promo2{
    clear: both; /*-----PARA INICIAR UNA NUEVA FILA VISUALMENTE-----*/

    width: 36%;
    background-color: #ffe8ae;
    height: 55vh;

    float: left;
}
.imgPromo2{
    border-radius: 50%;
    margin-top: 7%;
    /*--ALINEA A LA DERECHA--*/
    float: right;
}
.columna2Promo2{
    width: 64%;
    background-color: #ffe8ae;
    height: 55vh;

    float: left;
}
.inspirate{
    font-family: 'Times New Roman', Times, serif;
    font-weight: bold;
    margin: 12% 0% 0% 15%;
    font-size: 4vw;
}
.textoPromo2{
    font-size: 2vw;
    margin: 0% 0% 0% 15%;
}
.irVerde{
    background-color: #4caf50; 
    border: 2px solid #4caf50;
    cursor: pointer;
    padding: 1.7% 2.5%;
    border-radius: 50%;
    color: white;
    font-size: 1.2vw;
    font-weight: lighter;
    text-decoration: none;
    transition-property: background-color;
    transition-duration: .7s;
}
.irVerde:hover{
    background-color: white;
    color: black;
}

/*-----INICIA PROMO3-----*/

.columna1Promo3{
    clear: both;

    width: 50%;
    background-color: #cc2f4d;
    height: 72vh;

    float: left;
}
.columna2Promo3{
    width: 50%;
    background-color: #cc2f4d;
    height: 72vh;

    float: left;
}
.guadalajara{
    font-family: 'Times New Roman', Times, serif;
    font-weight: bold;
    margin: 17% 0% 0% 0%;
    font-size: 4vw;
    color: white;
}
.desde1{
    color: white;
    font-size: 2.2vw;
    
}
.textoPromo3{
    font-size: 2vw;
}
.irAzul{
    background-color: #6cadea;
    border: 2px solid #6cadea;
    cursor: pointer;
    padding: 1.7% 2.5%;
    border-radius: 50%;
    color: white;
    font-size: 1.2vw;
    font-weight: lighter;
    text-decoration: none;
    transition-property: background-color;
    transition-duration: .7s;
}
.irAzul:hover{
    background-color: white;
    color: black;
}

.columna1Promo4{
    clear: both;

    width: 45%;
    background-color:black;
    height: 40vh;

    float: left;
}
.imgPromo4{
    margin-top: 4%;
    /*--ALINEA A LA DERECHA--*/
    float: right;
}
.columna2Promo4{
    width: 20%;
    background-color:black;
    height: 40vh;
    color: white;
    font-size: 1.7vw;

    float: left;
}
.texto1Promo4{
margin: 25% 0% 0% 10%;
}
.columna3Promo4{
    width: 35%;
    background-color:black;
    height: 40vh;
    color: white;
    font-size: 1.7vw;

    float: left;
}
.texto2Promo4{
    margin: 20% 0% 0% 2%;
}
.irAmarillo{
    background-color: #e79800;
    border: 2px solid #e79800;
    cursor: pointer;
    padding: 3% 4%;
    border-radius: 50%;
    color: white;
    font-size: 1.2vw;
    font-weight: lighter;
    text-decoration: none;
    transition-property: background-color;
    transition-duration: .7s;
}
.irAmarillo:hover{
    background-color: white;
    color: black;
}

/*-----INICIA PROMO5-----*/

.columna1Promo5{
    clear: both;

    width: 57%;
    background-color: #f19218;
    height: 72vh;

    float: left;
}
.columna2Promo5{
    width: 43%;
    background-color: #f19218;
    height: 72vh;

    float: left;
}
.cancun{
    font-family: 'Times New Roman', Times, serif;
    font-weight: bold;
    margin: 17% 0% 0% 15%;
    font-size: 4vw;
    color: white;
}
.desde2{
    color: white;
    font-size: 2.2vw;
    margin: 0% 0% 0% 15%;
}
.textoPromo5{
    font-size: 2vw;
    margin: 0% 0% 0% 15%;
}
.irNegro{
    background-color:rgba(0,0,0,.9);
    border: 2px solid rgba(0,0,0,.8);
    cursor: pointer;
    padding: 2.5% 3.5%;
    border-radius: 50%;
    color: white;
    font-size: 1.2vw;
    font-weight: lighter;
    text-decoration: none;
    transition-property: background-color;
    transition-duration: .7s;
}
.irNegro:hover{
    background-color: white;
    color: black;
}
</style>

</head>

<div class="menu">
<a class="boton" href="#" target="_self">Menú</a>
    <a class="boton" href="#" target="_self">Consultar</a>
    <a class="boton" href="#" target="_self">Asesoria</a>
    <a class="boton" href="#" target="_self">Costos</a>
</div>

<!--INICIA PROMO 1-->
<div class="columna1Promo1">
    <video width="100%" src="carros.mp4" autoplay loop>
</div>
<div class="columna2Promo1">
    <p class="llegoTour">
        ¡Llegó el 
        <br>WordTour!</p>
    <p class="verTour">
        <a class="ver" href="#">Ver</a>
    </p>
    <p class="lugaresTour">
        Roma - Berlín - Tokio
    </p>
    <p class="desdeTour">
        Desde $2,459 USD
    </p>
</div>

<!--INICIA PROMO 2-->
<div class="columna1promo2">

    <img class="imgPromo2" src="imagenPromo2.jpg" height="83%"/>

</div>

<div class="columna2Promo2">
    <p class="inspirate">
        ¡Inspírate!
    </p>
    <p class="textoPromo2">
        Entra a nuestro blog de viajes y encuentra tu inspiración para volar.
        <a href="#" class="irVerde">Ir</a>
    </p>
</div>

<!--INICIA PROMO 3-->
<div class="columna1Promo3">
    <img src="imagenPromo3.jpg" height="100%"/>
</div>

<div class="columna2Promo3">
    <p class="guadalajara">
        Guadalajara
    <p class="desde1">Desde $2,599 MXN</p>
    </p>
    <p class="textoPromo3">
        Una tarde de tortas ahogadas, caminata en el centro, un tejuino...¿qué más necesitas?
        <a href="#" class="irAzul">Ir</a>
    </p>
</div>

<!--INICIA PROMO 4-->
<div class="columna1Promo4">
    <img class="imgPromo4" src="imagenPromo4.png" height="80%"/>
</div>
<div class="columna2Promo4">
    <p class="texto1Promo4">
    ¡Gratis un día! sólo si<br>
    rentas un auto con<br>
    nosotros!
    
    </p>
</div>
<div class="columna3Promo4">
    <p class="texto2Promo4">
    <a href="#" class="irAmarillo">Ir</a>
    </p>
</div>

<!--INICIA PROMO 5-->
<div class="columna1Promo5">
    <img src="imagenPromo5.jpg" height="100%"/>
</div>

<div class="columna2Promo5">
    <p class="cancun">
        Cancún
    <p class="desde2">Desde $3,199 MXN</p>
    </p>
    <p class="textoPromo5">
        Nada como los pies hundidos en la arena, esa persona especial y el amanecer...
        <a href="#" class="irNegro">Ir</a>
    </p>
</div>

<!--CIERRA BODY (CONTENIDO VISIBLE)-->
</body>

<!--CIERRA HTML5-->
</html>
