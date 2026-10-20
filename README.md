<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>سایت رایان | داشبورد دانش، تجربیات و راه حل‌های کاربردی</title>
    <link href="https://cdn.jsdelivr.net/gh/rastikerdar/vazirmatn@v33.003/Vazirmatn-font-face.css" rel="stylesheet" type="text/css" />
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Vazirmatn', sans-serif;
        }
        body {
            background-color: #f4f7f6;
            color: #333;
            line-height: 1.7;
        }
        header {
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            color: white;
            padding: 50px 20px;
            text-align: center;
        }
        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        header p {
            font-size: 1.1rem;
            opacity: 0.9;
        }
        nav {
            background-color: #fff;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
            display: flex;
            justify-content: center;
            gap: 25px;
            padding: 15px;
            position: sticky;
            top: 0;
            z-index: 100;
            flex-wrap: wrap;
        }
        nav a {
            text-decoration: none;
            color: #203a43;
            font-weight: bold;
            transition: 0.3s;
        }
        nav a:hover {
            color: #ff6b6b;
        }
        .container {
            max-width: 1200px;
            margin: 30px auto;
            padding: 0 20px;
        }
        .section-title {
            font-size: 1.7rem;
            margin: 40px 0 20px 0;
            color: #0f2027;
            border-right: 5px solid #2c5364;
            padding-right: 12px;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
        }
        .card {
            background: white;
            border-radius: 12px;
            padding: 25px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            transition: transform 0.3s, box-shadow 0.3s;
            border-top: 4px solid #203a43;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.1);
        }
        .card h3 {
            margin-bottom: 12px;
            color: #203a43;
            font-size: 1.25rem;
        }
        .card p {
            color: #666;
            margin-bottom: 20px;
            font-size: 0.95rem;
        }
        .btn {
            display: inline-block;
            background-color: #203a43;
            color: white;
            padding: 8px 18px;
            border-radius: 6px;
            text-decoration: none;
            font-size: 0.9rem;
            transition: background 0.3s;
        }
        .btn:hover {
            background-color: #0f2027;
        }
        footer {
            background-color: #111;
            color: white;
            text-align: center;
            padding: 25px;
            margin-top: 60px;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>سایت رایان</h1>
        <p>داشبورد جامع دانش، تجربیات عملی و راهکارهای حل مسئله در زندگی و کار</p>
    </header>

    <nav>
        <a href="#health">سلامت و پزشکی</a>
        <a href="#car">خودرو و فنی</a>
        <a href="#home">تاسیسات منزل</a>
        <a href="#management">مدیریت و منابع انسانی</a>
        <a href="#apps">اپلیکیشن‌ها</a>
    </nav>

    <div class="container">
        
        <!-- بخش سلامت و پزشکی -->
        <section id="health">
            <h2 class="section-title">سلامت، پزشکی و طب سنتی</h2>
            <div class="grid">
                <div class="card" style="border-color: #e74c3c;">
                    <h3>راهکارهای مقابله با ریزش مو</h3>
                    <p>بررسی دلایل رایج ریزش مو، روش‌های پیشگیری و درمان‌های تلفیقی پزشکی و طب سنتی.</p>
                    <a href="#" class="btn" style="background-color: #e74c3c;">مطالعه راهنما</a>
                </div>
                <div class="card" style="border-color: #e74c3c;">
                    <h3>مدیریت و درمان خانگی شکم‌درد</h3>
                    <p>شناخت انواع شکم‌درد، روش‌های تسکین سریع و زمان مراجعه به پزشک.</p>
                    <a href="#" class="btn" style="background-color: #e74c3c;">مطالعه راهنما</a>
                </div>
            </div>
        </section>

        <!-- بخش خودرو و فنی -->
        <section id="car">
            <h2 class="section-title">خودرو و تعمیرات فنی</h2>
            <div class="grid">
                <div class="card" style="border-color: #f39c12;">
                    <h3>علت روشن شدن چراغ چک ماشین</h3>
                    <p>چرا چراغ چک روشن می‌شود؟ بررسی خطاهای رایج، سنسور اکسیژن، خطاهای بنزین و اقدامات اولیه.</p>
                    <a href="#" class="btn" style="background-color: #f39c12;">مطالعه راهنما</a>
                </div>
            </div>
        </section>

        <!-- بخش تاسیسات منزل -->
        <section id="home">
            <h2 class="section-title">تاسیسات و رفع مشکلات منزل</h2>
            <div class="grid">
                <div class="card" style="border-color: #3498db;">
                    <h3>عیب‌یابی و تعمیر آبگرمکن منزل</h3>
                    <p>چرا آبگرمکن گرم نمی‌کند یا خاموش می‌شود؟ راهنمای گام‌به‌گام عیب‌یابی پکیج و آبگرمکن دیواری.</p>
                    <a href="#" class="btn" style="background-color: #3498db;">مطالعه راهنما</a>
                </div>
            </div>
        </section>

        <!-- بخش مدیریت و منابع انسانی -->
        <section id="management">
            <h2 class="section-title">مدیریت، منابع انسانی و حل تعارض</h2>
            <div class="grid">
                <div class="card" style="border-color: #2ecc71;">
                    <h3>مدیریت افراد و حل تعارض در محیط کار</h3>
                    <p>چگونه تنش‌های بین کارکنان را مدیریت کنیم و به حل مسالمت‌آمیز تعارضات سازمانی بپردازیم؟</p>
                    <a href="#" class="btn" style="background-color: #2ecc71;">مطالعه راهنما</a>
                </div>
            </div>
        </section>

        <!-- بخش اپلیکیشن‌ها -->
        <section id="apps">
            <h2 class="section-title">اپلیکیشن‌ها و ابزارهای کاربردی</h2>
            <div class="grid">
                <div class="card" style="border-color: #9b59b6;">
                    <h3>ابزارهای محاسباتی رایان</h3>
                    <p>مجموعه مینی‌پروژه‌ها و ابزارهای دیجیتال برای تسهیل محاسبات روزمره.</p>
                    <a href="#" class="btn" style="background-color: #9b59b6;">مشاهده ابزارها</a>
                </div>
            </div>
        </section>

    </div>

    <footer>
        <p>تمامی حقوق محفوظ است | طراحی شده در داشبورد جامع «رایان»</p>
    </footer>

</body>
</html>
