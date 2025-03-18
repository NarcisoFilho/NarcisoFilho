<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; }
        .content { display: none; }
        .active { display: block; }
        .flag-button { cursor: pointer; border: none; background: none; margin: 10px; }
        .flag-button img { width: 40px; }
    </style>
</head>
<body>
    <h1>💻 About Me</h1>
    
    <div>
        <button class="flag-button" onclick="switchLanguage('english')">
            <img src="https://cdn-icons-png.flaticon.com/64/197/197374.png" alt="English">
        </button>
        <button class="flag-button" onclick="switchLanguage('portuguese')">
            <img src="https://cdn-icons-png.flaticon.com/64/197/197386.png" alt="Português">
        </button>
        <button class="flag-button" onclick="switchLanguage('german')">
            <img src="https://cdn-icons-png.flaticon.com/64/197/197571.png" alt="Deutsch">
        </button>
    </div>
    
    <div id="english" class="content active">
        <h2>🌍 English</h2>
        <p>👋 Hi! I'm an electronics and programming enthusiast, always looking to solve complex challenges and learn new technologies.</p>
        <p>🎓 Computer Engineering student at UFRGS.</p>
        <p>⚡ Experienced in software and hardware development, including programming languages and digital/analog electronics.</p>
    </div>
    
    <div id="portuguese" class="content">
        <h2>🌍 Português</h2>
        <p>👋 Olá! Sou um entusiasta da eletrônica e programação, sempre buscando solucionar desafios complexos e aprender novas tecnologias.</p>
        <p>🎓 Estudante de Engenharia da Computação na UFRGS.</p>
        <p>⚡ Tenho experiência com desenvolvimento de software e hardware, incluindo linguagens de programação e eletrônica digital/analógica.</p>
    </div>
    
    <div id="german" class="content">
        <h2>🌍 Deutsch</h2>
        <p>👋 Hallo! Ich bin ein Elektronik- und Programmierbegeisterter, der immer nach komplexen Herausforderungen sucht und neue Technologien erlernen möchte.</p>
        <p>🎓 Informatikstudent an der UFRGS.</p>
        <p>⚡ Erfahrung in Software- und Hardwareentwicklung, einschließlich Programmiersprachen und digitaler/analoger Elektronik.</p>
    </div>
    
    <script>
        function switchLanguage(language) {
            document.querySelectorAll('.content').forEach(el => el.classList.remove('active'));
            document.getElementById(language).classList.add('active');
        }
    </script>
</body>
</html>
