<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ky Anh's Profile</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #1a1c2c 0%, #2a2d3e 100%);
            color: #ffffff;
            line-height: 1.6;
            padding: 2rem;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
            background: rgba(255, 255, 255, 0.05);
            border-radius: 20px;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.1);
            backdrop-filter: blur(10px);
        }

        .header {
            text-align: center;
            margin-bottom: 3rem;
        }

        .header h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            background: linear-gradient(45deg, #00ff87, #60efff);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            display: inline-block;
        }

        .header h3 {
            font-size: 1.2rem;
            color: #a0a0a0;
            margin-bottom: 2rem;
        }

        .section {
            margin-bottom: 3rem;
            padding: 2rem;
            background: rgba(255, 255, 255, 0.03);
            border-radius: 15px;
            transition: transform 0.3s ease;
        }

        .section:hover {
            transform: translateY(-5px);
        }

        .section-title {
            text-align: center;
            font-size: 1.5rem;
            margin-bottom: 1.5rem;
            color: #00ff87;
        }

        .tech-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
            gap: 1.5rem;
            justify-items: center;
            align-items: center;
        }

        .tech-item {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 1rem;
            background: rgba(255, 255, 255, 0.05);
            border-radius: 12px;
            transition: all 0.3s ease;
        }

        .tech-item:hover {
            transform: scale(1.05);
            background: rgba(255, 255, 255, 0.1);
        }

        .tech-item img {
            width: 50px;
            height: 50px;
            margin-bottom: 0.5rem;
            filter: drop-shadow(0 4px 6px rgba(0, 0, 0, 0.1));
        }

        @media (max-width: 768px) {
            .container {
                padding: 1rem;
            }

            .header h1 {
                font-size: 2rem;
            }

            .section {
                padding: 1rem;
            }

            .tech-grid {
                grid-template-columns: repeat(auto-fit, minmax(80px, 1fr));
                gap: 1rem;
            }
        }

        /* Animation */
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .section {
            animation: fadeIn 0.6s ease forwards;
        }

        .section:nth-child(2) {
            animation-delay: 0.2s;
        }

        .section:nth-child(3) {
            animation-delay: 0.4s;
        }

        .section:nth-child(4) {
            animation-delay: 0.6s;
        }

        .section:nth-child(5) {
            animation-delay: 0.8s;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Hi 👋, I'm Ky Anh (botodale)</h1>
            <h3>A passionate software engineer from Vietnam and can understand and implement AI/ML models</h3>
        </div>

        <div class="section">
            <h3 class="section-title">Frontend</h3>
            <div class="tech-grid">
                <a href="https://www.w3schools.com/css/" class="tech-item" target="_blank" rel="noreferrer">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3">
                </a>
                <a href="https://www.w3.org/html/" class="tech-item" target="_blank" rel="noreferrer">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5">
                </a>
                <a href="https://reactjs.org/" class="tech-item" target="_blank" rel="noreferrer">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react">
                </a>
                <a href="https://sass-lang.com" class="tech-item" target="_blank" rel="noreferrer">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sass/sass-original.svg" alt="sass">
                </a>
            </div>
        </div>

        <div class="section">
            <h3 class="section-title">Backend</h3>
            <div class="tech-grid">
                <a href="https://nodejs.org" class="tech-item" target="_blank" rel="noreferrer">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs">
                </a>
                <a href="https://expressjs.com" class="tech-item" target="_blank" rel="noreferrer">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express">
                </a>
                <a href="https://www.java.com" class="tech-item" target="_blank" rel="noreferrer">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java">
                </a>
                <a href="https://spring.io/" class="tech-item" target="_blank" rel="noreferrer">
                    <img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" alt="spring">
                </a>
            </div>
        </div>

        <div class="section">
            <h3 class="section-title">AI / Machine Learning</h3>
            <div class="tech-grid">
                <a href="https://pandas.pydata.org/" class="tech-item" target="_blank" rel="noreferrer">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas">
                </a>
                <a href="https://www.python.org" class="tech-item" target="_blank" rel="noreferrer">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python">
                </a>
                <a href="https://pytorch.org/" class="tech-item" target="_blank" rel="noreferrer">
                    <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch">
                </a>
            </div>
        </div>

        <div class="section">
            <h3 class="section-title">Database</h3>
            <div class="tech-grid">
                <a href="https://www.mysql.com/" class="tech-item" target="_blank" rel="noreferrer">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql">
                </a>
                <a href="https://www.postgresql.org" class="tech-item" target="_blank" rel="noreferrer">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql">
                </a>
                <a href="https://firebase.google.com/" class="tech-item" target="_blank" rel="noreferrer">
                    <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase">
                </a>
            </div>
        </div>

        <div class="section">
            <h3 class="section-title">DevOps / Containerization</h3>
            <div class="tech-grid">
                <a href="https://www.docker.com/" class="tech-item" target="_blank" rel="noreferrer">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker">
                </a>
            </div>
        </div>

        <div class="section">
            <h3 class="section-title">Programming Languages</h3>
            <div class="tech-grid">
                <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" class="tech-item" target="_blank" rel="noreferrer">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript">
                </a>
                <a href="https://www.typescriptlang.org/" class="tech-item" target="_blank" rel="noreferrer">
                    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript">
                </a>
            </div>
        </div>
    </div>
</body>
</html>
