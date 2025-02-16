<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>طريقة معرفة عقد العمل</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Amiri:wght@700&display=swap');

        body {
            font-family: 'Amiri', serif;
            text-align: center;
            direction: rtl;
            background-color: #f9f9f9;
            padding: 20px;
        }
        h1 {
            font-size: 36px;
            font-weight: bold;
            color: #222;
            margin-bottom: 20px;
        }
        .step {
            background: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin-bottom: 30px;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }
        .step p {
            font-size: 20px;
            color: #333;
            margin-bottom: 15px;
        }
        .image-container {
            text-align: center;
        }
        img {
            width: 100%;
            max-width: 500px;
            border-radius: 8px;
            border: 2px solid #ddd;
            box-shadow: 0 2px 6px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        img:hover {
            transform: scale(1.05);
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.3);
        }
        #backToTopBtn {
            display: none;
            position: fixed;
            bottom: 20px;
            right: 20px;
            z-index: 99;
            font-size: 18px;
            border: none;
            outline: none;
            background-color: #007BFF;
            color: white;
            cursor: pointer;
            padding: 15px;
            border-radius: 50%;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        #backToTopBtn:hover {
            background-color: #0056b3;
        }
        @media (max-width: 600px) {
            h1 {
                font-size: 28px;
            }
            .step p {
                font-size: 18px;
            }
            .step {
                padding: 15px;
            }
        }

        /* زر الانتقال إلى منصة قوى */
        .qwa-button {
            position: fixed;
            bottom: 20px;
            left: 20px;
            background-color: #007BFF;
            color: white;
            padding: 15px 25px;
            border-radius: 50px;
            text-decoration: none;
            font-size: 18px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: background-color 0.3s ease, transform 0.3s ease;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        .qwa-button:hover {
            background-color: #0056b3;
            transform: scale(1.05);
        }
        .qwa-button i {
            font-size: 24px;
        }
    </style>
    <!-- رابط مكتبة Font Awesome للأيقونات -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>

    <h1>طريقة معرفة عقد العمل</h1>

    <div class="step">
        <p>1️⃣ بعد الدخول إلى منصة قوى باستخدام اسم المستخدم وكلمة المرور، اختر حسابك الشخصي ثم انقر على <strong>العقود</strong>.</p>
        <div class="image-container">
            <img src="https://www2.0zz0.com/2025/02/16/21/305338641.jpg" alt="لقطة شاشة توضح النقر على العقود">
        </div>
    </div>

    <div class="step">
        <p>2️⃣ بعد النقر على العقود، اختر <strong>عقودك الحالية</strong> من القائمة.</p>
        <div class="image-container">
            <img src="https://www2.0zz0.com/2025/02/16/21/445046670.jpg" alt="لقطة شاشة توضح اختيار عقودك الحالية">
        </div>
    </div>

    <div class="step">
        <p>3️⃣ يمكنك الآن استعراض عقدك الحالي وتفاصيله بالكامل، مثل <strong>تاريخ بدء العقد وتاريخ انتهائه</strong>.</p>
        <div class="image-container">
            <img src="https://www2.0zz0.com/2025/02/16/21/123477069.jpg" alt="لقطة شاشة توضح تفاصيل العقد">
        </div>
    </div>

    <!-- زر الانتقال إلى منصة قوى -->
    <a href="https://qwa.qiwa.sa/" class="qwa-button" target="_blank">
        <i class="fas fa-external-link-alt"></i>
        الانتقال إلى منصة قوى
    </a>

    <button onclick="topFunction()" id="backToTopBtn" title="العودة إلى الأعلى">▲</button>

    <footer style="margin-top: 50px; padding: 20px; background-color: #f1f1f1; text-align: center;">
        <p>© 2025 جميع الحقوق محفوظة.</p>
    </footer>

    <script>
        window.onscroll = function() {scrollFunction()};

        function scrollFunction() {
            if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
                document.getElementById("backToTopBtn").style.display = "block";
            } else {
                document.getElementById("backToTopBtn").style.display = "none";
            }
        }

        function topFunction() {
            document.body.scrollTop = 0;
            document.documentElement.scrollTop = 0;
        }

        window.onbeforeunload = function() {
            return "هل أنت متأكد أنك تريد مغادرة الصفحة؟";
        };
    </script>

</body>
</html>
