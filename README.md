# Exercises-CSS

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Exercise 1-Curriculum Vitae</title>
    <link rel="stylesheet" href="MyStyle.css">
</head>
<body>

    <div class="cv-container">

        <div class="title">
            CURRICULUM<br>VITAE
        </div>

        <div class="section">
            <h2>PERSONAL DATA</h2>
            <p><strong>Name:</strong> Azamat</p>
            <p><strong>Surname:</strong> Azamat</p>
            <p><strong>Date of birth:</strong> 30.07.74</p>
            <p><strong>Place of birth:</strong> Bishkek, Kyrgyzstan</p>
        </div>

        <div class="section">
            <h2>EDUCATION</h2>

            <div class="row">
                <div class="years">2005-2009</div>
                <div class="info">
                    Computer Engineering in the Technical University of Kyrgyzstan in Bishkek
                </div>
            </div>

            <div class="row">
                <div class="years">2001-2005</div>
                <div class="info">
                    High School “Manas” in Osh
                </div>
            </div>

            <div class="row">
                <div class="years">1995-2001</div>
                <div class="info">
                    Primary school
                </div>
            </div>
        </div>

        <div class="section">
            <h2>PROFESSIONAL EXPERIENCE</h2>

            <div class="row">
                <div class="years">2007-2009</div>
                <div class="info">
                    Computer teacher in High School in Bishkek
                </div>
            </div>

            <div class="row">
                <div class="years">2005-2007</div>
                <div class="info">
                    Secretary of Department of Software in Technical University of Kyrgyzstan in Bishkek
                </div>
            </div>
        </div>
    </div>

</body>
</html>

/* Normal text */
body {
    font-family: Arial, sans-serif;
    color: black;
    font-size: 16px;
    background-color: white;
}

/* Main container */
.cv-container {
    width: 700px;
    margin: auto; /* Centrar el div */
    border: 1px solid #999;
    padding: 20px;
}

/* Main title */
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

/* Sections */
.section {
    margin-bottom: 25px;
}

/* Section headings */
h2 {
    font-family: Georgia, serif;
    color: darkred;
    font-size: 18px;
    letter-spacing: 1.4em;
    margin-bottom: 15px;
}

/* Rows for two columns */
.row {
    overflow: hidden;
    margin-bottom: 10px;
}

/* Left column (years) */
.years {
    float: left;
    width: 120px;
    font-weight: bold;
}

/* Right column (info) */
.info {
    float: left;
    width: 520px;
}


