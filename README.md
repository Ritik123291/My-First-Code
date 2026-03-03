Hi there, I'm Ritik! 👋

I'm a passionate learner and an aspiring Full Stack Web Developer from India. I believe that pure hard work and consistency can beat any obstacle. Currently, I am building web projects and mastering coding concepts every single day, right from my mobile phone!

🚀 What I'm currently doing:
- Mastering the core of the web: HTML, CSS, and JavaScript.
- Solving coding challenges and leveling up my problem-solving logic.
- Building a strong foundation to crack a high-paying tech job in the future.

💻 Tech Stack & Tools:
- Frontend: HTML5, CSS3, JavaScript
- Tools: GitHub, Mobile Code Editors

⚡ Fun Fact: My day starts at 5:30 AM. I write my code before the sun comes up and before heading out for my daily physical field work. Dedication and discipline are my biggest superpowers! 





 <!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gram Kalyan Portal | Ritik Dev</title>
    <style>
        /* CSS Settings */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f4f7f6;
            color: #333;
            line-height: 1.6;
        }

        /* Header & Navigation */
        header {
            background: #2c3e50;
            color: white;
            padding: 40px 20px;
            text-align: center;
            border-bottom: 5px solid #27ae60;
        }

        .navbar {
            background: #1a252f;
            padding: 10px;
            text-align: center;
        }

        .navbar span {
            color: #27ae60;
            font-weight: bold;
            font-size: 1.2rem;
        }

        /* Hero Section */
        .hero-text h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        /* Container */
        .container {
            max-width: 1000px;
            margin: 30px auto;
            padding: 0 20px;
        }

        /* Breaking News Bar */
        .news-bar {
            background: #fff;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            margin-bottom: 30px;
            display: flex;
            align-items: center;
        }

        .news-label {
            background: #e74c3c;
            color: white;
            padding: 5px 12px;
            border-radius: 4px;
            font-weight: bold;
            margin-right: 15px;
            font-size: 0.9rem;
        }

        /* Schemes Grid */
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
        }

        .card {
            background: white;
            padding: 25px;
            border-radius: 12px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            transition: 0.3s ease;
            border-top: 4px solid #2980b9;
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 15px rgba(0,0,0,0.1);
        }

        .card h3 {
            color: #2c3e50;
            margin-bottom: 12px;
        }

        .card p {
            font-size: 0.95rem;
            color: #666;
            margin-bottom: 20px;
        }

        .btn {
            background: #27ae60;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            display: inline-block;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 40px;
            background: #2c3e50;
            color: white;
            margin-top: 50px;
        }

        /* Responsive for Mobile */
        @media (max-width: 600px) {
            .hero-text h1 { font-size: 1.8rem; }
            .grid { grid-template-columns: 1fr; }
        }
    </style>
</head>
<body>

    <div class="navbar">
        <span>🇮🇳 ग्राम कल्याण सेवा</span>
    </div>

    <header>
        <div class="hero-text">
            <h1>सरकारी योजना पोर्टल</h1>
            <p>गाँव के विकास के लिए हर जानकारी, अब आपकी भाषा में।</p>
        </div>
    </header>

    <div class="container">
        <div class="news-bar">
            <div class="news-label">नया अपडेट</div>
            <marquee>UP Board Exams 18 February se shuru ho rahe hain! | PM Kisan Yojana ki kist jaari ho gayi hai. | Ration Card list check karein.</marquee>
        </div>

        <div class="grid">
            <div class="card">
                <h2>🚜</h2>
                <h3>PM किसान योजना</h3>
                <p>खेती के लिए सालाना ₹6,000 की सहायता राशि की जानकारी यहाँ प्राप्त करें।</p>
                <a href="#" class="btn">चेक करें</a>
            </div>

            <div class="card" style="border-top-color: #f39c12;">
                <h2>🏠</h2>
                <h3>आवास योजना</h3>
                <p>गरीब परिवारों के लिए पक्का घर बनाने हेतु सरकारी सब्सिडी की पूरी जानकारी।</p>
                <a href="#" class="btn">देखें</a>
            </div>

            <div class="card" style="border-top-color: #8e44ad;">
                <h2>🎓</h2>
                <h3>स्कॉलरशिप 2026</h3>
                <p>10वीं और 12वीं के मेधावी छात्रों के लिए नई छात्रवृत्ति योजनाओं की सूची।</p>
                <a href="#" class="btn">अप्लाई करें</a>
            </div>

            <div class="card" style="border-top-color: #e67e22;">
                <h2>💡</h2>
                <h3>फ्री बिजली कनेक्शन</h3>
                <p>गाँव के हर घर तक मुफ्त बिजली पहुँचाने के लिए रजिस्ट्रेशन की जानकारी।</p>
                <a href="#" class="btn">विवरण</a>
            </div>
        </div>
    </div>

    <footer>
        <p>Developed by <b>Ritik</b> | 2026</p>
        <p style="font-size: 0.8rem; margin-top: 10px; color: #bdc3c7;">Google Coder Goal: Mission 2026</p>
    </footer>

</body>
</html>   