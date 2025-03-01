<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fayza Travel Agency</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- الشريط العلوي -->
    <header>
        <h1>Fayza Travel Agency</h1>
        <nav>
            <ul>
                <li><a href="#home">الرئيسية</a></li>
                <li><a href="#travel">السفر والسياحة</a></li>
                <li><a href="#study">الدراسة في الخارج</a></li>
                <li><a href="#migration">الهجرة والعمل</a></li>
                <li><a href="#scholarships">المنح الدراسية</a></li>
                <li><a href="#contact">تواصل معنا</a></li>
            </ul>
        </nav>
    </header>

    <!-- القسم الرئيسي -->
    <section id="home">
        <h2>مرحبًا بك في Fayza Travel Agency</h2>
        <p>نحن نوفر لك كل ما تحتاجه للسفر، السياحة، الدراسة، والهجرة بسهولة وأمان.</p>
    </section>

    <!-- قسم السفر والسياحة -->
    <section id="travel">
        <h2>السفر والسياحة</h2>
        <p>اكتشف أفضل الوجهات السياحية حول العالم بأفضل الأسعار.</p>
    </section>

    <!-- قسم الدراسة في الخارج -->
    <section id="study">
        <h2>الدراسة في الخارج</h2>
        <p>نوفر لك دليل شامل عن الجامعات والمنح الدراسية.</p>
    </section>

    <!-- قسم الهجرة والعمل -->
    <section id="migration">
        <h2>الهجرة والعمل</h2>
        <p>تعرف على أفضل الدول للهجرة وفرص العمل المتاحة.</p>
    </section>

    <!-- قسم المنح الدراسية -->
    <section id="scholarships">
        <h2>المنح الدراسية</h2>
        <p>اكتشف أحدث المنح الدراسية وكيفية التقديم عليها.</p>
    </section>

    <!-- قسم التواصل -->
    <section id="contact">
        <h2>تواصل معنا</h2>
        <form>
            <label for="name">الاسم:</label>
            <input type="text" id="name" required>
            
            <label for="email">البريد الإلكتروني:</label>
            <input type="email" id="email" required>
            
            <label for="message">رسالتك:</label>
            <textarea id="message" required></textarea>
            
            <button type="submit">إرسال</button>
        </form>
    </section>

    <!-- الفوتر -->
    <footer>
        <p>جميع الحقوق محفوظة &copy; 2025 Fayza Travel Agency</p>
    </footer>

</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    text-align: center;
    direction: rtl;
    background-color: #f8f9fa;
    margin: 0;
    padding: 0;
}

header {
    background: #007bff;
    color: white;
    padding: 15px;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

section {
    padding: 20px;
    margin: 20px auto;
    width: 80%;
    background: white;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

form {
    display: flex;
    flex-direction: column;
    width: 50%;
    margin: auto;
}

input, textarea, button {
    margin: 10px 0;
    padding: 10px;
    border-radius: 5px;
    border: 1px solid #ccc;
}

button {
    background: #007bff;
    color: white;
    font-size: 16px;
    cursor: pointer;
}

button:hover {
    background: #0056b3;
}

footer {
    background: #333;
    color: white;
    padding: 10px;
    margin-top: 20px;
}
document.addEventListener("DOMContentLoaded", function() {
    document.querySelector("form").addEventListener("submit", function(event) {
        event.preventDefault();
        alert("تم إرسال رسالتك بنجاح! سنتواصل معك قريبًا.");
    });
});
