<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile Page</title>
    <style>
        /* Basic styling for better visibility */
        .button-container button {
            margin: 5px;
            padding: 10px;
            font-size: 16px;
        }
    </style>
</head>
<body>

<div align="center" class="button-container">
  <button onclick="showLanguage('english')">🇬🇧 English</button>
  <button onclick="showLanguage('portuguese')">🇧🇷 Português</button>
  <button onclick="showLanguage('german')">🇩🇪 Deutsch</button>
</div>

<hr>

<div id="english" style="display:block;">
  <h2>🌍 English</h2>
  <p>👋 Hi! I'm an electronics and programming enthusiast...</p>
</div>

<div id="portuguese" style="display:none;">
  <h2>🌍 Português</h2>
  <p>👋 Olá! Sou um entusiasta da eletrônica e programação...</p>
</div>

<div id="german" style="display:none;">
  <h2>🌍 Deutsch</h2>
  <p>👋 Hallo! Ich bin ein Elektronik- und Programmierbegeisterter...</p>
</div>

<script>
  // Function to show the selected language and hide the others
  function showLanguage(lang) {
    // Hide all language sections
    document.getElementById('english').style.display = 'none';
    document.getElementById('portuguese').style.display = 'none';
    document.getElementById('german').style.display = 'none';

    // Show the selected language section
    document.getElementById(lang).style.display = 'block';
  }
</script>

</body>
</html>
