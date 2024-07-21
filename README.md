## Hi there 👋
<!--
**techcompedro/techcompedro** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

  <img src="https://raw.githubusercontent.com/MicaelliMedeiros/micaellimedeiros/master/image/computer-illustration.png" alt="ilustração de um computador" min-width="400px" max-width="400px" width="400px" align="right">

<p align="left"> 
  oi meu nome é pedro e momento sou desenvolvedor full stack <strong>Sua stack</strong>.<br>
 
</p>

<p align="left">
  🦄 Linguagens: **Coloque as linguagens que você desenvolve.**
</p>

<p align="left">
  💼 Ferramentas: **Coloque as suas ferramentas de trabalho.**
</p>

<p align="left">
  💌 Aqui vai uma mensagem para entrar em contato com você: ⤵️
</p>

<p align="left">
  <a href="#" title="Gmail">
  <img src="https://img.shields.io/badge/-Gmail-FF0000?style=flat-square&labelColor=FF0000&logo=gmail&logoColor=white&link=LINK-DO-SEU-GMAIL" alt="Gmail"/></a>
  <a href="#" title="LinkedIn">
  <img src="https://img.shields.io/badge/-Linkedin-0e76a8?style=flat-square&logo=Linkedin&logoColor=white&link=LINK-DO-SEU-LINKEDIN" alt="LinkedIn"/></a>
  <a href="#" title="WhatsApp">
  <img src="https://img.shields.io/badge/-WhatsApp-25d366?style=flat-square&labelColor=25d366&logo=whatsapp&logoColor=white&link=API-DO-SEU-WHATSAPP" alt="WhatsApp"/></a>
  <a href="#" title="Facebook">
  <img src="https://img.shields.io/badge/-Facebook-3b5998?style=flat-square&labelColor=3b5998&logo=facebook&logoColor=white&link=LINK-DO-SEU-FACEBOOK" alt="Facebook"/></a>
  <a href="#" title="Instagram">
  <img src="https://img.shields.io/badge/-Instagram-DF0174?style=flat-square&labelColor=DF0174&logo=instagram&logoColor=white&link=LINK-DO-SEU-INSTAGRAM" alt="Instagram"/></a>
</p>          
     <title>Pato Pulando</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f0f0;
            margin: 0;
        }
        svg {
            width: 200px;
            height: 200px;
        }
    </style>
</head>
<body>
    <svg viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
        <!-- Corpo do pato -->
        <circle cx="50" cy="50" r="10" fill="yellow" />
        <!-- Cabeça do pato -->
        <circle cx="50" cy="35" r="5" fill="yellow" />
        <!-- Bico do pato -->
        <polygon points="53,35 60,33 53,37" fill="orange" />
        <!-- Olho do pato -->
        <circle cx="48" cy="34" r="1" fill="black" />
    </svg>

    <script>
        const svg = document.querySelector('svg');
        const pato = svg.querySelectorAll('circle, polygon');

        function jump() {
            pato.forEach(element => {
                element.animate([
                    { transform: 'translateY(0)' },
                    { transform: 'translateY(-20px)' },
                    { transform: 'translateY(0)' }
                ], {
                    duration: 500,
                    easing: 'ease-in-out'
                });
            });
        }

        setInterval(jump, 1000);
    </script>


       
</body>
</html>



