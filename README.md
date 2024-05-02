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
        .language-buttons {
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
        <!-- Add more English content here -->
    </div>

    <div class="content" id="greek-content" style="display: none;">
        <h1>Τουρνουά Μπάσκετ 3on3 Platres</h1>
        <ul>
            <li>Ημερομηνία: 2 Ιουνίου 2024</li>
            <li>Τοποθεσία: <a href="https://platresarena.com/">Αρένα Πλάτρες</a>, Πλάτρες.</li>
        </ul>
        <p>
            Μετά από μια επιτυχημένη χρονιά, το Platres 3on3 επιστρέφει στο γήπεδο των Πάνω Πλατρών για μια ακόμη διοργάνωση, με κύριο στόχο την υποστήριξη του Ιδρύματος Μικροί Ήρωες και του Europa Donna Cyprus, δύο μη κερδοσκοπικών οργανισμών οι οποίοι παρέχουν βοήθεια και στήριξη σε παιδιά τα οποία παλεύουν με την λευχαιμία, σε γυναίκες και άντρες οι οποίοι αγωνίζονται κατά του καρκίνου του μαστού.
        </p>
        <!-- Add more Greek content here -->
    </div>

    <div class="language-buttons">
        <button onclick="showEnglishContent()">English</button>
        <button onclick="showGreekContent()">Ελληνικά</button>
    </div>

    <script>
        function showEnglishContent() {
            var englishContent = document.getElementById('english-content');
            var greekContent = document.getElementById('greek-content');

            englishContent.style.display = 'block';
            greekContent.style.display = 'none';
        }

        function showGreekContent() {
            var englishContent = document.getElementById('english-content');
            var greekContent = document.getElementById('greek-content');

            englishContent.style.display = 'none';
            greekContent.style.display = 'block';
        }
    </script>
</body>
</html>
