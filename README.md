<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> بوابة السفراء - منصة نحن</title>
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
        input[type="text"], input[type="tel"], select {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 14px;
        }
        input[type="text"]:focus, input[type="tel"]:focus, select:focus {
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
            <select id="university" name="entry.1904839153" required>
                <option value="">اختر الجامعة أو الكلية</option>
                <!-- الجامعات الحكومية -->
                <option value="الجامعة الأردنية">الجامعة الأردنية</option>
                <option value="جامعة اليرموك">جامعة اليرموك</option>
                <option value="جامعة العلوم والتكنولوجيا الأردنية">جامعة العلوم والتكنولوجيا الأردنية</option>
                <option value="جامعة مؤتة">جامعة مؤتة</option>
                <option value="جامعة البلقاء التطبيقية">جامعة البلقاء التطبيقية</option>
                <option value="جامعة الطفيلة التقنية">جامعة الطفيلة التقنية</option>
                <option value="جامعة الحسين بن طلال">جامعة الحسين بن طلال</option>
                <option value="جامعة جدارا">جامعة جدارا</option>
                <option value="جامعة العقبة للتكنولوجيا">جامعة العقبة للتكنولوجيا</option>
                <option value="الجامعة الهاشمية">الجامعة الهاشمية</option>
                <option value="جامعة آل البيت">جامعة آل البيت</option>
                <option value="الجامعة الألمانية الأردنية">الجامعة الألمانية الأردنية</option>
                <option value="فرع الجامعة الأردنية في العقبة">فرع الجامعة الأردنية في العقبة</option>
                
                <!-- الكليات التطبيقية التابعة لجامعة البلقاء التطبيقية -->
                <option value="أكاديمية الأمير حسين للحماية المدنية">أكاديمية الأمير حسين للحماية المدنية</option>
                <option value="كلية العقبة الجامعية">كلية العقبة الجامعية</option>
                <option value="كلية معان الجامعية">كلية معان الجامعية</option>
                <option value="كلية الحصن الجامعية">كلية الحصن الجامعية</option>
                <option value="كلية الكرك الجامعية">كلية الكرك الجامعية</option>
                <option value="كلية إربد الجامعية">كلية إربد الجامعية</option>
                <option value="كلية الزرقاء الجامعية">كلية الزرقاء الجامعية</option>
                <option value="كلية الشوبك الجامعية">كلية الشوبك الجامعية</option>
                <option value="كلية الهندسة التكنولوجية">كلية الهندسة التكنولوجية</option>
                <option value="كلية الأميرة عالية الجامعية">كلية الأميرة عالية الجامعية</option>
                <option value="كلية الأميرة رحمة الجامعية">كلية الأميرة رحمة الجامعية</option>
                <option value="كلية عجلون الجامعية">كلية عجلون الجامعية</option>
                <option value="كلية عمان الجامعية للعلوم المالية والإدارية">كلية عمان الجامعية للعلوم المالية والإدارية</option>
                
                <!-- الجامعات الخاصة -->
                <option value="جامعة ابن سينا للعلوم الطبية">جامعة ابن سينا للعلوم الطبية</option>
                <option value="جامعة العقبة للعلوم الطبية">جامعة العقبة للعلوم الطبية</option>
                <option value="جامعة العقبة للتكنولوجيا">جامعة العقبة للتكنولوجيا</option>
                <option value="جامعة عجلون الوطنية">جامعة عجلون الوطنية</option>
                <option value="الجامعة الأمريكية في مادبا">الجامعة الأمريكية في مادبا</option>
                <option value="جامعة جدارا">جامعة جدارا</option>
                <option value="جامعة الشرق الأوسط">جامعة الشرق الأوسط</option>
                <option value="جامعة عمان العربية">جامعة عمان العربية</option>
                <option value="جامعة الزرقاء">جامعة الزرقاء</option>
                <option value="جامعة إربد الأهلية">جامعة إربد الأهلية</option>
                <option value="جامعة الزيتونة الأردنية">جامعة الزيتونة الأردنية</option>
                <option value="جامعة جرش">جامعة جرش</option>
                <option value="جامعة الأميرة سمية للتكنولوجيا">جامعة الأميرة سمية للتكنولوجيا</option>
                <option value="جامعة الإسراء">جامعة الإسراء</option>
                <option value="جامعة البترا">جامعة البترا</option>
                <option value="جامعة العلوم التطبيقية الخاصة">جامعة العلوم التطبيقية الخاصة</option>
                <option value="جامعة فيلادلفيا">جامعة فيلادلفيا</option>
                <option value="جامعة عمان الأهلية">جامعة عمان الأهلية</option>
                
                <!-- الجامعات الإقليمية والدولية -->
                <option value="الجامعة العربية المفتوحة فرع الأردن">الجامعة العربية المفتوحة فرع الأردن</option>
                
                <!-- الجامعات ذات قانون خاص -->
                <option value="جامعة الحسين التقنية">جامعة الحسين التقنية</option>
                <option value="جامعة العلوم الإسلامية العالمية">جامعة العلوم الإسلامية العالمية</option>
                
                <!-- المستشفيات الجامعية -->
                <option value="مستشفى الجامعة الأردنية">مستشفى الجامعة الأردنية</option>
                <option value="مستشفى الملك المؤسس عبد الله الجامعي">مستشفى الملك المؤسس عبد الله الجامعي</option>
                
                <!-- الكليات الجامعية -->
                <option value="الكلية الجامعية الوطنية للتكنولوجيا">الكلية الجامعية الوطنية للتكنولوجيا</option>
                <option value="كلية طلال أبو غزالة الجامعية للابتكار">كلية طلال أبو غزالة الجامعية للابتكار</option>
                <option value="الأكاديمية الملكية لفنون الطهي">الأكاديمية الملكية لفنون الطهي</option>
                <option value="كلية العلوم التربوية والآداب (جامعة ناعور)">كلية العلوم التربوية والآداب (جامعة ناعور)</option>
                <option value="الأكاديمية الأردنية للموسيقى">الأكاديمية الأردنية للموسيقى</option>
                <option value="كلية لومينوس الجامعية التقنية">كلية لومينوس الجامعية التقنية</option>
                <option value="كلية عمون الجامعية التطبيقية">كلية عمون الجامعية التطبيقية</option>
                <option value="الكلية الجامعية العربية للتكنولوجيا">الكلية الجامعية العربية للتكنولوجيا</option>
                <option value="كلية الخوارزمي الجامعية التقنية">كلية الخوارزمي الجامعية التقنية</option>
                <!-- يمكنك إضافة المزيد من الجامعات والكليات هنا -->
            </select>
            
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
        <p> 2024 بوابة السفراء. جميع الحقوق محفوظة.</p>
        <p>This portal was designed by Engineer Farhan AL- Khawaldeh.</p>
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
