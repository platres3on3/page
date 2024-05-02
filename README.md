<!DOCTYPE html>
<html lang="el">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Platres 3on3 Basketball Tournament</title>
    <style>
        /* Add your CSS styles here */
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }
        #language-switcher {
            position: fixed;
            top: 10px;
            right: 10px;
        }
        #language-switcher img {
            width: 30px;
            height: auto;
            margin-left: 5px;
            cursor: pointer;
        }
        .content {
            margin: 20px;
            color: #333;
        }
    </style>
</head>
<body>
    <div id="language-switcher">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5c/Flag_of_Greece.svg/2560px-Flag_of_Greece.svg.png" alt="Greek Flag" onclick="switchLanguage('greek')">
        <img src="https://upload.wikimedia.org/wikipedia/en/thumb/a/ae/Flag_of_the_United_Kingdom.svg/1280px-Flag_of_the_United_Kingdom.svg.png" alt="UK Flag" onclick="switchLanguage('english')">
    </div>

    <div class="content" id="english-content" style="display: none;">
        <!-- English content here -->
    </div>

    <div class="content" id="greek-content">
        <!-- Greek content here -->
    </div>

    <script>
        function switchLanguage(language) {
            var englishContent = document.getElementById('english-content');
            var greekContent = document.getElementById('greek-content');

            if (language === 'greek') {
                englishContent.style.display = 'none';
                greekContent.style.display = 'block';
            } else {
                englishContent.style.display = 'block';
                greekContent.style.display = 'none';
            }
        }
    </script>
</body>
</html>
