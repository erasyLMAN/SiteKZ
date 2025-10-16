<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Қазақ Хандығы: Толық шолу (Бір беттік нұсқа)</title>
    <style>
        /* 1. Негізгі стильдер (Material Surface) */
        body {
            background-color: #ECEFF1; /* Ашық сұр фон */
            font-family: 'Roboto', 'Helvetica Neue', Arial, sans-serif;
            color: #263238; /* Қою сұр мәтін */
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 24px 16px;
        }

        /* 2. Жоғарғы Панель (AppBar) */
        .app-bar {
            background-color: #2C3E50; /* Қою көк (Primary Color) */
            color: white;
            padding: 20px 24px;
            margin: 0 -16px 24px -16px; /* Контейнердің бүйірлік жиектерін жабу үшін */
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }

        /* 3. Типографика */
        h1 {
            font-size: 36px;
            font-weight: 500;
            margin: 0;
        }

        h2 {
            color: #F1C40F; /* Алтын (Secondary Color) */
            font-size: 28px;
            font-weight: 500;
            margin-top: 40px;
            padding-bottom: 10px;
            border-bottom: 2px solid #CFD8DC;
        }

        h3 {
            color: #2C3E50;
            font-size: 20px;
            font-weight: 500;
            margin-top: 25px;
            margin-bottom: 10px;
        }

        /* 4. Жалпы ақпарат карточкасы */
        .general-card {
            background-color: #FFFFFF;
            padding: 24px;
            border-radius: 8px;
            margin-bottom: 30px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        /* 5. Хан туралы карточка (Higher Elevation) */
        .khan-card {
            background-color: #FFFFFF;
            padding: 0;
            border-radius: 8px;
            margin-bottom: 24px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.15); /* Көтеріңкі көлеңке */
            transition: box-shadow 0.3s, transform 0.3s;
            overflow: hidden;
        }

        .khan-card:hover {
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
            transform: translateY(-2px);
        }

        .khan-header {
            background-color: #34495E; /* Сәл ашықтау көк */
            color: white;
            padding: 16px 24px;
        }

        .khan-header h3 {
            margin: 0;
            font-size: 22px;
            font-weight: 500;
            color: white;
        }

        .khan-body {
            padding: 24px;
        }

        .khan-body p strong {
            color: #263238;
        }

        .khan-body span.period {
            display: block;
            color: #F1C40F;
            font-weight: 500;
            margin-bottom: 8px;
        }

        /* 6. Тізім стилі */
        ul {
            list-style: none;
            padding: 0;
            margin-top: 15px;
        }
        ul li {
            padding: 10px 0;
            border-bottom: 1px dashed #CFD8DC;
        }
        ul li:last-child {
            border-bottom: none;
        }

        /* 7. Footer */
        .footer {
            margin-top: 50px;
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid #CFD8DC;
            color: #78909C;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <div class="app-bar">
        <h1>Қазақ Хандығына шолу 🇰🇿</h1>
    </div>

    <div class="container">

        <div class="general-card">
            <h2>Хандыққа кіріспе</h2>
            <p><strong>Қазақ хандығы</strong> — XV ғасырдың ортасында (шамамен 1465 ж.) Жошы ұрпақтары **Керей** мен **Жәнібек** сұлтандардың бастамасымен құрылған ортағасырлық мемлекет. Хандықтың құрылуы Әбілқайыр ханның (Өзбек ұлысы) қатал билігінен наразы болған халықтың **Шу мен Қозы-Басы** аймағына көшуінен басталды. Бұл тарихи қадам қазақ мемлекеттілігінің негізін қалады.</p>

            <h3>Басқару құрылымы</h3>
            <ul>
                <li><strong>Хан:</strong> Жоғары билеуші, тек **Төре** әулетінен сайланды.</li>
                <li><strong>Сұлтандар:</strong> Әкімшілік және әскери міндеттерді атқарды.</li>
                <li><strong>Билер мен Батырлар:</strong> Билер сот істерін жүргізді, Батырлар әскерді басқарды.</li>
            </ul>

            <h3>Ең маңызды кезеңдер</h3>
            <ul>
                <li>**Гүлдену кезеңі:** **Қасым ханның** билігі (XVI ғ.) және **"Қасқа жолы"** заңдары.</li>
                <li>**Дағдарыс және қайта өрлеу:** **Тәуке ханның** кезіндегі **"Жеті Жарғы"** және **Абылай ханның** Жоңғарға қарсы күресі.</li>
            </ul>
        </div>

        <h2>Қазақ хандарының хронологиясы</h2>

        <div class="khan-card">
            <div class="khan-header"><h3>Керей хан (Құрылтайшы)</h3></div>
            <div class="khan-body">
                <span class="period">Билік кезеңі: Шамамен 1465 ж. – 1473 ж. шамасы.</span>
                <p><strong>Рөлі:</strong> Қазақ хандығының **алғашқы ханы**. Жәнібекпен бірге көшпелі руларды біріктіріп, жаңа мемлекеттің территориялық және саяси негізін қалады. Оның есімі мемлекеттің құрылған күнімен тікелей байланысты.</p>
            </div>
        </div>

        <div class="khan-card">
            <div class="khan-header"><h3>Жәнібек хан (Біріктіруші)</h3></div>
            <div class="khan-body">
                <span class="period">Билік кезеңі: Шамамен 1473 ж. – 1480 ж. шамасы.</span>
                <p><strong>Рөлі:</strong> Керейдің серігі. Кейінгі барлық ірі хандардың (Қасым, Хақназар) әкесі немесе атасы болғандықтан, **хан әулетінің негізін қалаушы** болып саналады. Хандықтың алғашқы жылдарында мемлекетті нығайтуға үлес қосты.</p>
            </div>
        </div>

        <div class="khan-card">
            <div class="khan-header"><h3>Қасым хан (Ұлы империяның құрушысы)</h3></div>
            <div class="khan-body">
                <span class="period">Билік кезеңі: Шамамен 1511 ж. – 1521 ж.</span>
                <p><strong>Рөлі:</strong> Хандықты **тарихтағы ең үлкен аумағына** жеткізді. Оның басты мұрасы — **«Қасым ханның қасқа жолы»** атты дәстүрлі заңдар жиынтығын жүйелеуі. Бұл заңдар қазақ қоғамын реттеуде ұзақ уақыт бойы қолданылды.</p>
            </div>
        </div>

        <div class="khan-card">
            <div class="khan-header"><h3>Тәуке хан (Заң шығарушы)</h3></div>
            <div class="khan-body">
                <span class="period">Билік кезеңі: Шамамен 1680 ж. – 1718 ж.</span>
                <p><strong>Рөлі:</strong> Қазақ хандығының соңғы **бірлігін** сақтаған. Ол ішкі қайшылықтарды азайту үшін **«Жеті Жарғы»** заңдар жиынтығын қабылдады, осылайша Билер Кеңесінің ықпалын күшейтті және Жоңғар шабуылы қарсаңында халықты біріктірді.</p>
            </div>
        </div>

        <div class="khan-card">
            <div class="khan-header"><h3>Абылай хан (Тәуелсіздік үшін күрескер)</h3></div>
            <div class="khan-body">
                <span class="period">Билік кезеңі: 1771 ж. – 1781 ж. (Іс жүзінде 1740 жылдардан бастап биледі).</span>
                <p><strong>Рөлі:</strong> XVIII ғасырдағы ұлы билеуші. **Үш жүзді** біріктіріп, **Жоңғарларға** қарсы күресті басқарды. Оның әскери және **көпвекторлы дипломатиясы** Қазақ хандығының **тәуелсіздігін** сақтауда шешуші рөл атқарды.</p>
            </div>
        </div>

        <div class="footer">
            © 2025. Material Design нұсқасы. Ақпарат көзі: Тарихи деректер.
        </div>
    </div>
</body>
</html>
