<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Reciclaje y Medio Ambiente</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Reciclaje y Medio Ambiente</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#que-es-reciclaje">¿Qué es el reciclaje?</a></li>
            <li><a href="#beneficios">Beneficios</a></li>
            <li><a href="#como-reciclar">Cómo Reciclar</a></li>
        </ul>
    </nav>
    <main>
        <section id="que-es-reciclaje">
            <h2>¿Qué es el reciclaje?</h2>
            <p>El reciclaje es el proceso de convertir materiales usados en nuevos productos para prevenir el desperdicio de materiales potencialmente útiles, reducir el consumo de materias primas frescas, reducir el uso de energía, reducir la contaminación del aire y del agua y reducir las emisiones de gases de efecto invernadero.</p>
        </section>
        <section id="beneficios">
            <h2>Beneficios del Reciclaje</h2>
            <ul>
                <li>Reducción de residuos.</li>
                <li>Conservación de recursos naturales.</li>
                <li>Ahorro de energía.</li>
                <li>Reducción de la contaminación.</li>
                <li>Creación de empleos.</li>
            </ul>
        </section>
        <section id="como-reciclar">
            <h2>Cómo Reciclar</h2>
            <p>Para reciclar correctamente, sigue estos pasos:</p>
            <ol>
                <li>Clasifica los residuos en papel, plástico, vidrio y metal.</li>
                <li>Lava los envases antes de reciclarlos.</li>
                <li>Deposita los residuos en los contenedores adecuados.</li>
            </ol>
            <button id="learnMore">Aprende más</button>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Reciclaje y Medio Ambiente. Todos los derechos reservados.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #e0f7fa;
    margin: 0;
    padding: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
}

header {
    background-color: #00796b;
    color: white;
    padding: 1em;
    text-align: center;
    width: 100%;
}

nav {
    background-color: #004d40;
    width: 100%;
}

nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 1em;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

main {
    background-color: white;
    padding: 2em;
    margin: 1em;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    width: 60%;
    text-align: left;
}

section {
    margin-bottom: 2em;
}

footer {
    background-color: #004d40;
    color: white;
    padding: 1em;
    text-align: center;
    width: 100%;
    position: fixed;
    bottom: 0;
}

button {
    padding: 0.5em 1em;
    color: white;
    background-color: #00796b;
    border: none;
    cursor: pointer;
}

button:hover {
    background-color: #004d40;
}
document.getElementById('learnMore').addEventListener('click', function() {
    alert('Reciclar ayuda a preservar el medio ambiente. ¡Aprende y participa en el reciclaje!');
});

 </section>
        <section id="integrantes">
            <h2>Integrantes</h2>
            <ul>
                <li>Gerardo Alejandro Kumul Cen</li>
