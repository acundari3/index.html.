
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>MY GAMING TV</title>
<style>
*{box-sizing:border-box}
body{
 margin:0;
 background:#080808;
 color:white;
 font-family:Arial,sans-serif;
 padding:30px;
}
h1{font-size:34px;letter-spacing:3px}
p{color:#999}
.grid{
 display:grid;
 grid-template-columns:repeat(2,minmax(0,1fr));
 gap:18px;
 max-width:900px;
}
button{
 background:#202020;
 color:white;
 border:1px solid #444;
 border-radius:16px;
 padding:35px 12px;
 font-size:21px;
 font-weight:bold;
 cursor:pointer;
}
button:focus{outline:3px solid white}
button:hover{background:#333}
small{display:block;color:#aaa;margin-top:12px}
</style>
</head>
<body>
<h1>MY GAMING TV</h1>
<p>TU CENTRO DE ENTRETENIMIENTO</p>
<div class="grid">
<button onclick="location.href='https://www.youtube.com/tv'">
▶ YOUTUBE<small>Ver vídeos</small></button>
<button onclick="location.href='https://www.xbox.com/play'">
🎮 XBOX<small>Cloud Gaming</small></button>
<button onclick="location.href='https://play.google.com/store/apps'">
🕹️ JUEGOS<small>Explorar juegos</small></button>
<button onclick="location.href='https://www.google.com'">
⚙ AJUSTES<small>Más opciones</small></button>
</div>
</body>
</html>
