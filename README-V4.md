<div align="center">
    <div class="scanline"></div>
    <div class="container">    
        <div class="header">
            <h1 class="username">ZeroDayZ7</h1>
            <p class="subtitle">Fullstack Developer</p>
        </div>
        <div class="contact-section">
            <a href="mailto:zerodayz7@proton.me" class="cyber-button">
                📧 Contact
            </a>
            <a href="https://zerodayz7.github.io/portfolio/" class="cyber-button">
                🌐 Portfolio
            </a>
        </div>
        <div class="tech-stack">
            <span class="tech-badge">Next.js</span>
            <span class="tech-badge">Express.js</span>
            <span class="tech-badge">TypeScript</span>
            <span class="tech-badge">Node.js</span>
            <span class="tech-badge">Docker</span>
            <span class="tech-badge">MySQL</span>
            <span class="tech-badge">Redis</span>
        </div>
        <div class="separator"></div>
        <div class="project-section">
            <h3 class="project-title">AGV-MAN</h3>
            <p class="project-description">
                Autonomous Ground Vehicle Management System <br>
                Python/Tkinter UI for industrial fleet control.
            </p>
            <div style="text-align: center;">
                <img src="https://i.ibb.co/XJBdx4T/20230220-124429-kopia.jpg" alt="AGV-MAN Cybernetic Interface" class="project-image" />
            </div>
        </div>
        <div class="separator"></div>
    </div>
</div>

