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
 

# 💻 About Me
 


 

<div align="center">
 

  <button onclick="showLanguage('english')">🇬🇧 English</button>
 

  <button onclick="showLanguage('portuguese')">🇧🇷 Português</button>
 

  <button onclick="showLanguage('german')">🇩🇪 Deutsch</button>
 

</div>
 


 

---
 


 

<div id="english" style="display:block;">
 

  
 

  ## 🌍 English
 

  
 

  👋 Hi! I'm an electronics and programming enthusiast, always looking to solve complex challenges and learn new technologies.
 

  
 

  🎓 Computer Engineering student at UFRGS.
 

  
 

  ⚡ Experienced in software and hardware development, including programming languages and digital/analog electronics.
 

  
 

  ### 🛠️ Skills
 

  - **Programming Languages & Technologies:** C, C++, Java, JavaScript, PHP, HTML, CSS, VHDL
 

  - **Electronics:** Analog & Digital
 

  - **Tools & Frameworks:** Git & GitHub, Arduino, Raspberry Pi, Web & Backend Development
 

  
 

  ### 🚀 Projects
 

  🔹 Soon, I will add some of my interesting projects here. Stay tuned!
 

  
 

  ### 📫 Contact
 

  - [LinkedIn](#)
 

  - Email: *(your email)*
 

  - GitHub: [@your-username](https://github.com/your-username)
 

  
 

  ⭐ If you like my profile, don't forget to follow me! 😃
 

</div>
 


 

<div id="portuguese" style="display:none;">
 

  
 

  ## 🌍 Português
 

  
 

  👋 Olá! Sou um entusiasta da eletrônica e programação, sempre buscando solucionar desafios complexos e aprender novas tecnologias.
 

  
 

  🎓 Estudante de Engenharia da Computação na UFRGS.
 

  
 

  ⚡ Tenho experiência com desenvolvimento de software e hardware, incluindo linguagens de programação e eletrônica digital/analógica.
 

  
 

  ### 🛠️ Habilidades
 

  - **Linguagens & Tecnologias:** C, C++, Java, JavaScript, PHP, HTML, CSS, VHDL
 

  - **Eletrônica:** Analógica e Digital
 

  - **Ferramentas & Frameworks:** Git & GitHub, Arduino, Raspberry Pi, Desenvolvimento Web & Backend
 

  
 

  ### 🚀 Projetos
 

  🔹 Em breve, adicionarei alguns dos meus projetos interessantes aqui. Fique ligado!
 

  
 

  ### 📫 Contato
 

  - [LinkedIn](#)
 

  - Email: *(seu email)*
 

  - GitHub: [@seu-usuario](https://github.com/seu-usuario)
 

  
 

  ⭐ Se gostou do meu perfil, não esqueça de me seguir! 😃
 

</div>
 


 

<div id="german" style="display:none;">
 

  
 

  ## 🌍 Deutsch
 

  
 

  👋 Hallo! Ich bin ein Elektronik- und Programmierbegeisterter, der immer nach komplexen Herausforderungen sucht und neue Technologien erlernen möchte.
 

  
 

  🎓 Informatikstudent an der UFRGS.
 

  
 

  ⚡ Erfahrung in Software- und Hardwareentwicklung, einschließlich Programmiersprachen und digitaler/analoger Elektronik.
 

  
 

  ### 🛠️ Fähigkeiten
 

  - **Programmiersprachen & Technologien:** C, C++, Java, JavaScript, PHP, HTML, CSS, VHDL
 

  - **Elektronik:** Analog & Digital
 

  - **Werkzeuge & Frameworks:** Git & GitHub, Arduino, Raspberry Pi, Web- & Backend-Entwicklung
 

  
 

  ### 🚀 Projekte
 

  🔹 Bald werde ich hier einige meiner interessanten Projekte hinzufügen. Bleiben Sie dran!
 

  
 

  ### 📫 Kontakt
 

  - [LinkedIn](#)
 

  - Email: *(Ihre E-Mail)*
 

  - GitHub: [@Ihr-Benutzername](https://github.com/Ihr-Benutzername)
 

  
 

  ⭐ Wenn Ihnen mein Profil gefällt, vergessen Sie nicht, mir zu folgen! 😃
 

</div>
 


 

<script>
 

  function showLanguage(lang) {
 

    document.getElementById('english').style.display = 'none';
 

    document.getElementById('portuguese').style.display = 'none';
 

    document.getElementById('german').style.display = 'none';
 

    document.getElementById(lang).style.display = 'block';
 

  }
 

</script>
