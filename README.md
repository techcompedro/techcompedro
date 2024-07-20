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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
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



