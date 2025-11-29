<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>My Gothic Page</title>

    <!-- Devicon (icons) -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/devicon.min.css">

    <style>
        body {
            margin: 0;
            padding: 0;
            background: #0d0d0d; /* Gothic Dark */
            color: #e0e0e0;
            font-family: "Cinzel", serif;
            text-align: center;
        }

        h1 {
            margin-top: 60px;
            font-size: 3rem;
            letter-spacing: 3px;
            text-shadow: 0 0 15px #6f00ff;
        }

        .skills {
            margin-top: 50px;
            display: flex;
            gap: 40px;
            justify-content: center;
            flex-wrap: wrap;
        }

        .skill {
            background: rgba(255, 255, 255, 0.03);
            padding: 25px;
            border-radius: 15px;
            width: 130px;
            backdrop-filter: blur(4px);
            box-shadow: 0 0 20px rgba(111, 0, 255, 0.2);
            transition: 0.3s;
        }

        .skill:hover {
            transform: translateY(-8px);
            box-shadow: 0 0 25px rgba(111, 0, 255, 0.8);
        }

        .skill i {
            font-size: 60px;
            margin-bottom: 10px;
            filter: drop-shadow(0 0 8px #6f00ff);
        }

        footer {
            margin-top: 70px;
            padding: 20px;
            font-size: 12px;
            color: #888;
        }
    </style>
</head>

<body>

    <h1>⚔ My Gothic Profile ⚔</h1>

    <section class="skills">
        <div class="skill">
            <i class="devicon-python-plain colored"></i>
            <p>Python</p>
        </div>

        <div class="skill">
            <i class="devicon-c-plain colored"></i>
            <p>C</p>
        </div>

        <div class="skill">
            <i class="devicon-cplusplus-plain colored"></i>
            <p>C++</p>
        </div>

        <!-- زيد لغات أخرى إلا بغيتي -->
    </section>

    <footer>
        © 2025 — Gothic Dark Design
    </footer>

</body>
</html>
