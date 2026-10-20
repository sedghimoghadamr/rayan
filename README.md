<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>رایان | مرجع هوشمند داشبوردها و ابزارهای کاربردی</title>
    <!-- فونت وزیرمتن -->
    <link href="https://cdn.jsdelivr.net/gh/rastikerdar/vazirmatn@v33.003/Vazirmatn-font-face.css" rel="stylesheet" type="text/css" />
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Vazirmatn', sans-serif;
        }
        body {
            background-color: #f8fafc;
            color: #1e293b;
            line-height: 1.6;
        }
        header {
            background: linear-gradient(135deg, #0f172a 0%, #1e3a8a 100%);
            color: white;
            padding: 3rem 1rem;
            text-align: center;
        }
        header h1 {
            font-size: 2.2rem;
            margin-bottom: 0.5rem;
            font-weight: 800;
        }
        header p {
            font-size: 1.1rem;
            color: #94a3b8;
            max-width: 600px;
            margin: 0 auto;
        }
        .container {
            max-width: 1200px;
            margin: -2rem auto 3rem auto;
            padding: 0 1.5rem;
            position: relative;
        }
        .category-section {
            margin-bottom: 3rem;
        }
        .category-title {
            font-size: 1.4rem;
            font-weight: 700;
            margin-bottom: 1.2rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
            color: #0f172a;
            border-right: 4px solid #3b82f6;
            padding-right: 0.75rem;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
            gap: 1.5rem;
        }
        .card {
            background: white;
            border-radius: 16px;
            padding: 1.5rem;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05), 0 2px 4px -1px rgba(0, 0, 0, 0.03);
            transition: all 0.3s ease;
            border: 1px solid #e2e8f0;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.08);
            border-color: #cbd5e1;
        }
        .card-icon {
            font-size: 2.2rem;
            margin-bottom: 1rem;
        }
        .card h3 {
            font-size: 1.2rem;
            margin-bottom: 0.5rem;
            color: #0f172a;
        }
        .card p {
            font-size: 0.9rem;
            color: #64748b;
            margin-bottom: 1.5rem;
        }
        .card-btn {
            display: inline-block;
            background-color: #f1f5f9;
            color: #1e293b;
            text-align: center;
            padding: 0.6rem 1rem;
            border-radius: 8px;
            text-decoration: none;
            font-weight: 600;
            font-size: 0.9rem;
            transition: all 0.2s;
        }
        .card-btn:hover {
            background-color: #3b82f6;
            color: white;
        }
        footer {
            text-align: center;
            padding: 2rem;
            color: #94a3b8;
            font-size: 0.85rem;
            border-top: 1px solid #e2e8f0;
            background: white;
        }
        @media (max-width: 768px) {
            header h1 { font-size: 1.8rem; }
            .container { margin-top: -1rem; }
        }
    </style>
</head>
<body>

    <header>
        <h1>سامانه جامع داشبوردهای تخصصی رایان</h1>
        <p>مجموعه‌ای از ابزارهای محاسباتی، پایش و حل مسئله تعاملی برای صنعت، خودرو، سلامت و مدیریت</p>
    </header>

    <div class="container">

        <!-- بخش صنعت و انرژی -->
        <div class="category-section">
            <h2 class="category-title">⚙️ صنعت و انرژی</h2>
            <div class="grid">
                <div class="card">
                    <div>
                        <div class="card-icon">🔄</div>
                        <h3>بهینه‌ساز چیدمان ایمپلر</h3>
                        <p>محاسبه و بهینه‌سازی بالانس ضد تیغ‌ها و روبندها بر اساس استاندارد و شعاع نصب.</p>
                    </div>
                    <a href="impeller_optimizer.html" class="card-btn">ورود به داشبورد</a>
                </div>
                <div class="card">
                    <div>
                        <div class="card-icon">⚡</div>
                        <h3>پایش مصرف انرژی و بار</h3>
                        <p>محاسبه خطوط پایه مصرف برق، گاز و راندمان تجهیزات کارگاهی.</p>
                    </div>
                    <a href="#" class="card-btn">به زودی...</a>
                </div>
            </div>
        </div>

        <!-- بخش خودرو -->
        <div class="category-section">
            <h2 class="category-title">🚗 خودرو و نگهداری</h2>
            <div class="grid">
                <div class="card">
                    <div>
                        <div class="card-icon">🛠️</div>
                        <h3>عیب‌یاب هوشمند چراغ چک</h3>
                        <p>بررسی کدهای خطا، علائم بالینی موتور و راهنمای گام‌به‌گام رفع عیب.</p>
                    </div>
                    <a href="#" class="card-btn">ورود به داشبورد</a>
                </div>
            </div>
        </div>

        <!-- بخش پزشکی و سلامت -->
        <div class="category-section">
            <h2 class="category-title">🩺 پزشکی و سلامت (سنتی/مدرن)</h2>
            <div class="grid">
                <div class="card">
                    <div>
                        <div class="card-icon">🌿</div>
                        <h3>پایشگر و راهکار ریزش مو</h3>
                        <p>ارزیابی الگوهای ریزش، بررسی عوامل تغذیه‌ای، هورمونی و راهکارهای درمانی.</p>
                    </div>
                    <a href="#" class="card-btn">ورود به داشبورد</a>
                </div>
                <div class="card">
                    <div>
                        <div class="card-icon">🍵</div>
                        <h3>تسکین و عیب‌یابی معده‌درد</h3>
                        <p>تشخیص افتراقی علائم گوارشی و توصیه‌های فوری طب سنتی و مدرن.</p>
                    </div>
                    <a href="#" class="card-btn">ورود به داشبورد</a>
                </div>
            </div>
        </div>

        <!-- بخش لوازم خانگی -->
        <div class="category-section">
            <h2 class="category-title">🏠 تعمیرات لوازم خانگی</h2>
            <div class="grid">
                <div class="card">
                    <div>
                        <div class="card-icon">🔥</div>
                        <h3>عیب‌یاب و سرویس آبگرمکن</h3>
                        <p>راهنمای عیب‌یابی شمعک، فشار آب، مشکلات احتراق و رسوب‌زدایی.</p>
                    </div>
                    <a href="#" class="card-btn">ورود به داشبورد</a>
                </div>
            </div>
        </div>

        <!-- بخش مدیریت و منابع انسانی -->
        <div class="category-section">
            <h2 class="category-title">👥 مدیریت و منابع انسانی</h2>
            <div class="grid">
                <div class="card">
                    <div>
                        <div class="card-icon">🤝</div>
                        <h3>مدیریت تعارض و حل اختلاف</h3>
                        <p>ابزار گام‌به‌گام میانجی‌گری، تحلیل رفتار سازمانی و حل کشمکش‌های کاری.</p>
                    </div>
                    <a href="#" class="card-btn">ورود به داشبورد</a>
                </div>
            </div>
        </div>

    </div>

    <footer>
        <p>تمامی حقوق محفوظ است | پلتفرم رایان (Rayan Hub) مجهز به ابزارهای محاسباتی هوشمند</p>
    </footer>

</body>
</html>
