<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Media Query</title>
    <style>

        /* declaraçoes gerais*/

    * {
    margin: 0px;
    padding: 0px;
    font-family: Arial, Helvetica, sans-serif;
}

html, body {
    width: 100vw;
    height: 100vh;
    background-color: blue;
    background-size: contain ;
    background-repeat: no-repeat;
}

h1 {
    color: white;
    text-shadow: 5px 5px 0px blue;
    padding: 10px ;
}

/* declaraçoes retrato*/
@media screen and (orientation: portrait) {
    body {
    background-image: url(imagens/cev-portrait1.png) ;
    background-position: center bottom;
}
}

/* declaraçoes paisagem*/
@media screen and (orientation: landscape) {
    body {
    background-image: url(imagens/cev-landscape1.png);
    background-position: left bottom;
    background-color:blue ;
}
}
</style>
</head>
<body>
    <h1>Mude a orientação do seu dispositivo</h1>
</body>
</html>

 
