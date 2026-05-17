<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HiddenLogic | Portfolio</title>
    <style>
        /* تصميم كلاسيكي أسود وأبيض بالكامل */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #000000; /* أسود خالص */
            color: #ffffff; /* أبيض خالص */
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        header {
            background-color: #000000;
            padding: 50px 20px;
            text-align: center;
            border-bottom: 1px solid #ffffff; /* خط أبيض فاصل */
        }

        header h1 {
            color: #ffffff;
            margin: 0;
            font-size: 2.5rem;
            letter-spacing: 2px;
            font-weight: 800;
        }

        header p {
            color: #aaaaaa; /* رمادي فاتح للنصوص الفرعية */
            font-size: 1.1rem;
            margin-top: 10px;
        }

        .container {
            max-width: 900px;
            margin: 40px auto;
            padding: 0 20px;
        }

        section {
            background-color: #000000;
            padding: 30px 0;
            margin-bottom: 40px;
            border-bottom: 1px dashed #333333; /* خط منقط فاصل بين الأقسام */
        }

        section h2 {
            color: #ffffff;
            margin-top: 0;
            font-size: 1.8rem;
            letter-spacing: 1px;
            padding-bottom: 10px;
        }

        /* معرض الصور المتناسق */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
            margin-top: 20px;
        }

        .gallery-item {
            background-color: #000000;
            overflow: hidden;
            border: 1px solid #ffffff; /* إطار أبيض حول الصورة */
            text-align: center;
        }

        .gallery-item img {
            width: 100%;
            height: 240px;
            object-fit: cover;
            display: block;
            filter: grayscale(100%); /* تحويل الصور تلقائياً إلى أسود وأبيض لتناسب التصميم */
        }

        .gallery-item p {
            padding: 15px;
            margin: 0;
            font-size: 0.95rem;
            color: #ffffff;
            border-top: 1px solid #ffffff;
        }

        /* تنسيق أزرار التواصل */
        .links-container {
            display: flex;
            flex-direction: column;
            gap: 15px;
            margin-top: 25px;
        }

        .btn-link {
            display: block;
            text-align: center;
            background-color: #ffffff; /* زر أبيض بخلفية بيضاء */
            color: #000000; /* نص أسود */
            padding: 14px;
            text-decoration: none;
            font-weight: bold;
            border: 1px solid #ffffff;
            transition: all 0.3s ease;
        }

        /* تأثير عند تمرير الفأرة أو الضغط */
        .btn-link:hover {
            background-color: #000000;
            color: #ffffff;
        }

        footer {
            text-align: center;
            padding: 40px 20px;
            color: #666666;
            font-size: 0.85rem;
            border-top: 1px solid #222222;
        }
    </style>
</head>
<body>

    <header>
        <h1>HiddenLogic</h1>
        <p>المساحة الرقمية الخاصة بي وتطوير الأفكار</p>
    </header>

    <div class="container">

        <section id="about">
            <h2>نبذة عني</h2>
            <p>مرحباً بك في موقعي الشخصي. أنا مهتم بمجالات البرمجة، تطوير الأنظمة، والأمن السيبراني. أؤمن بالتعلم الذاتي والتطبيق العملي المستمر لبناء أدوات وحلول ذكية.</p>
        </section>

        <section id="projects">
            <h2>معرض الصور والمشاريع</h2>
            <div class="gallery">
                
                <div class="gallery-item">
                    <img src="7E465A66-C40D-468C-926C-921AA046BE8B.png" alt="Image 1">
                    <p>المشروع أو الصورة الأولى</p>
                </div>

                <div class="gallery-item">
                    <img src="B6BE3752-6DAE-4FFC-A560-A5FE751EBC77.png" alt="Image 2">
                    <p>المشروع أو الصورة الثانية</p>
                </div>

                <div class="gallery-item">
                    <img src="73BEC5A5-234A-456C-BE6F-4A42A5826554.png" alt="Image 3">
                    <p>المشروع أو الصورة الثالثة</p>
                </div>

                <div class="gallery-item">
                    <img src="6D1AF646-9C26-4884-9260-BE0BFE8F092A.png" alt="Image 4">
                    <p>المشروع أو الصورة الرابعة</p>
                </div>

                <div class="gallery-item">
                    <img src="2CB02463-5222-4FB2-8B9B-E4AF81CCB5BD.png" alt="Image 5">
                    <p>المشروع أو الصورة الخامسة</p>
                </div>

                <div class="gallery-item">
                    <img src="955840BE-359E-4601-A0E1-E23B19E50B20.png" alt="Image 6">
                    <p>المشروع أو
