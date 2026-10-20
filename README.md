<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>رایان | پلتفرم ابزارها و داشبوردهای تخصصی</title>
    <!-- Vazirmatn Font -->
    <link href="https://cdn.jsdelivr.net/gh/rastikerdar/vazirmatn@v33.003/Vazirmatn-font-face.css" rel="stylesheet" type="text/css" />
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Vazirmatn', sans-serif;
        }
        body {
            background-color: #f4f6f9;
            color: #333;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
        }
        /* Navbar تمام صفحه */
        header {
            background: #1e293b;
            color: white;
            padding: 1rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 4px 6px -1px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
            z-index: 1000;
            width: 100%;
        }
        .logo {
            font-size: 1.5rem;
            font-weight: 800;
            color: #38bdf8;
            text-decoration: none;
        }
        .nav-links {
            display: flex;
            gap: 1.5rem;
            list-style: none;
        }
        .nav-links a {
            color: #cbd5e1;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.2s;
        }
        .nav-links a:hover {
            color: #38bdf8;
        }

        /* بخش اصلی تمام صفحه */
        main {
            flex: 1;
            width: 100%;
            padding: 2.5rem 2rem;
        }
        .hero {
            text-align: center;
            margin-bottom: 3rem;
        }
        .hero h1 {
            font-size: 2.5rem;
            color: #0f172a;
            margin-bottom: 0.5rem;
        }
        .hero p {
            color: #64748b;
            font-size: 1.1rem;
        }

        /* گرید کارت‌ها */
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            width: 100%;
        }
        .card {
            background: white;
            border-radius: 12px;
            padding: 1.5rem;
            box-shadow: 0 4px 6px -1px rgba(0,0,0,0.05);
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            transition: transform 0.2s, box-shadow 0.2s;
            border-top: 4px solid #38bdf8;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px -3px rgba(0,0,0,0.1);
        }
        .card h3 {
            font-size: 1.3rem;
            color: #1e293b;
            margin-bottom: 0.75rem;
        }
        .card p {
            color: #64748b;
            font-size: 0.95rem;
            margin-bottom: 1.5rem;
            line-height: 1.6;
        }
        .btn {
            background: #0284c7;
            color: white;
            text-align: center;
            padding: 0.75rem 1rem;
            border-radius: 8px;
            text-decoration: none;
            font-weight: 600;
            transition: background 0.2s;
        }
        .btn:hover {
            background: #0369a1;
        }
        .btn-disabled {
            background: #94a3b8;
            cursor: not-allowed;
        }

        /* فوتر */
        footer {
            background: #0f172a;
            color: #94a3b8;
            text-align: center;
            padding: 1.5rem;
            font-size: 0.9rem;
            width: 100%;
            margin-top: auto;
        }

        @media (max-width: 768px) {
            header { padding: 1rem; }
            main { padding: 1.5rem 1rem; }
            .hero h1 { font-size: 2rem; }
        }
    </style>
</head>
<body>

    <!-- هدر بالای سایت با دسترسی سریع -->
    <header>
        <a href="index.html" class="logo">رایان (Rayan)</a>
        <ul class="nav-links">
            <li><a href="index.html">خانه</a></li>
            <li><a href="#categories">دسته‌بندی‌ها</a></li>
        </ul>
    </header>

    <!-- بدنه اصلی تمام‌صفحه -->
    <main>
        <div class="hero">
            <h1>پلتفرم ابزارها و داشبوردهای تخصصی</h1>
            <p>راهکارهای تعاملی سریع برای مسائل مهندسی، صنعت، خودرو و زندگی روزمره</p>
        </div>

        <div id="categories" class="grid">
            <!-- کارت صنعت و انرژی -->
            <div class="card">
                <div>
                    <h3>صنعت و انرژی</h3>
                    <p>بهینه‌سازی تجهیزات دوار، تحلیل مصرف انرژی، خط پایه SEC و محاسبات مهندسی.</p>
                </div>
                <a href="impeller_optimizer (1).html" class="btn">ورود به بهینه‌ساز ایمپلر</a>
            </div>

            <!-- کارت خودرو -->
            <div class="card">
                <div>
                    <h3>خودرو</h3>
                    <p>عیب‌یاب هوشمند سیستم‌های خودرو، تحلیل کدهای خطا و بررسی عملکرد فنی.</p>
                </div>
                <a href="#" class="btn btn-disabled">به زودی...</a>
            </div>

            <!-- کارت پزشکی و سلامت -->
            <div class="card">
                <div>
                    <h3>پزشکی و سلامت</h3>
                    <p>داشبوردهای ارزیابی سلامت، پایش شاخص‌های حیاتی و ابزارهای محاسباتی پزشکی.</p>
                </div>
                <a href="#" class="btn btn-disabled">به زودی...</a>
            </div>

            <!-- کارت لوازم خانگی -->
            <div class="card">
                <div>
                    <h3>لوازم خانگی</h3>
                    <p>راهنمای عیب‌یابی و محاسبه راندمان و مصرف انرژی لوازم خانگی.</p>
                </div>
                <a href="#" class="btn btn-disabled">به زودی...</a>
            </div>

            <!-- کارت روانشناسی و منابع انسانی -->
            <div class="card">
                <div>
                    <h3>روانشناسی و منابع انسانی</h3>
                    <p>آزمون‌های ارزیابی سازمانی، تحلیل بهره‌وری نیروی کار و ابزارهای HR.</p>
                </div>
                <a href="#" class="btn btn-disabled">به زودی...</a>
            </div>
        </div>
    </main>

    <!-- فوتر -->
    <footer>
        <p>تمامی حقوق محفوظ است | پلتفرم هوشمند رایان</p>
    </footer>

</body>
</html>
