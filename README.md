<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="estilosopen.css">
    <title>"Disposición de elementos en CSS" </title>
</head>
<body >
    <video class="video" playsinline autoplay muted loop controls>
        <source src="/imagenes/WhatsApp Video 2022-09-21 at 14.46.05.mp4"> </video>

<div class="header">
<h1>TEXTO EN VIDEO</h1>
</div>
  

</body>

</html>


Css

*{
    padding: 0%;
    margin:0%
}

html{
    font-family: Arial, Helvetica, sans-serif;
    color: white;
}
.video{
 width: 100vw;
 height: 100vh;
 object-fit: cover;
 position: fixed;
}

.header{
height: 100vh;
position: relative;
text-align: center;
display: flex;
justify-content: center;
align-items: center;
}
