<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Desi Shuddh</title>
    <link href="https://fonts.googleapis.com/css2?family=Baloo+2:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Baloo 2', cursive;
            margin: 0;
            padding: 0;
            background: #fffaf0;
            color: #333;
        }

        /* Header */
        header {
            background: linear-gradient(90deg, #ff704d, #ffab91);
            color: white;
            padding: 40px 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 3em;
        }
        header p {
            font-size: 1.2em;
        }

        /* Navigation */
        nav {
            background: #ffab91;
            display: flex;
            justify-content: center;
            gap: 25px;
            padding: 15px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
        }
        nav a:hover {
            color: #fff3e0;
        }

        /* Sections */
        section {
            padding: 60px 20px;
            max-width: 1000px;
            margin: auto;
        }
        section h2 {
            text-align: center;
            font-size: 2.5em;
            margin-bottom: 20px;
            color: #ff704d;
        }
        section p, section ul {
            font-size: 1.1em;
            line-height: 1.8em;
            text-align: center;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        ul li {
            background: #ffe0cc;
            margin: 10px 0;
            padding: 15px;
            border-radius: 10px;
        }

        /* Buttons */
        .btn {
            display: inline-block;
            background: #ff704d;
            color: white;
            padding: 12px 25px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
        }
        .btn:hover {
            background: #ffab91;
        }

        /* Footer */
        footer {
            background: linear-gradient(90deg, #ff704d, #ffab91);
            color: white;
            text-align: center;
            padding: 25px 0;
        }

        /* Responsive Images */
        .section-img {
            width: 100%;
            max-width: 600px;
            display: block;
            margin: 20px auto;
            border-radius: 20px;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2.2em;
            }
            section h2 {
                font-size: 2em;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Desi Shuddh</h1>
    <p>शुद्ध देसी स्वाद और संस्कृति के लिए आपका स्वागत है</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
</nav>

<section id="home">
    <h2>स्वागत है Desi Shuddh में!</h2>
    <img src="https://via.placeholder.com/600x350?text=Desi+Shuddh" alt="Desi Shuddh" class="section-img">
    <p>हम लाते हैं आपके लिए शुद्ध देसी स्वाद, संस्कृति और उत्पाद। यहां आपको मिलेगा सबसे अच्छा देसी अनुभव।</p>
    <a href="#contact" class="btn">हमसे संपर्क करें</a>
</section>

<section id="about">
    <h2>हमारे बारे में</h2>
    <img src="https://via.placeholder.com/600x350?text=About+Us" alt="About Desi Shuddh" class="section-img">
    <p>Desi Shuddh एक ऐसा प्लेटफ़ॉर्म है जो देसी परंपरा और शुद्धता को बढ़ावा देता है। हम आपके लिए केवल सर्वोत्तम उत्पाद और जानकारी लाते हैं।</p>
</section>

<section id="services">
    <h2>हमारी सेवाएँ</h2>
    <ul>
        <li>देसी उत्पादों की बिक्री</li>
        <li>भारतीय संस्कृति और रेसिपीज़ साझा करना</li>
        <li>ऑनलाइन शुद्धता और हेल्थ टिप्स</li>
    </ul>
</section>

<section id="contact">
    <h2>संपर्क करें</h2>
    <p>Email: desishuddh49@example.com</p>
    <p>फोन: +91 8544068642</p>
    <ahref="mailto:desishuddh49@example.com" class="btn">ईमेल भेजें</a>
</section>

<footer>
    <p>&copy; 2025 Desi Shuddh. सभी अधिकार सुरक्षित।</p>
</footer>

</body>
</html>
