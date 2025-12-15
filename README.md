# Exercises-CSS

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Curriculum Vitae</title>

    <style>
        /* Texto normal */
        body {
            font-family: Arial, sans-serif;
            font-size: 16px;
            color: black;
            background-color: white;
        }

        /* Contenedor centrado */
        .cv {
            width: 700px;
            margin: auto;
            border: 1px solid #999;
            padding: 20px;
        }

        /* Título principal */
        .title {
            background-color: #d3d3d3;
            color: #2a5da8;
            font-family: Georgia, serif;
            font-size: 24px;
            font-weight: bold;
            letter-spacing: 1.6em;
            word-spacing: 2em;
            text-align: center;
            padding: 10px;
            margin-bottom: 30px;
        }

        /* Encabezados */
        h2 {
            font-family: Georgia, serif;
            color: darkred;
            font-size: 18px;
            letter-spacing: 1.4em;
            margin-bottom: 15px;
        }

        /* Filas */
        .row {
            overflow: hidden;
            margin-bottom: 10px;
        }

        /* Columna años */
        .years {
            float: left;
            width: 120px;
            font-weight: bold;
        }

        /* Columna información */
        .info {
            float: left;
            width: 520px;
        }
    </style>
</head>
<body>

<div class="cv">

    <div class="title">
        CURRICULUM<br>VITAE
    </div>

    <h2>PERSONAL DATA</h2>
    <p><strong>Name:</strong> Azamat</p>
    <p><strong>Surname:</strong> Azamat</p>
    <p><strong>Date of birth:</strong> 30.07.74</p>
    <p><strong>Place of birth:</strong> Bishkek, Kyrgyzstan</p>

    <h2>EDUCATION</h2>

    <div class="row">
        <div class="years">2005-2009</div>
        <div class="info">Computer Engineering in the Technical University of Kyrgyzstan in Bishkek</div>
    </div>

    <div class="row">
        <div class="years">2001-2005</div>
        <div class="info">High School “Manas” in Osh</div>
    </div>

    <div class="row">
        <div class="years">1995-2001</div>
        <div class="info">Primary school</div>
    </div>

    <h2>PROFESSIONAL EXPERIENCE</h2>

    <div class="row">
        <div class="years">2007-2009</div>
        <div class="info">Computer teacher in High School in Bishkek</div>
    </div>

    <div class="row">
        <div class="years">2005-2007</div>
        <div class="info">Secretary of Department of Software in Technical University of Kyrgyzstan in Bishkek</div>
    </div>

</div>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Classic Horror Authors - Edgar Allan Poe</title>

    <style>
        /* Página general */
        body {
            background-color: #666666;
            font-family: Arial, Helvetica, sans-serif;
            font-size: 90%;
        }

        /* Todos los divs */
        div {
            margin-top: 6px;
            padding: 6px;
            border: 1px solid black;
        }

        /* Header */
        #header {
            background-color: #990000;
            width: 779px;
            color: white;
        }

        /* Navigation */
        #navigation {
            background-color: #CCCCCC;
            width: 779px;
        }

        /* Content */
        #content {
            background-color: #999999;
            width: 464px;
            float: left;
            margin-bottom: 6px;
        }

        /* Right panel */
        #rightpanel {
            background-color: #999999;
            width: 295px;
            margin-left: 484px;
        }

        /* Footer */
        #footer {
            background-color: #CCCCCC;
            width: 779px;
            text-align: center;
            clear: left;
        }
    </style>
</head>
<body>

<div id="header">
    <h1>Classic Horror Authors - Edgar Allan Poe</h1>
</div>

<div id="navigation">
    <a href="poe.html">Edgar Allan Poe</a> |
    <a href="shelley.html">Mary Shelley</a> |
    <a href="stoker.html">Bram Stoker</a>
</div>

<div id="content">
    <h2>Edgar Allan Poe</h2>
    <p>
        Edgar Allan Poe was born in Boston on January 19, 1809. He was an American
        writer, poet, editor and literary critic, best known for his tales of
        mystery and the macabre.
    </p>
</div>

<div id="rightpanel">
    <h3>Stories by Poe</h3>
    <ul>
        <li>The Tell-Tale Heart</li>
        <li>The Black Cat</li>
        <li>The Raven</li>
    </ul>

    <h3>Comments / Suggestions</h3>
    <p>
        Please <a href="mailto:example@email.com">let us know</a> your opinion.
    </p>
</div>

<div id="footer">
    © 2025 Classic Horror Authors Website
</div>

</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Exercise 3 - Background</title>

    <style>
        /* Evita scroll */
        html, body {
            height: 100%;
            margin: 0;
            overflow: hidden;
        }

        /* Fondo */
        body {
            background-image: url("background.jpg"); /* cambia por tu imagen */
            background-repeat: repeat-y;       /* repetir solo eje Y */
            background-position: left top;      /* imagen a la izquierda */
            background-attachment: fixed;       /* no se mueve */
            font-family: Arial, Helvetica, sans-serif;
        }

        /* Contenido a la derecha */
        .content {
            margin-left: 220px; /* espacio para la imagen */
            padding: 20px;
        }
    </style>
</head>
<body>

    <div class="content">
        <h1>CSS Background Exercise</h1>
        <p>
            This page shows a background image repeated only on the Y axis.
        </p>
        <p>
            The image stays fixed, there is no scroll, and the text appears
            on the right side of the image.
        </p>
        <p>
            This solution is based on the W3Schools background example.
        </p>
    </div>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Exercise 4 - Horizontal Menu</title>

    <style>
        /* Reset básico */
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
        }

        /* Menú */
        ul.navbar {
            list-style-type: none;
            margin: 0;
            padding: 0;
            background-color: #555;
            overflow: hidden; /* necesario para float */
        }

        /* Elementos en horizontal */
        ul.navbar li {
            float: left;
        }

        /* Enlaces */
        ul.navbar li a {
            display: block;
            color: black;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }

        /* Hover */
        ul.navbar li a:hover {
            background-color: #333; /* gris oscuro */
            color: white;
        }
    </style>
</head>
<body>

    <ul class="navbar">
        <li><a href="#">Home</a></li>
        <li><a href="#">News</a></li>
        <li><a href="#">Contact</a></li>
        <li><a href="#">About</a></li>
    </ul>

</body>
</html>
