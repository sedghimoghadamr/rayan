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
