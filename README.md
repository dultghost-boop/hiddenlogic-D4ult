<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HiddenLogic | Portfolio</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #0d1117;
            color: #c9d1d9;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        header {
            background-color: #161b22;
            padding: 40px 20px;
            text-align: center;
            border-bottom: 2px solid #21262d;
        }

        header h1 {
            color: #58a6ff;
            margin: 0;
            font-size: 2.5rem;
            letter-spacing: 1px;
        }

        header p {
            color: #8b949e;
            font-size: 1.1rem;
            margin-top: 10px;
        }

        .container {
            max-width: 900px;
            margin: 40px auto;
            padding: 0 20px;
        }

        section {
            background-color: #161b22;
            padding: 25px;
            margin-bottom: 25px;
            border-radius: 8px;
            border: 1px solid #21262d;
        }

        section h2 {
            color: #58a6ff;
            margin-top: 0;
            border-bottom: 1px solid #30363d;
            padding-bottom: 10px;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .gallery-item {
            background-color: #0d1117;
            border-radius: 6px;
            overflow: hidden;
            border: 1px solid #30363d;
            text-align: center;
        }

        .gallery-item img {
            width: 100%;
            height: 220px;
            object-fit: cover;
            display: block;
        }

        .gallery-item p {
            padding: 12px;
            margin: 0;
            font-size: 0.9rem;
            color: #8b949e;
        }

        .links-container {
            display: flex;
            flex-direction: column;
            gap: 15px;
            margin-top: 20px;
        }

        .btn-link {
            display: block;
            text-align: center;
            background-color: #21262d;
            color: #c9d1d9;
            padding: 12px;
            text-decoration: none;
            border-radius: 6px;
            border: 1px solid #30363d;
            font-weight: bold;
            transition: 0.3s;
        }

        .btn-link:hover {
            background-color: #30363d;
            color: #58a6ff;
        }

        footer {
            text-align: center;
            padding: 20px;
            color: #8b949e;
            font-size: 0.85rem;
            margin-top: 40px;
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
                    <p>المشروع أو الصورة السادسة</p>
                </div>

            </div>
        </section>

        <section id="contact">
            <h2>تواصل معي</h2>
            <div class="links-container">
                <a href="https://github.com/dultghost-boop" class="btn-link" target="_blank">حساب GitHub</a>
                
                <a href="#" class="btn-link" target="_blank">حساب Discord</a>
            </div>
        </section>

    </div>

    <footer>
        <p>© 2026 HiddenLogic. جميع الحقوق محفوظة.</p>
    </footer>

</body>
</html>
