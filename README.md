<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Қазақ Хандығы: Толық шолу (Бір беттік нұсқа)</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
    <style>
        /* ========================================================== */
        /* 1. НЕГІЗГІ ЖӘНЕ MATERIAL 3 СТИЛЬДЕРІ */
        /* ========================================================== */
        :root {
            /* Material 3 Colors */
            --primary: #597d51; /* Орман жасылы */
            --on-primary: #ffffff;
            --primary-container: #daefd0;
            --secondary: #c2951b; /* Ежелгі алтын */
            --on-secondary: #ffffff;
            --surface: #fcfcf7; /* Ашық фон */
            --on-surface: #1a1c18;
            --background: #fdfdf5;
            --outline: #74796e;
            --elevation-1: 0 1px 3px rgba(0, 0, 0, 0.1);
            --elevation-2: 0 2px 6px rgba(0, 0, 0, 0.15);
            --elevation-3: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        body {
            background-color: var(--background);
            font-family: 'Roboto', Arial, sans-serif;
            color: var(--on-surface);
            line-height: 1.7;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 24px 16px;
        }

        /* ========================================================== */
        /* 2. ЖОҒАРҒЫ ПАНЕЛЬ (APP BAR) */
        /* ========================================================== */
        .app-bar {
            background-color: var(--primary);
            color: var(--on-primary);
            padding: 24px 16px;
            box-shadow: var(--elevation-3);
            display: flex;
            align-items: center;
        }

        .app-bar h1 {
            font-size: 28px;
            font-weight: 500;
            margin: 0;
            flex-grow: 1;
        }
        .app-bar .material-icons {
            font-size: 32px;
            margin-right: 12px;
        }

        /* ========================================================== */
        /* 3. ТИПОГРАФИКА */
        /* ========================================================== */
        h2 {
            color: var(--secondary);
            font-size: 26px;
            font-weight: 700;
            margin-top: 40px;
            margin-bottom: 20px;
            padding-bottom: 8px;
            border-bottom: 3px solid var(--primary-container);
            display: flex;
            align-items: center;
        }
        h2 .material-icons {
            font-size: 30px;
            margin-right: 8px;
            color: var(--primary);
        }

        h3 {
            color: var(--primary);
            font-size: 20px;
            font-weight: 500;
            margin-top: 25px;
            margin-bottom: 10px;
        }

        strong {
            font-weight: 600;
            color: var(--on-surface);
        }

        /* ========================================================== */
        /* 4. КАРТОЧКАЛАР (CARDS) */
        /* ========================================================== */
        .card {
            background-color: var(--surface);
            padding: 24px;
            border-radius: 12px;
            margin-bottom: 30px;
            box-shadow: var(--elevation-1);
            border: 1px solid var(--primary-container);
        }

        /* 5. ХАН КАРТОЧКАСЫНЫҢ СТИЛІ */
        .khan-card {
            padding: 0;
            transition: box-shadow 0.3s, transform 0.3s;
            overflow: hidden;
        }

        .khan-card:hover {
            box-shadow: var(--elevation-3);
            transform: translateY(-3px);
        }

        .khan-header {
            background-color: var(--primary);
            color: var(--on-primary);
            padding: 16px 24px;
            display: flex;
            align-items: center;
        }

        .khan-header h3 {
            margin: 0;
            font-size: 22px;
            font-weight: 500;
            color: var(--on-primary);
            flex-grow: 1;
        }
        .khan-header .material-icons {
            font-size: 24px;
            margin-right: 10px;
        }

        .khan-body {
            padding: 20px 24px;
        }

        .khan-body span.period {
            display: block;
            color: var(--secondary);
            font-weight: 500;
            margin-bottom: 10px;
            font-style: italic;
            padding-left: 20px;
            border-left: 3px solid var(--secondary);
        }

        /* 6. ТІЗІМ ЖӘНЕ АҚПАРАТ БЛОГЫ */
        .info-block {
            padding: 15px;
            background-color: var(--primary-container);
            border-radius: 8px;
            margin-top: 15px;
        }
        .info-block h4 {
            color: var(--primary);
            margin-top: 0;
            margin-bottom: 10px;
            font-size: 18px;
            font-weight: 600;
        }

        ul.check-list {
            list-style: none;
            padding: 0;
            margin: 10px 0;
        }
        ul.check-list li {
            padding: 8px 0;
            border-bottom: 1px dashed var(--outline);
            display: flex;
            align-items: flex-start;
        }
        ul.check-list li:last-child {
            border-bottom: none;
        }
        ul.check-list .material-icons {
            color: var(--primary);
            font-size: 20px;
            margin-right: 10px;
            line-height: 1.7; /* Мәтінмен туралану үшін */
        }

        /* 7. FOOTER */
        .footer {
            margin-top: 50px;
            text-align: center;
            padding: 20px;
            border-top: 1px solid var(--outline);
            color: var(--outline);
            font-size: 14px;
        }

        /* ========================================================== */
        /* 8. МОБИЛЬДІ ҚҰРЫЛҒЫЛАРҒА БЕЙІМДЕУ (MEDIA QUERIES) */
        /* ========================================================== */

        @media (max-width: 600px) {
            .container {
                padding: 10px;
            }

            .app-bar h1 {
                font-size: 24px;
            }

            h2 {
                font-size: 22px;
                margin-top: 30px;
                padding-bottom: 5px;
            }

            .card {
                padding: 16px;
                border-radius: 8px;
                margin-bottom: 20px;
            }

            .khan-header h3 {
                font-size: 18px;
            }

            .khan-body {
                padding: 16px;
            }
        }
    </style>
</head>
<body>
    <div class="app-bar">
        <i class="material-icons">gavel</i>
        <h1>Қазақ Хандығына толық шолу 🇰🇿</h1>
    </div>

    <div class="container">

        <div class="card">
            <h2><i class="material-icons">history_toggle_off</i>Хандыққа кіріспе және Құрылуы</h2>
            <p><strong>Қазақ хандығы</strong> — XV ғасырдың ортасында (ресми түрде **1465 жылы**) Жошы ұрпақтары **Керей** мен **Жәнібек** сұлтандардың бастамасымен құрылған ұлы дала мемлекеті. Хандықтың құрылуы Әбілқайыр ханның (Өзбек ұлысы) қатал саясатына наразы болған ру-тайпалардың одан бөлініп, **Моғолстанның батысына (Шу мен Қозы-Басы аймағы)** көшуінен басталды. Бұл оқиға **"қазақ" (еркін, бостан)** атауының мемлекеттік мәртебе алуына негіз болды.</p>

            <div class="info-block">
                <h4>Құрылудың үш маңызды факторы</h4>
                <ul class="check-list">
                    <li><i class="material-icons">public</i> <strong>Әбілқайырдың өлімі:</strong> 1468 жылы оның қазасы Қазақ сұлтандарына еркіндік берді.</li>
                    <li><i class="material-icons">vpn_key</i> <strong>Моғолстанның қолдауы:</strong> Моғол ханы Есен-Бұғаның Керей мен Жәнібекке жер бөліп беруі.</li>
                    <li><i class="material-icons">groups</i> <strong>Этникалық консолидация:</strong> Көшпелі өзбектерден бөлінген 200 мыңдай адамның бірігуі.</li>
                </ul>
            </div>

            <h3>Басқару құрылымы</h3>
            <ul class="check-list">
                <li><i class="material-icons">star</i> <strong>Хан:</strong> Жошының ұрпағы **Төре** әулетінен сайланатын жоғары билеуші, әскери және саяси жетекші.</li>
                <li><i class="material-icons">shield</i> <strong>Сұлтандар:</strong> Облыстық әкімшілік және әскери міндеттерді атқарды, әдетте Жошы ұрпақтары.</li>
                <li><i class="material-icons">balance</i> <strong>Билер Кеңесі:</strong> Әр Жүзден шыққан беделді билер сот істерін жүргізді, "Жеті Жарғы" кезінде рөлі күшейді.</li>
                <li><i class="material-icons">local_fire_department</i> <strong>Батырлар:</strong> Әскери басшылар, рулардың соғысқа қабілеттілігін қамтамасыз етті.</li>
            </ul>
        </div>

        <h2><i class="material-icons">people_alt</i> Қазақ хандары және олардың мұрасы</h2>

        <div class="khan-card card">
            <div class="khan-header"><i class="material-icons">vpn_key</i><h3>Керей хан (Құрылтайшы)</h3></div>
            <div class="khan-body">
                <span class="period">Билік кезеңі: Шамамен 1465 ж. – 1473 ж. шамасы.</span>
                <p><strong>Еңбегі:</strong> Қазақ хандығының **тарихтағы алғашқы ханы**. Жәнібекпен бірге халықты бастап, мемлекеттің территориялық және саяси негізін қалады. Керей билігі кезінде алғашқы ұйымдасу істері жүргізілді.</p>
            </div>
        </div>

        <div class="khan-card card">
            <div class="khan-header"><i class="material-icons">hub</i><h3>Жәнібек хан (Біріктіруші)</h3></div>
            <div class="khan-body">
                <span class="period">Билік кезеңі: Шамамен 1473 ж. – 1480 ж. шамасы.</span>
                <p><strong>Еңбегі:</strong> **Хан әулетінің тікелей негізін қалаушы**. Оның ұрпақтары (Қасым, Хақназар, Тәуекел, Есім) кейіннен хандықтың дамуына үлкен үлес қосты. Мемлекеттің ішкі тұрақтылығын нығайтуға басты назар аударды.</p>
            </div>
        </div>

        <div class="khan-card card">
            <div class="khan-header"><i class="material-icons">map</i><h3>Қасым хан (Ұлы империяның құрушысы)</h3></div>
            <div class="khan-body">
                <span class="period">Билік кезеңі: Шамамен 1511 ж. – 1521 ж.</span>
                <p><strong>Еңбегі:</strong> Хандықты **тарихтағы ең үлкен аумағына** жеткізді (1 миллионға жуық халық). Оның басты мұрасы — **«Қасым ханның қасқа жолы»** (Көшпелілердің дәстүрлі заңдарының жиынтығын жүйелеуі). Бұл кезең хандықтың "Алтын ғасыры" деп саналады.</p>
            </div>
        </div>

        <div class="khan-card card">
            <div class="khan-header"><i class="material-icons">gavel</i><h3>Тәуке хан (Заң шығарушы)</h3></div>
            <div class="khan-body">
                <span class="period">Билік кезеңі: Шамамен 1680 ж. – 1718 ж.</span>
                <p><strong>Еңбегі:</strong> Қазақ хандығының соңғы **орталықтандырылған** кезеңі. Ол **«Жеті Жарғы»** атты жаңа заңдар жиынтығын қабылдап, руаралық дауларды реттеді, Билер Кеңесінің рөлін күшейтті. Бұл заңдар Жоңғар шапқыншылығы қарсаңында халықты біріктіруде маңызды болды.</p>
                <div class="info-block">
                    <h4>"Жеті Жарғының" негізгі қағидалары:</h4>
                    <ul class="check-list">
                        <li><i class="material-icons">handshake</i> Қылмыстық істер (Құн ережелері).</li>
                        <li><i class="material-icons">family_restroom</i> Неке және отбасы қатынастары.</li>
                        <li><i class="material-icons">military_tech</i> Әскери міндеттер және Жеті Жарғыны бұзғандарға жаза.</li>
                    </ul>
                </div>
            </div>
        </div>

        <div class="khan-card card">
            <div class="khan-header"><i class="material-icons">bolt</i><h3>Абылай хан (Тәуелсіздік үшін күрескер)</h3></div>
            <div class="khan-body">
                <span class="period">Билік кезеңі: 1771 ж. – 1781 ж. (Іс жүзінде 1740 жылдардан бастап биледі).</span>
                <p><strong>Еңбегі:</strong> XVIII ғасырдағы ұлы билеуші. Ұсақ хандықтар мен сұлтандарды бағындырып, **Үш жүзді** біріктірді. Ол **Жоңғарларға** (Қалмақтарға) қарсы **"Ақтабан шұбырынды, Алқакөл сұлама"** кезіндегі күресті басқарды. Ресей және Қытай арасындағы **көпвекторлы дипломатиясы** арқасында хандықтың тәуелсіздігін сақтап қалды.</p>
            </div>
        </div>

        <div class="footer">
            <i class="material-icons">copyright</i> 2025. Қазақ Тарихына шолу. Дизайн: Material Inspired. Ақпарат көзі: Тарихи деректер.
        </div>
    </div>
</body>
</html>
