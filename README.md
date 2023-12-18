<!DOCTYPE html>
<html lang="de">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home Staging</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }

        header {
            text-align: center;
            padding: 40px;
            background-color: #dbdddd;
        }

        h1 {
            color: #000000;
        }

        p {
            color: #969393;
        }

        img {
            max-width: 100%;
            height: auto;
            position: relative;
        }

        .blog-header {
            position: relative;
            text-align: center;
        }

        .blog-description {
            margin: 10px;
        }

        .blog-header img {
            width: 50%;
            height: auto;
            object-fit: cover;
        }

        .blog-header::after {
            content: '';
            display: block;
            clear: both;
        }

        .custom-box-container {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
        }

        .custom-box {
            flex: 0 1 calc(20% - 20px);
            height: 200px;
            background-color: #cdd6cd;
            margin: 20px 0;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .custom-box h3 {
            font-weight: bold;
            margin-bottom: 10px;
        }

        .custom-box p {
            position: absolute;
            bottom: 10px;
            left: 0;
            right: 0;
            margin: 0;
        }

        .custom-box span {
            display: block;
            font-weight: bold;
            margin-top: 10px;
        }

        .custom-box img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
    </style>
</head>

<body>

    <header>
        <h1>Web & Blog Design</h1>
        <p class="blog-description">"Kreative Webdesigns & Innovative Programmierung für Ihren perfekten Online-Auftritt!"</p>
    </header>

    <main>
        <!-- Hier könnten Blog-Beiträge eingefügt werden -->
        <article>
            <h2>Der bisherige Favorit unserer Kunden</h2>
        </article>

        <header class="blog-header">
            <img src="dior.avif" alt="Beschreibung des Bildes">
        </header>

        <div class="custom-box-container">
            <!-- Obere Reihe -->
            <div class="custom-box">
                <!-- Hier das Hintergrundbild für Bild 1 einfügen -->
                <img src="dior.avif" alt="Bild 1">
                <h3>Kasten 1</h3>
                <p>Text unter dem ersten Kasten</p>
                <span>SHOP NOW</span>
            </div>

            <div class="custom-box">
                <!-- Hier das Hintergrundbild für Bild 2 einfügen -->
                <img src="dior.avif" alt="Bild 2">
                <h3>Kasten 2</h3>
                <p>Text unter dem zweiten Kasten</p>
                <span>SHOP NOW</span>
            </div>

            <div class="custom-box">
                <!-- Hier das Hintergrundbild für Bild 3 einfügen -->
                <img src="dior.avif" alt="Bild 3">
                <h3>Kasten 3</h3>
                <p>Text unter dem dritten Kasten</p>
                <span>SHOP NOW</span>
            </div>

            <div class="custom-box">
                <!-- Hier das Hintergrundbild für Bild 4 einfügen -->
                <img src="dior.avif" alt="Bild 4">
                <h3>Kasten 4</h3>
                <p>Text unter dem vierten Kasten</p>
                <span>SHOP NOW</span>
            </div>

            <div class="custom-box">
                <!-- Hier das Hintergrundbild für Bild 5 einfügen -->
                <img src="dior.avif" alt="Bild 5">
                <h3>Kasten 5</h3>
                <p>Text unter dem fünften Kasten</p>
                <span>SHOP NOW</span>
            </div>

            <!-- Untere Reihe -->
            <div class="custom-box">
                <!-- Hier das Hintergrundbild für Bild 6 einfügen -->
                <img src="dior.avif" alt="Bild 6">
                <h3>Kasten 6</h3>
                <p>Text unter dem sechsten Kasten</p>
                <span>SHOP NOW</span>
            </div>

            <div class="custom-box">
                <!-- Hier das Hintergrundbild für Bild 7 einfügen -->
                <img src="dior.avif" alt="Bild 7">
                <h3>Kasten 7</h3>
                <p>Text unter dem siebten Kasten</p>
                <span>SHOP NOW</span>
            </div>

            <div class="custom-box">
                <!-- Hier das Hintergrundbild für Bild 8 einfügen -->
                <img src="dior.avif" alt="Bild 8">
                <h3>Kasten 8</h3>
                <p>Text unter dem achten Kasten</p>
                <span>SHOP NOW</span>
            </div>

            <div class="custom-box">
                <!-- Hier das Hintergrundbild für Bild 9 einfügen -->
                <img src="dior.avif" alt="Bild 9">
                <h3>Kasten 9</h3>
                <p>Text unter dem neunten Kasten</p>
                <span>SHOP NOW</span>
            </div>

            <div class="custom-box">
                <!-- Hier das Hintergrundbild für Bild 10 einfügen -->
                <img src="dior.avif" alt="Bild 10">
                <h3>Kasten 10</h3>
                <p>Text unter dem zehnten Kasten</p>
                <span>SHOP NOW</span>
            </div>
        </div>

        <article>
            <h2>Zweiter Beitrag</h2>
            <p>Dies ist der Text des zweiten Beitrags.</p>
        </article>
    </main>

</body>

</html>
