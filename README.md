# calculadora-binaria
convierte un numero a binario , octal y hexadecimal 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">


  <form id="cal" name="calculadora" method="POST">
    <title>ES8 Project</title>
    <h1>calculadora binaria , octal y hexadecimal</h1>
    
 <label>numero</label>
 <input type="number" id="bin" autofocus
    placeholder="ingrese un numero">
<button onclick="borrar();"> borrar</button> <br>
   <br><br>
   <p1> elija una de las transfomaciones<br>
   <br>
 <input type="button" name="name" value="Binario" onclick="bina();">
 <input type="button" name="name" value="Octal" onclick="oct();">
     <input type="button" name="name" value="Hexadecimal" onclick="hexa();">
    <br><br>
     <p1> La conversión que eligió es: <span id="resultado"></span></p1>
     </form>
    
     <link rel="stylesheet" href="style.css">
  <script src="//unpkg.com/systemjs@0.19.47/dist/system.js"></script>
</head>

<body>
  <script src="config.js"></script>
</body>
</html>
