<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>سایت رایان | مرجع آموزش، مقالات و اپلیکیشن‌ها</title>
    <!-- استفاده از فونت زیبای وزیرمتن -->
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
            line-height: 1.6;
        }
        header {
            background: linear-gradient(135deg, #1e3c72, #2a5298);
            color: white;
            padding: 40px 20px;
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
            gap: 20px;
            padding: 15px;
            position: sticky;
            top: 0;
            z-index: 100;
        }
        nav a {
            text-decoration: none;
            color: #2a5298;
            font-weight: bold;
            transition: 0.3s;
        }
        nav a:hover {
            color: #ff6b6b;
        }
        .container {
            max-width: 1100px;
            margin: 30px auto;
            padding: 0 20px;
        }
        .section-title {
            font-size: 1.8rem;
            margin-bottom: 20px;
            color: #1e3c72;
            border-right: 5px solid #2a5298;
            padding-right: 10px;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-bottom: 40px;
        }
        .card {
            background: white;
            border-radius: 12px;
            padding: 20px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.05);
            transition: transform 0.3s;
        }
        .card:hover {
            transform: translateY(-5px);
        }
        .card h3 {
            margin-bottom: 10px;
            color: #2a5298;
        }
        .card p {
            color: #666;
            margin-bottom: 15px;
            font-size: 0.95rem;
        }
        .btn {
            display: inline-block;
            background-color: #2a5298;
            color: white;
            padding: 8px 16px;
            border-radius: 6px;
            text-decoration: none;
            font-size: 0.9rem;
            transition: background 0.3s;
        }
        .btn:hover {
            background-color: #1e3c72;
        }
        footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 50px;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>سایت رایان</h1>
        <p>مجموعه‌ای از تجربیات، مقالات آموزشی و اپلیکیشن‌های کاربردی</p>
    </header>

    <nav>
        <a href="#articles">مقالات و تجربیات</a>
        <a href="#apps">اپلیکیشن‌ها</a>
        <a href="#about">درباره رایان</a>
    </nav>

    <div class="container">
        
        <!-- بخش مقالات -->
        <section id="articles">
            <h2 class="section-title">آخرین مقالات و تجربیات</h2>
            <div class="grid">
                <div class="card">
                    <h3>تجربیات مدیریت انرژی و بهینه‌سازی</h3>
                    <p>در این مقاله به بررسی راهکارهای عملی کاهش مصرف انرژی و افزایش بهره‌وری در صنایع می‌پردازیم.</p>
                    <a href="#" class="btn">مطالعه مقاله</a>
                </div>
                <div class="card">
                    <h3>مسیر یادگیری برنامه‌نویسی برای همه</h3>
                    <p>چطور بدون داشتن پیش‌زمینه فنی، قدم به دنیای جذاب برنامه‌نویسی و ساخت وب بگذاریم؟</p>
                    <a href="#" class="btn">مطالعه مقاله</a>
                </div>
            </div>
        </section>

        <!-- بخش اپلیکیشن‌ها -->
        <section id="apps">
            <h2 class="section-title">اپلیکیشن‌های کاربردی</h2>
            <div class="grid">
                <div class="card">
                    <h3>نرم‌افزار محاسبات مهندسی رایان</h3>
                    <p>ابزاری کاربردی برای انجام محاسبات سریع و دقیق در حوزه‌های صنعتی و مهندسی.</p>
                    <a href="#" class="btn">دانلود اپلیکیشن</a>
                </div>
                <div class="card">
                    <h3>چک‌لیست دیجیتال مدیران</h3>
                    <p>اپلیکیشنی برای مدیریت روزانه وظایف، چک‌لیست‌ها و نظارت بر پایش‌های دوره‌ای.</p>
                    <a href="#" class="btn">دانلود اپلیکیشن</a>
                </div>
            </div>
        </section>

    </div>

    <footer>
        <p>تمامی حقوق محفوظ است | طراحی شده در سایت رایان</p>
    </footer>

</body>
</html>