<style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Share Tech Mono', monospace;
            background: linear-gradient(135deg, #0a0a0a 0%, #1a0a2e 25%, #16213e 50%, #0f0f23 75%, #000000 100%);
            background-attachment: fixed;
            color: #00ff88;
            height: 100px;
            overflow-x: hidden;
            position: relative;
        }

        /* Cyber grid background */
        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: 
                linear-gradient(rgba(0, 255, 136, 0.03) 1px, transparent 1px),
                linear-gradient(90deg, rgba(0, 255, 136, 0.03) 1px, transparent 1px);
            background-size: 50px 50px;
            z-index: -2;
            animation: gridPulse 4s ease-in-out infinite alternate;
        }

        /* Animated particles */
        body::after {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: radial-gradient(circle, transparent 1px, rgba(0, 255, 136, 0.1) 1px);
            background-size: 100px 100px;
            animation: float 20s linear infinite;
            z-index: -1;
            opacity: 0.3;
        }

        @keyframes gridPulse {
            0% { opacity: 0.3; }
            100% { opacity: 0.1; }
        }

        @keyframes float {
            0% { transform: translateX(0) translateY(0); }
            100% { transform: translateX(-100px) translateY(-100px); }
        }

        @keyframes glitch {
            0%, 95%, 100% { 
                transform: translateX(0) skew(0deg);
                color: #39ff14;
                text-shadow: 0 0 5px #39ff14;
            }
            5% { 
                transform: translateX(-3px) skew(-3deg) rotate(-1deg);
                color: #ff00ff;
                text-shadow: 0 0 8px #ff00ff, 2px 0 10px #00fff2;
            }
            15% { 
                transform: translateX(3px) skew(3deg) rotate(1deg);
                color: #00fff2;
                text-shadow: 0 0 8px #00fff2, -2px 0 10px #ff00ff;
            }
            25% { 
                transform: translateX(-2px) skew(-2deg) rotate(-0.5deg);
                color: #ffea00;
                text-shadow: 0 0 6px #ffea00, 1px 0 8px #39ff14;
            }
            35% { 
                transform: translateX(2px) skew(2deg) rotate(0.5deg);
                color: #ff0099;
                text-shadow: 0 0 6px #ff0099, -1px 0 8px #00fff2;
            }
            50% { 
                transform: translateX(0) skew(0deg) rotate(0deg);
                color: #39ff14;
                text-shadow: 0 0 5px #39ff14;
            }
        }


        @keyframes neonPulse {
        0% {
            text-shadow:
            0 0 5px #ff00ff,
            2px 0 10px #ff6600ff,
            4px 0 15px #00fff2,
            6px 0 20px #39ff14;
            color: #ff00ff;
            transform: skewX(0deg);
        }
        25% {
            text-shadow:
            0 0 5px #00fff2,
            2px 0 10px #39ff14,
            4px 0 15px #ffea00,
            6px 0 20px #ff0000ff;
            color: #00fff2;
            transform: skewX(1deg);
        }
        50% {
            text-shadow:
            0 0 5px #39ff14,
            2px 0 10px #ffea00,
            4px 0 15px #ff0000ff,
            6px 0 20px #00fff2;
            color: #39ff14;
            transform: skewX(-1deg);
        }
        75% {
            text-shadow:
            0 0 5px #ffea00,
            2px 0 10px #ff00ff,
            4px 0 15px #00fff2,
            6px 0 20px #39ff14;
            color: #ffea00;
            transform: skewX(1deg);
        }
        100% {
            text-shadow:
            0 0 5px #ff00ff,
            2px 0 10px #00fff2,
            4px 0 15px #39ff14,
            6px 0 20px #ffea00;
            color: #ff00ff;
            transform: skewX(0deg);
        }
    }


        @keyframes scanline {
            0% { transform: translateY(-100vh); }
            100% { transform: translateY(100vh); }
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 40px 20px;
            position: relative;
            z-index: 1;
        }

        .header {
            text-align: center;
            margin-bottom: 20px;
            position: relative;
        }

        .username {
            font-family: 'Orbitron', monospace;
            font-size: 4rem;
            font-weight: 900;
            color: #ff0080;
            letter-spacing: 8px;
            margin-bottom: 20px;
            animation: neonPulse 2s ease-in-out infinite alternate, glitch 5s infinite;
        }

        .username::before {
            content: 'ZeroDayZ7';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            color: #00ff88;
            animation: glitch 7s infinite ease-in-out;
            z-index: -1;
        }

        .subtitle {
            font-family: 'Orbitron', monospace;
            font-size: 1.5rem;
            color: #00ffff;
            text-transform: uppercase;
            letter-spacing: 3px;
            margin-bottom: 10px;
            text-shadow: 0 0 10px #00ffff;
        }

        .contact-section {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-bottom: 25px;
            flex-wrap: wrap;
        }

        .cyber-button {
            background: linear-gradient(45deg, #1a1a2e, #16213e);
            border: 2px solid #00ff88;
            color: #00ff88;
            text-decoration: none;
            padding: 12px 24px;
            font-family: 'Share Tech Mono', monospace;
            text-transform: uppercase;
            letter-spacing: 2px;
            position: relative;
            overflow: hidden;
            transition: all 0.3s ease;
            clip-path: polygon(10px 0%, 100% 0%, calc(100% - 10px) 100%, 0% 100%);
        }

        .cyber-button::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(0, 255, 136, 0.2), transparent);
            transition: left 0.5s ease;
        }

        .cyber-button:hover {
            color: #000;
            background: #00ff88;
            box-shadow: 0 0 20px #00ff88, inset 0 0 20px rgba(0, 255, 136, 0.2);
            transform: translateY(-2px);
        }

        .cyber-button:hover::before {
            left: 100%;
        }

        .tech-stack {
            display: flex;
            flex-wrap: wrap;
            gap: 25px;
            justify-content: center;
            margin-bottom: 20px;
        }

        .tech-badge {
            background: linear-gradient(135deg, #0f0f23, #1a0a2e);
            border: 1px solid #00ffff;
            color: #00ffff;
            padding: 8px 16px;
            font-family: 'Share Tech Mono', monospace;
            font-size: 0.9rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            position: relative;
            clip-path: polygon(5px 0%, 100% 0%, calc(100% - 5px) 100%, 0% 100%);
            transition: all 0.3s ease;
        }

        .tech-badge:hover {
            background: linear-gradient(135deg, #00ffff, #0080ff);
            color: #000;
            transform: scale(1.05);
            box-shadow: 0 0 15px #00ffff;
        }

        .separator {
            height: 2px;
            background: linear-gradient(90deg, transparent, #ff0080, #00ff88, #00ffff, transparent);
            margin: 20px 0;
            position: relative;
            overflow: hidden;
        }

        .separator::after {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.8), transparent);
            animation: scanline 3s linear infinite;
        }

        .stats-section {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin-bottom: 60px;
            flex-wrap: wrap;
        }

        .stat-card {
            background: linear-gradient(135deg, rgba(26, 10, 46, 0.8), rgba(15, 15, 35, 0.8));
            border: 1px solid #00ff88;
            border-radius: 10px;
            padding: 20px;
            text-align: center;
            backdrop-filter: blur(10px);
            position: relative;
            overflow: hidden;
        }

        .stat-card::before {
            content: '';
            position: absolute;
            top: -2px;
            left: -2px;
            right: -2px;
            bottom: -2px;
            background: linear-gradient(45deg, #ff0080, #00ff88, #00ffff, #ff0080);
            border-radius: 12px;
            z-index: -1;
            animation: neonPulse 3s linear infinite;
            opacity: 0.7;
        }

        .project-section {
            background: linear-gradient(135deg, rgba(26, 10, 46, 0.6), rgba(15, 15, 35, 0.6));
            border: 1px solid #ff0080;
            border-radius: 15px;
            padding: 20px;
            backdrop-filter: blur(15px);
            position: relative;
            overflow: hidden;
        }

        .project-section::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 3px;
            background: linear-gradient(90deg, #ff0080, #00ff88, #00ffff, #ff0080);
            animation: scanline 2s linear infinite;
        }

        .project-title {
            font-family: 'Orbitron', monospace;
            font-size: 2rem;
            color: #ff0080;
            text-transform: uppercase;
            letter-spacing: 3px;
            margin-bottom: 10px;
            text-shadow: 0 0 10px #ff0080;
        }

        .project-description {
            color: #00ffff;
            font-size: 1.1rem;
            margin-bottom: 20px;
            letter-spacing: 1px;
        }

        .project-image {
            width: 70%;
            max-width: 400px;
            border-radius: 10px;
            border: 2px solid #00ff88;
            box-shadow: 0 0 20px rgba(0, 255, 136, 0.3);
            transition: all 0.3s ease;
        }

        .project-image:hover {
            transform: scale(1.02);
            box-shadow: 0 0 30px rgba(0, 255, 136, 0.5);
        }

        /* Scanline effect */
        .scanline {
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            height: 2px;
            background: linear-gradient(90deg, transparent, #00ff88, transparent);
            animation: scanline 4s linear infinite;
            z-index: 1000;
            opacity: 0.5;
        }

        @media (max-width: 768px) {
            .username {
                font-size: 3.5rem;
                letter-spacing: 4px;
            }
            
            .subtitle {
                font-size: 1.2rem;
                letter-spacing: 2px;
            }
            
            .contact-section {
                flex-direction: row;
                align-items: center;
            }
            
            .stats-section {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
