<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me - Minimal CV</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #b8e3ff, #0583d2, #16558f);
            color: white;
            overflow-x: hidden;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }
        h1, h2, p, li {
            opacity: 0;
            animation: fadeIn 1.5s forwards ease-in-out;
        }
        h1 {
            font-size: 40px;
            text-align: center;
            margin-top: 40px;
            animation-delay: 0.2s;
        }
        h2 {
            font-size: 26px;
            margin-bottom: 15px;
            color: #fcbf49;
        }
        p {
            font-size: 18px;
            line-height: 1.6;
        }
        .content {
            padding: 0 30px;
            margin-top: 20px;
            flex: 1; /* Take up the remaining space */
            animation-delay: 0.4s;
        }
        .section {
            margin-bottom: 30px;
        }
        .section-title {
            font-size: 22px;
            margin-bottom: 10px;
            color: #fcbf49;
            animation-delay: 0.6s;
        }
        .skills, .experience {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .item {
            width: 45%;
            margin-bottom: 20px;
            padding: 15px;
            border-radius: 8px;
            background: rgba(255, 255, 255, 0.15);
            transition: transform 0.3s ease-in-out;
            animation-delay: 0.6s;
        }
        .item:hover {
            transform: scale(1.03);
        }
        ul {
            list-style: none;
            padding-left: 0;
        }
        li {
            font-size: 18px;
            margin-bottom: 8px;
        }
        .footer {
            text-align: center;
            padding: 15px;
            background-color: rgba(255, 255, 255, 0.15);
            color: #fff;
            font-size: 16px;
            animation-delay: 0.8s;
        }
        /* Animation */
        @keyframes fadeIn {
            0% {
                opacity: 0;
                transform: translateY(30px);
            }
            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @media (max-width: 768px) {
            .item {
                width: 90%;
            }
        }
    </style>
</head>
<body>

    <h1>Alexandros Passas</h1>

    <div class="content">
        <div class="section">
            <h2>About Me</h2>
            <p>I am a full-stack developer passionate about building functional, responsive, and modern websites. I thrive on collaboration and always stay updated with current web trends to create meaningful user experiences.</p>
        </div>

        <div class="section skills">
            <div class="item">
                <h3 class="section-title">Skills</h3>
                <ul>
                    <li>HTML & CSS</li>
                    <li>JavaScript (ES6+)</li>
                    <li>React & Redux</li>
                    <li>Responsive Web Design</li>
                    <li>PHP & MySQL</li>
                    <li>WordPress</li>
                    <li>Bootstrap</li>
                </ul>
            </div>
            <div class="item">
                <h3 class="section-title">Education</h3>
                <p>Full-Stack Web Developer</p>
                <p>Social Hackers Academy, May 2023 - Dec 2023</p>
            </div>
        </div>

        <div class="section experience">
            <div class="item">
                <h3 class="section-title">Work Experience</h3>
                <p><strong>Web Developer</strong> - Vibrand Agency (June 2024 - Present)</p>
                <p>Developed interactive and responsive websites, ensuring top performance and excellent user experiences for a wide range of clients.</p>
            </div>
            <div class="item">
                <h3 class="section-title">Projects</h3>
                <p><strong>Portfolio Website:</strong> A personal portfolio showcasing my skills and projects.</p>
                <p><strong>E-commerce Platform:</strong> Built an online shopping platform using React and Node.js.</p>
            </div>
        </div>

        <div class="footer">
            <p>Contact me: alex09.ap19@gmail.com | +306980819054 | LinkedIn: linkedin.com/in/alexandros-passas-511624264/</p>
        </div>
    </div>

</body>
</html>
