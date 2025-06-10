<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>John Albert Andal | GitHub Profile</title>
    <style>
        :root {
            --bg-color: #0d1117;
            --text-color: #e6edf3;
            --accent-color: #58a6ff;
            --secondary-color: #8b949e;
            --card-bg: #161b22;
            --border-color: #30363d;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            line-height: 1.6;
            padding: 2rem;
            max-width: 800px;
            margin: 0 auto;
        }
        
        .container {
            display: flex;
            flex-direction: column;
            gap: 2rem;
        }
        
        .header {
            display: flex;
            flex-direction: column;
            gap: 0.5rem;
            border-bottom: 1px solid var(--border-color);
            padding-bottom: 1.5rem;
        }
        
        h1 {
            font-size: 2rem;
            font-weight: 600;
        }
        
        .intro {
            font-size: 1.2rem;
            color: var(--secondary-color);
        }
        
        .wave {
            animation-name: wave-animation;
            animation-duration: 2.5s;
            animation-iteration-count: infinite;
            transform-origin: 70% 70%;
            display: inline-block;
        }
        
        @keyframes wave-animation {
            0% { transform: rotate( 0.0deg) }
            10% { transform: rotate(14.0deg) }
            20% { transform: rotate(-8.0deg) }
            30% { transform: rotate(14.0deg) }
            40% { transform: rotate(-4.0deg) }
            50% { transform: rotate(10.0deg) }
            60% { transform: rotate( 0.0deg) }
            100% { transform: rotate( 0.0deg) }
        }
        
        .section {
            margin-top: 1.5rem;
        }
        
        h2 {
            font-size: 1.3rem;
            margin-bottom: 1rem;
            color: var(--accent-color);
            font-weight: 500;
        }
        
        .card {
            background-color: var(--card-bg);
            border-radius: 6px;
            padding: 1.5rem;
            border: 1px solid var(--border-color);
        }
        
        .skills, .socials {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            justify-content: flex-start;
        }
        
        .skill-icon, .social-icon {
            transition: transform 0.2s ease;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .skill-icon:hover, .social-icon:hover {
            transform: translateY(-5px);
        }
        
        .social-icon img {
            opacity: 0.8;
            transition: opacity 0.2s ease;
        }
        
        .social-icon:hover img {
            opacity: 1;
        }
        
        .footer {
            margin-top: 2rem;
            text-align: center;
            color: var(--secondary-color);
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">            <h1><span class="wave">👋</span> Hi there! I'm John Albert Andal</h1>
            <p class="intro">Designer & Developer | Turning ideas into visual experiences</p>
        </div>
        
        <div class="section">            <h2>About Me</h2>
            <div class="card">
                <p>I'm passionate about design and development. With expertise in various design tools and development environments, I create engaging and meaningful digital experiences that combine creativity with technical skills.</p>
            </div>
        </div>
          <div class="section">
            <h2>Design Tools</h2>
            <div class="card">
                <div class="skills">
                    <div class="skill-icon"><img src="https://skillicons.dev/icons?i=ps" height="40" alt="Adobe Photoshop logo" /></div>
                    <div class="skill-icon"><img src="https://skillicons.dev/icons?i=ai" height="40" alt="Adobe Illustrator logo" /></div>
                    <div class="skill-icon"><img src="https://skillicons.dev/icons?i=ae" height="40" alt="Adobe After Effects logo" /></div>
                    <div class="skill-icon"><img src="https://skillicons.dev/icons?i=xd" height="40" alt="Adobe XD logo" /></div>
                    <div class="skill-icon"><img src="https://skillicons.dev/icons?i=figma" height="40" alt="Figma logo" /></div>
                    <div class="skill-icon"><img src="https://skillicons.dev/icons?i=blender" height="40" alt="Blender logo" /></div>
                </div>
            </div>
        </div>
        
        <div class="section">
            <h2>Development Tools</h2>
            <div class="card">
                <div class="skills">                    <div class="skill-icon"><img src="https://skillicons.dev/icons?i=vscode" height="40" alt="VS Code logo" /></div>
                    <div class="skill-icon"><img src="https://skillicons.dev/icons?i=visualstudio" height="40" alt="Visual Studio logo" /></div>
                    <div class="skill-icon">
                        <img src="cursor-logo.svg" height="40" alt="Cursor AI IDE logo" />
                    </div>
                </div>
            </div>
        </div>
        
        <div class="section">
            <h2>Connect With Me</h2>
            <div class="card">
                <div class="socials">
                    <a href="#" class="social-icon" title="LinkedIn">
                        <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="40" height="30" alt="LinkedIn logo" />
                    </a>
                    <a href="#" class="social-icon" title="Instagram">
                        <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/instagram/default.svg" width="40" height="30" alt="Instagram logo" />
                    </a>
                    <a href="#" class="social-icon" title="Discord">
                        <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/discord/default.svg" width="40" height="30" alt="Discord logo" />
                    </a>
                    <a href="#" class="social-icon" title="Email">
                        <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gmail/default.svg" width="40" height="30" alt="Gmail logo" />
                    </a>
                </div>
            </div>
        </div>
        
        <div class="footer">
            ✨ Thanks for visiting my profile! ✨
        </div>
    </div>
</body>
</html>
