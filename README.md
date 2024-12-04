<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> بوابة السفراء -منصة نحن</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #00000; /* لون قريب من منصة نحن */
            margin: 0;
            padding: 20px;
            direction: rtl;
        }
        header {
            background: white; /* خلفية الرأسية بيضاء */
            color: #3cc4cc; /* لون النص أزرق */
            padding: 20px;
            text-align: center;
            border-bottom: 4px solid #3cc4cc; /* خط سفلي أزرق */
        }
        header img {
            width: 120px;
            margin-bottom: 10px;
        }
        main {
            background: #3cc4cc; /* خلفية رئيسية بلون منصة نحن */
            color: white; /* لون النص أبيض */
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            max-width: 600px;
            margin: 20px auto;
        }
        footer {
            text-align: center;
            margin-top: 20px;
            font-size: 0.9em;
            color: #666;
        }
        button {
            background-color: white; /* زر أبيض */
            color: #3cc4cc; /* نص أزرق */
            border: 2px solid #3cc4cc; /* حدود زرقاء */
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            transition: background-color 0.3s ease, color 0.3s ease;
        }
        button:hover {
            background-color: #0056b3; /* لون خلفية عند التمرير */
            color: white; /* نص أبيض عند التمرير */
        }
        label {
            margin-top: 10px;
            display: block;
            font-weight: bold;
            color: white;
        }
        input[type="text"], input[type="tel"] {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 14px;
        }
        input[type="text"]:focus, input[type="tel"]:focus {
            border-color: #007bff; /* لون الحدود عند التفاعل */
            outline: none;
        }
        .success-message {
            display: none;
            background-color: #d4edda;
            color: #155724;
            padding: 10px;
            border: 1px solid #c3e6cb;
            border-radius: 5px;
            margin-top: 15px;
        }
    </style>
</head>
<body>
    <header>
        <img src="https://assets.onecompiler.app/42r523uca/4323gpvvz/logo.png" alt="شعار منصة نحن">
        <h1> بوابة السفراء - منصة نحن </h1>
    </header>
    <main>
        <h2> مرحبا بكم في بوابة السفراء - منصة نحن</h2>
        <p>هذه المنصة مصممة لتسهيل التواصل وتبادل المعلومات.</p>
        <form id="ambassadorsForm">
            <label for="fullName">الاسم الرباعي:</label>
            <input type="text" id="fullName" name="entry.601052600" required>
            
            <label for="university">اسم الجامعة:</label>
            <input type="text" id="university" name="entry.1904839153" required>
            
            <label for="specialization">التخصص:</label>
            <input type="text" id="specialization" name="entry.2012494155" required>
            
            <label for="phone">رقم الهاتف:</label>
            <input type="tel" id="phone" name="entry.1544434453" required>
            
            <button type="submit">دخول</button>
        </form>
        <div class="success-message" id="successMessage">
            تم إرسال بياناتك بنجاح! سيتم تحويلك الآن إلى الصفحة الرئيسية.
        </div>
    </main>
    <footer>
        <p>&copy 2024 بوابة السفراء. جميع الحقوق محفوظة.</p>
    </footer>

    <script>
        document.getElementById("ambassadorsForm").addEventListener("submit", function (e) {
            e.preventDefault(); // منع إعادة تحميل الصفحة

            // عرض رسالة نجاح
            const successMessage = document.getElementById("successMessage");
            successMessage.style.display = "block";

            // إرسال البيانات إلى Google Forms
            const formData = new FormData(this);
            fetch("https://docs.google.com/forms/d/e/1FAIpQLSdjFEUsOF5zJoocZSF84x6I6dAfrvmUqKD7vs4gbcHS50YHyg/formResponse", {
                method: "POST",
                body: formData,
                mode: "no-cors"
            }).then(() => {
                // إعادة التوجيه بعد التأكيد
                setTimeout(() => {
                    window.location.href = "https://fa893.github.io/nahno.un/";
                }, 2000);
            }).catch((error) => {
                alert("حدث خطأ أثناء إرسال البيانات. حاول مرة أخرى.");
                console.error("Error:", error);
            });
        });
    </script>
</body>
</html>
