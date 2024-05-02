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
        <!-- English content -->
    </div>

    <div class="content" id="greek-content" style="display: none;">
        <!-- Greek content -->
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
