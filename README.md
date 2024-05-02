<!DOCTYPE html>
<html lang="el">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Platres 3on3 Basketball Tournament</title>
    <style>
        /* Add your CSS styles here */
        img {
            width: 100%;
            height: auto;
        }
        .content {
            margin: 20px;
            font-family: Arial, sans-serif;
            color: #333;
        }
        .toggle-button {
            position: fixed;
            top: 10px;
            right: 10px;
        }
    </style>
</head>
<body>
    <img src="background5.png" alt="Background Image">
    <div class="content" id="english-content">
        <h1>Platres 3on3 Basketball Tournament</h1>
        <ul>
            <li>Date: 2 June 2024</li>
            <li>Location: <a href="https://platresarena.com/">Platres Arena</a>, Platres.</li>
        </ul>
        <p>
            After a successful year, Platres 3on3 returns to the Panos Platres basketball court for another event, with the main goal of supporting the Little Heroes Foundation and Europa Donna Cyprus, two non-profit organizations that provide assistance and support to children battling leukemia, and to women and men fighting breast cancer.
        </p>
        <!-- English content continues... -->
    </div>

    <div class="content" id="greek-content" style="display: none;">
        <h1>Τουρνουά Μπάσκετ 3on3 Platres</h1>
        <!-- Greek content continues... -->
    </div>

    <button class="toggle-button" onclick="toggleLanguage()">Toggle Language</button>

    <script>
        function toggleLanguage() {
            var englishContent = document.getElementById('english-content');
            var greekContent = document.getElementById('greek-content');

            if (englishContent.style.display === 'none') {
                englishContent.style.display = 'block';
                greekContent.style.display = 'none';
            } else {
                englishContent.style.display = 'none';
                greekContent.style.display = 'block';
            }
        }
    </script>
</body>
</html>
