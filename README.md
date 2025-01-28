<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fotis Dimitriadis - Portfolio</title>
    <style>
        body {
            font-family: 'Courier New', Courier, monospace;
            background-color: #121212;
            color: #f0f0f0;
            margin: 0;
            padding: 0;
        }
        header {
            text-align: center;
            padding: 50px 20px;
            background: #1f1f1f;
            color: #00ff00;
        }
        header h1 {
            font-size: 2.5rem;
            margin: 0;
            text-shadow: 0 0 8px #00ff00;
        }
        header h3 {
            font-size: 1.5rem;
            font-weight: 300;
            text-shadow: 0 0 5px #00ff00;
        }
        section {
            max-width: 800px;
            margin: 40px auto;
            padding: 20px;
            background: #1a1a1a;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 255, 0, 0.2);
        }
        section h3 {
            border-bottom: 2px solid #00ff00;
            padding-bottom: 5px;
            margin-bottom: 15px;
        }
        .info-list {
            list-style: none;
            padding: 0;
        }
        .info-list li {
            margin: 10px 0;
        }
        .info-list a {
            color: #00ff00;
            text-decoration: none;
        }
        .info-list a:hover {
            text-decoration: underline;
        }
        .social-links img {
            margin-right: 10px;
        }
        .languages-tools img {
            margin: 10px;
            transition: transform 0.3s;
            filter: grayscale(100%);
        }
        .languages-tools img:hover {
            transform: scale(1.2);
            filter: none;
        }
        .stats {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .stats img {
            max-width: 100%;
            border-radius: 8px;
        }
        .highlight {
            font-weight: bold;
            color: #00ff00;
        }
        .gif-placeholder {
            display: flex;
            justify-content: center;
            margin-top: 30px;
        }
        .gif-placeholder img {
            max-width: 100%;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 255, 0, 0.2);
        }
    </style>
</head>
<body>

<header>
    <h1>Hello, I'm Fotis Dimitriadis</h1>
    <h3>A self-taught Pen Tester and Full Stack Developer</h3>
</header>

<section>
    <p align="center">
        <img src="https://komarev.com/ghpvc/?username=fedality&label=Profile%20views&color=00ff00&style=flat" alt="Profile Views" />
    </p>
    <h3>About Me</h3>
    <ul class="info-list">
        <li>🌟 Currently working on my <span class="highlight">PQC Encryption & PQC Solutions</span>.</li>
        <li>📚 Learning <span class="highlight">Falcon Algorithm with Assembly</span>.</li>
        <li>🖇️ All of my projects will soon be available at <a href="#">[soon]</a>.</li>
        <li>📝 I regularly write articles at <a href="#">[soon]</a>.</li>
        <li>💬 Feel free to ask me about <span class="highlight">Assembly, Kyber, SPHINCS+, or Blackarch</span>.</li>
        <li>📩 How to reach me: <a href="mailto:ftdimitriadis@outlook.com">ftdimitriadis@outlook.com</a>.</li>
    </ul>
    <h3>Connect with Me</h3>
    <p class="social-links">
        <a href="https://linkedin.com/in/fotis-dimitriadis" target="_blank">
            <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40" />
        </a>
    </p>
</section>

<section>
    <h3>Languages and Tools</h3>
    <div class="languages-tools">
        <a href="https://angular.io" target="_blank">
            <img src="https://angular.io/assets/images/logos/angular/angular.svg" alt="Angular" width="40" height="40" />
        </a>
        <a href="https://getbootstrap.com" target="_blank">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="Bootstrap" width="40" height="40" />
        </a>
        <a href="https://www.cprogramming.com/" target="_blank">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="C" width="40" height="40" />
        </a>
        <a href="https://www.w3schools.com/cpp/" target="_blank">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="C++" width="40" height="40" />
        </a>
        <a href="https://www.python.org" target="_blank">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40" />
        </a>
    </div>
</section>

<section>
    <h3>Stats</h3>
    <div class="stats">
        <img src="https://github-readme-stats.vercel.app/api/top-langs?username=fedality&show_icons=true&locale=en&layout=compact&theme=radical" alt="Top Languages" />
        <img src="https://github-readme-stats.vercel.app/api?username=fedality&show_icons=true&locale=en&theme=radical" alt="GitHub Stats" />
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=fedality&theme=radical" alt="GitHub Streak" />
    </div>
</section>

<div class="gif-placeholder">
    <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" alt="Hacker GIF" />
</div>

</body>
</html>
