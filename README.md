# Hello-World-HTML-JS
Mi primer repositorio en GitHub 

#Recetario
<head>
    <title>Modificación de un párrafo de texto</title>
    <script>
    function modificarParrafo(){
        document.getElementById("párrafo").innerHTML="Texto Modificado"
    </script>
</head>

<body>
    <p Id="párrafo">Este es un párrafo convencional</p>
    <button onclick="modificarParrafo();">Modificar Parrafo</button>
<\body>




#Color text 

<head>
    <title>Modificar color de texto</title>
    <script>
        function modificarColorTexto()
                document.getElementById("titulo").innerHTML("Text Modificado").style.color="Tomato";
document.getElementById("parrafo1").style.color="LimeGreen";
document.getElementById("parrafo2").style.color="Red";
document.getElementById("division").style.color="Blue";
    </script>
</head>

<body>
    <h1 Id="titulo">Cambiar color de texto<h1>
    <p id="parrafo1">Este es un párrafo de texto convencional</p>
    <p id="parrafo2">Este es otro párrafo de texto</p>
    <div id="division">Texto de una división</div>
    <button onclick="modificarColorTexto();"Modificar color texto</button>
    
    




#Obtener texto de una caja ¿de cartón?

<head>
    <title>Validación de formularios</title>
    <script>
        function modificarColorTexto(){
                document.getElementById("titulo").innerHTML("Text Modificado").style.color="Tomato";
document.getElementById("parrafo1").style.color="LimeGreen";
}
        function nombreusuario();{
        let nombre=document.getElementById("nombre del usuario").value;
document.getElementById("resultado").innerHTML=("<h1>Bienvenido"+nombre+"</h1>
    </script>
</head>

<body>
    <h1 Id="titulo">Cambiar color de texto<h1>
    <p id="parrafo1">Este es un párrafo de texto convencional</p>
    <button onclick="modificarColorTexto();"Modificar color texto</button>
    <label>Nombre Usuario</label><input type="text" id="nombreusuario()">
    <label>Contraseña</label><input type="password" id="password()">
    <p id="resultado"></p>
