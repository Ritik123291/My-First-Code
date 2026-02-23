# My-First-Code
Repository name: Learning-Coding ​Description: My journey from village to Google. ​README: <!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gramin Yojana Portal</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>🏠 ग्राम सेवा पोर्टल</h1>
        <p>सरकारी योजनाओं की जानकारी सबसे पहले यहाँ</p>
    </header>

    <div class="container">
        <div class="alert-box">
            <marquee>🔔 नई अपडेट: पीएम किसान 17वीं किस्त की जानकारी आ गई है! | राशन कार्ड की नई लिस्ट जारी...</marquee>
        </div>

        <section class="schemes">
            <h2>मुख्य योजनाएं (Top Schemes)</h2>
            <div class="grid">
                <div class="card">
                    <h3>👨‍🌾 किसान सम्मान निधि</h3>
                    <p>खेती के लिए सालाना ₹6,000 की सहायता।</p>
                    <a href="#" class="btn">चेक करें</a>
                </div>
                <div class="card">
                    <h3>👩‍🍳 उज्ज्वला योजना</h3>
                    <p>मुफ्त गैस कनेक्शन और सब्सिडी की जानकारी।</p>
                    <a href="#" class="btn">चेक करें</a>
                </div>
                <div class="card">
                    <h3>🏘️ आवास योजना</h3>
                    <p>पक्का घर बनाने के लिए सरकारी मदद।</p>
                    <a href="#" class="btn">चेक करें</a>
                </div>
                <div class="card">
                    <h3>📚 फ्री साइकिल/लैपटॉप</h3>
                    <p>विद्यार्थियों के लिए विशेष राज्य योजनाएं।</p>
                    <a href="#" class="btn">चेक करें</a>
                </div>
            </div>
        </section>

        <section class="notify">
            <h3>नयी योजना की सूचना WhatsApp पर पायें</h3>
            <input type="text" placeholder="अपना नाम लिखें">
            <input type="number" placeholder="WhatsApp नंबर">
            <button class="submit-btn">Register करें</button>
        </section>
    </div>

    <footer>
        <p>&copy; 2026 आपका गांव - आपकी सेवा</p>
    </footer>

</body>
</html>
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    background-color: #f4f7f6;
    color: #333;
}

header {
    background-color: #2c3e50;
    color: white;
    text-align: center;
    padding: 20px 0;
}

.container {
    max-width: 900px;
    margin: auto;
    padding: 20px;
}

.alert-box {
    background: #e74c3c;
    color: white;
    padding: 10px;
    border-radius: 5px;
    margin-bottom: 20px;
}

.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
}

.card {
    background: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    text-align: center;
    border-top: 5px solid #27ae60;
}

.btn {
    display: inline-block;
    margin-top: 10px;
    padding: 10px 20px;
    background: #27ae60;
    color: white;
    text-decoration: none;
    border-radius: 5px;
}

.notify {
    margin-top: 40px;
    background: #ecf0f1;
    padding: 30px;
    border-radius: 10px;
    text-align: center;
}

input {
    padding: 10px;
    margin: 10px;
    width: 80%;
    max-width: 300px;
}

.submit-btn {
    padding: 10px 20px;
    background: #2980b9;
    color: white;
    border: none;
    cursor: pointer;
    border-radius: 5px;
}

footer {
    text-align: center;
    padding: 20px;
    background: #333;
    color: white;
    margin-top: 50px;
}