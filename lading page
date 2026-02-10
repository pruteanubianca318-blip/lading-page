<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fitness & Nutriție Acasă - Transformă-ți Corpul și Sănătatea Osoasă</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            line-height: 1.6;
            color: #333;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 100px 20px;
            text-align: center;
        }
        
        .hero h1 {
            font-size: 3em;
            margin-bottom: 25px;
            line-height: 1.2;
            font-weight: 800;
        }
        
        .hero .subtitle {
            font-size: 1.4em;
            margin-bottom: 20px;
            opacity: 0.95;
            font-weight: 400;
            line-height: 1.5;
        }
        
        .hero .description {
            font-size: 1.15em;
            margin-bottom: 40px;
            max-width: 900px;
            margin-left: auto;
            margin-right: auto;
            opacity: 0.9;
        }
        
        .cta-button {
            display: inline-block;
            background: #ff6b6b;
            color: white;
            padding: 20px 50px;
            font-size: 1.3em;
            font-weight: bold;
            text-decoration: none;
            border-radius: 50px;
            transition: all 0.3s;
            box-shadow: 0 8px 25px rgba(0,0,0,0.3);
            border: none;
            cursor: pointer;
        }
        
        .cta-button:hover {
            background: #ff5252;
            transform: translateY(-3px);
            box-shadow: 0 12px 35px rgba(0,0,0,0.4);
        }
        
        /* Pain Points Section */
        .pain-section {
            padding: 80px 20px;
            background: #f8f9fa;
        }
        
        .section-title {
            text-align: center;
            font-size: 2.5em;
            margin-bottom: 60px;
            color: #2c3e50;
            font-weight: 700;
        }
        
        .pain-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 30px;
            margin-bottom: 50px;
        }
        
        .pain-card {
            background: white;
            padding: 35px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.08);
            transition: transform 0.3s;
        }
        
        .pain-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.12);
        }
        
        .pain-card h3 {
            color: #e74c3c;
            margin-bottom: 20px;
            font-size: 1.5em;
            font-weight: 600;
        }
        
        .pain-card ul {
            list-style: none;
            padding-left: 0;
        }
        
        .pain-card li {
            padding: 10px 0;
            padding-left: 30px;
            position: relative;
            font-size: 1.05em;
            line-height: 1.5;
        }
        
        .pain-card li:before {
            content: "✗";
            position: absolute;
            left: 0;
            color: #e74c3c;
            font-weight: bold;
            font-size: 1.2em;
        }
        
        .pain-conclusion {
            text-align: center;
            margin-top: 50px;
        }
        
        .pain-conclusion p {
            font-size: 1.25em;
            color: #555;
            max-width: 850px;
            margin: 0 auto 35px;
            line-height: 1.6;
        }
        
        .pain-conclusion strong {
            color: #e74c3c;
            font-weight: 700;
        }
        
        /* Dream State Section */
        .dream-section {
            padding: 80px 20px;
            background: linear-gradient(135deg, #84fab0 0%, #8fd3f4 100%);
        }
        
        .dream-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 30px;
            margin-bottom: 50px;
        }
        
        .dream-card {
            background: white;
            padding: 35px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }
        
        .dream-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.15);
        }
        
        .dream-card h3 {
            color: #27ae60;
            margin-bottom: 20px;
            font-size: 1.5em;
            font-weight: 600;
        }
        
        .dream-card ul {
            list-style: none;
            padding-left: 0;
        }
        
        .dream-card li {
            padding: 10px 0;
            padding-left: 30px;
            position: relative;
            font-size: 1.05em;
            line-height: 1.5;
        }
        
        .dream-card li:before {
            content: "✓";
            position: absolute;
            left: 0;
            color: #27ae60;
            font-weight: bold;
            font-size: 1.3em;
        }
        
        .dream-conclusion {
            text-align: center;
            margin-top: 50px;
        }
        
        .dream-conclusion p {
            font-size: 1.25em;
            color: #2c3e50;
            max-width: 850px;
            margin: 0 auto 35px;
            line-height: 1.6;
            font-weight: 500;
        }
        
        /* Transformations Section */
        .transformations {
            padding: 80px 20px;
            background: white;
        }
        
        .transformations .subtitle {
            text-align: center;
            font-size: 1.3em;
            color: #666;
            margin-bottom: 60px;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
        }
        
        .placeholder-box {
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            border: 3px dashed #667eea;
            padding: 80px 40px;
            text-align: center;
            border-radius: 15px;
            margin-bottom: 40px;
        }
        
        .placeholder-box h3 {
            color: #667eea;
            font-size: 1.8em;
            margin-bottom: 15px;
            font-weight: 600;
        }
        
        .placeholder-box p {
            color: #555;
            font-size: 1.1em;
            font-style: italic;
        }
        
        /* Testimonials Section */
        .testimonials {
            padding: 80px 20px;
            background: #f8f9fa;
        }
        
        .testimonial-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 35px;
            margin-bottom: 50px;
        }
        
        .testimonial-card {
            background: white;
            padding: 40px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.08);
            position: relative;
        }
        
        .testimonial-card:before {
            content: '"';
            font-size: 5em;
            color: #667eea;
            opacity: 0.2;
            position: absolute;
            top: 10px;
            left: 20px;
            font-family: Georgia, serif;
        }
        
        .testimonial-content {
            position: relative;
            z-index: 1;
        }
        
        .testimonial-text {
            font-size: 1.1em;
            line-height: 1.7;
            color: #444;
            margin-bottom: 20px;
            font-style: italic;
        }
        
        .testimonial-author {
            font-weight: 600;
            color: #667eea;
            font-size: 1.1em;
        }
        
        .testimonial-details {
            color: #666;
            font-size: 0.95em;
        }
        
        /* Mentor Section */
        .mentor-section {
            padding: 80px 20px;
            background: white;
        }
        
        .mentor-content {
            display: grid;
            grid-template-columns: 1fr 2fr;
            gap: 50px;
            align-items: start;
            margin-top: 40px;
        }
        
        .mentor-story {
            font-size: 1.1em;
            line-height: 1.8;
            color: #444;
        }
        
        .mentor-story p {
            margin-bottom: 20px;
        }
        
        .mentor-credentials {
            background: #f8f9fa;
            padding: 30px;
            border-radius: 12px;
            margin-top: 30px;
        }
        
        .mentor-credentials h3 {
            color: #667eea;
            margin-bottom: 15px;
            font-size: 1.4em;
        }
        
        .mentor-credentials ul {
            list-style: none;
            padding-left: 0;
        }
        
        .mentor-credentials li {
            padding: 8px 0;
            padding-left: 25px;
            position: relative;
        }
        
        .mentor-credentials li:before {
            content: "→";
            position: absolute;
            left: 0;
            color: #667eea;
            font-weight: bold;
        }
        
        /* Solution Section */
        .solution-section {
            padding: 80px 20px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
        }
        
        .solution-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
            margin-bottom: 50px;
        }
        
        .solution-card {
            background: rgba(255,255,255,0.15);
            padding: 35px;
            border-radius: 12px;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255,255,255,0.3);
            transition: all 0.3s;
        }
        
        .solution-card:hover {
            background: rgba(255,255,255,0.25);
            transform: translateY(-5px);
        }
        
        .solution-card h3 {
            margin-bottom: 15px;
            font-size: 1.5em;
            font-weight: 600;
        }
        
        .solution-card p {
            font-size: 1.05em;
            line-height: 1.6;
            opacity: 0.95;
        }
        
        /* Comparison Section */
        .comparison-section {
            padding: 80px 20px;
            background: white;
        }
        
        .comparison-table {
            max-width: 1000px;
            margin: 0 auto;
            background: white;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 5px 30px rgba(0,0,0,0.1);
        }
        
        .comparison-row {
            display: grid;
            grid-template-columns: 2fr 1fr 1fr;
            border-bottom: 1px solid #eee;
        }
        
        .comparison-row:last-child {
            border-bottom: none;
        }
        
        .comparison-row.header {
            background: #667eea;
            color: white;
            font-weight: 700;
            font-size: 1.2em;
        }
        
        .comparison-cell {
            padding: 25px;
            text-align: center;
        }
        
        .comparison-cell:first-child {
            text-align: left;
            font-weight: 500;
        }
        
        .check {
            color: #27ae60;
            font-size: 2em;
            font-weight: bold;
        }
        
        .cross {
            color: #e74c3c;
            font-size: 2em;
            font-weight: bold;
        }
        
        /* FAQ Section */
        .faq-section {
            padding: 80px 20px;
            background: #f8f9fa;
        }
        
        .faq-container {
            max-width: 900px;
            margin: 0 auto;
        }
        
        .faq-item {
            background: white;
            margin-bottom: 20px;
            border-radius: 12px;
            padding: 30px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.08);
        }
        
        .faq-item h3 {
            color: #667eea;
            margin-bottom: 15px;
            font-size: 1.3em;
            font-weight: 600;
        }
        
        .faq-item p {
            color: #555;
            line-height: 1.7;
            font-size: 1.05em;
        }
        
        /* Final CTA */
        .final-cta {
            padding: 100px 20px;
            background: linear-gradient(135deg, #ff6b6b 0%, #ee5a6f 100%);
            color: white;
            text-align: center;
        }
        
        .final-cta h2 {
            font-size: 3em;
            margin-bottom: 25px;
            font-weight: 800;
        }
        
        .final-cta p {
            font-size: 1.3em;
            margin-bottom: 40px;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
            line-height: 1.6;
        }
        
        .final-cta .cta-button {
            background: white;
            color: #ff6b6b;
            font-size: 1.4em;
        }
        
        .final-cta .cta-button:hover {
            background: #f8f9fa;
            color: #ff5252;
        }
        
        /* Responsive */
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2em;
            }
            
            .hero .subtitle {
                font-size: 1.1em;
            }
            
            .section-title {
                font-size: 2em;
            }
            
            .mentor-content {
                grid-template-columns: 1fr;
            }
            
            .comparison-row {
                grid-template-columns: 2fr 1fr 1fr;
                font-size: 0.9em;
            }
            
            .comparison-cell {
                padding: 15px 10px;
            }
            
            .pain-grid, .dream-grid, .solution-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <h1>Transformă-ți Corpul și Protejează-ți Oasele<br>Fără Să Renunți la Viața Ta Ocupată</h1>
            <p class="subtitle">Program complet de fitness și nutriție pentru adulți 30-55 ani care vor să slăbească sustenabil, să construiască mușchi și să prevină osteoporoza - totul acasă, în 20-30 minute</p>
            <p class="description">Descoperă cum poți arăta și te poți simți cu 10 ani mai tânăr, având energie abundentă și oase puternice - fără ore petrecute la sală sau diete extreme imposibile.</p>
            <a href="#inscriere" class="cta-button">Vreau Să Încep Transformarea</a>
        </div>
    </section>

    <!-- Pain Points Section -->
    <section class="pain-section">
        <div class="container">
            <h2 class="section-title">Te Recunoști În Aceste Frustrări?</h2>
            <div class="pain-grid">
                <div class="pain-card">
                    <h3>😰 Teama de Osteoporoză</h3>
                    <ul>
                        <li>Frică de fracturi și imobilitate prematură</li>
                        <li>Densitatea osoasă scade fără să știi</li>
                        <li>Risc de mortalitate 20-75% după fractură de șold</li>
                        <li>Nu știi cum să previi această boală tăcută</li>
                    </ul>
                </div>
                
                <div class="pain-card">
                    <h3>⏰ Zero Timp Pentru Tine</h3>
                    <ul>
                        <li>Program haotic între serviciu și familie</li>
                        <li>Nu apuci să ajungi la sală</li>
                        <li>Copiii, munca, responsabilitățile te copleșesc</li>
                        <li>30 minute par imposibil de găsit</li>
                    </ul>
                </div>
                
                <div class="pain-card">
                    <h3>😞 Grăsime Persistentă</h3>
                    <ul>
                        <li>Burta/grăsimea de pe coapse nu dispare</li>
                        <li>Celulită vizibilă și aspect neatractiv</li>
                        <li>Haine care nu mai vin bine</li>
                        <li>Te simți jalnic când te uiți în oglindă</li>
                    </ul>
                </div>
                
                <div class="pain-card">
                    <h3>🔄 Efectul Yo-Yo</h3>
                    <ul>
                        <li>Slăbești 5-10 kg, apoi le iei înapoi</li>
                        <li>Diete extreme care nu durează</li>
                        <li>Metabolismul pare "stricat"</li>
                        <li>Simți că ai eșuat de prea multe ori</li>
                    </ul>
                </div>
                
                <div class="pain-card">
                    <h3>💪 Lipsă de Energie & Tonus</h3>
                    <ul>
                        <li>Oboseală cronică după program</li>
                        <li>Nu mai ții pasul cu copiii</li>
                        <li>Mușchi slabi, aspect "moale"</li>
                        <li>Te simți îmbătrânit prematur</li>
                    </ul>
                </div>
                
                <div class="pain-card">
                    <h3>😕 Confuzie Totală</h3>
                    <ul>
                        <li>Informații contradictorii peste tot</li>
                        <li>Nu știi ce antrenamente funcționează</li>
                        <li>Nu știi ce să mănânci pentru rezultate</li>
                        <li>YouTube-ul te copleșește cu opțiuni</li>
                    </ul>
                </div>
            </div>
            
            <div class="pain-conclusion">
                <p><strong>Și cel mai dureros?</strong> Simți că ai ratat trenul, că e prea târziu pentru tine, că metabolismul tău e "stricat" și că orice ai încerca e sortit eșecului... dar asta nu e adevărat.</p>
                <a href="#solutie" class="cta-button">Vreau Soluția</a>
            </div>
        </div>
    </section>

    <!-- Dream State Section -->
    <section class="dream-section">
        <div class="container">
            <h2 class="section-title">Imaginează-ți Cum Ar Fi Să...</h2>
            <div class="dream-grid">
                <div class="dream-card">
                    <h3>🎯 Corp Tonifiat & Definit</h3>
                    <ul>
                        <li>Fără grăsime abdominală sau celulită vizibilă</li>
                        <li>Mușchi fermi, aspect athletic și atractiv</li>
                        <li>Mândrie când te privești în oglindă</li>
                        <li>Hainele tale preferate îți vin perfect</li>
                    </ul>
                </div>
                
                <div class="dream-card">
                    <h3>🦴 Oase Puternice ca Oțelul</h3>
                    <ul>
                        <li>Densitate osoasă crescută, certificată medical</li>
                        <li>Zero frică de fracturi sau osteoporoză</li>
                        <li>Certitudinea că vei fi activ la 70-80 ani</li>
                        <li>Independență și mobilitate pe termen lung</li>
                    </ul>
                </div>
                
                <div class="dream-card">
                    <h3>⚡ Energie ca la 30 de Ani</h3>
                    <ul>
                        <li>Te trezești plin de vitalitate în fiecare dimineață</li>
                        <li>Ții pasul cu copiii fără oboseală</li>
                        <li>Productivitate maximă la serviciu</li>
                        <li>Metabolism rapid și eficient</li>
                    </ul>
                </div>
                
                <div class="dream-card">
                    <h3>🏡 Libertate Totală</h3>
                    <ul>
                        <li>Antrenezi acasă, 20-30 minute, când vrei tu</li>
                        <li>Fără dependență de săli scumpe</li>
                        <li>Fără stres legat de mese - știi exact ce să mănânci</li>
                        <li>Program simplu, sustenabil, adaptat vieții tale</li>
                    </ul>
                </div>
                
                <div class="dream-card">
                    <h3>😊 Încredere și Respect</h3>
                    <ul>
                        <li>Partenerii îți admiră transformarea</li>
                        <li>Copiii te văd ca model de sănătate</li>
                        <li>Colegii te întreabă "cum ai făcut?"</li>
                        <li>Tu însuți te simți mândru de realizare</li>
                    </ul>
                </div>
                
                <div class="dream-card">
                    <h3>🎉 Viață Fără Limite</h3>
                    <ul>
                        <li>Participi activ la toate evenimentele</li>
                        <li>Nu mai eviti plaja sau piscina</li>
                        <li>Te simți sexy și atractiv la orice vârstă</li>
                        <li>Viață socială îmbunătățită, energie pozitivă</li>
                    </ul>
                </div>
            </div>
            
            <div class="dream-conclusion">
                <p>Asta nu e un vis imposibil. E realitatea pentru sute de români care au ales să facă un singur lucru diferit...</p>
                <a href="#transformari" class="cta-button">Vreau Această Transformare</a>
            </div>
        </div>
    </section>

    <!-- Transformations Section -->
    <section class="transformations" id="transformari">
        <div class="container">
            <h2 class="section-title">Transformări Reale Ale Românilor Ca Tine</h2>
            <p class="subtitle">Adulți 30-55 ani care au reușit să slăbească sustenabil, să construiască mușchi și să prevină osteoporoza - totul acasă, fără să renunțe la viața lor ocupată</p>
            
            <div class="placeholder-box">
                <h3>📸 AICI VIN POZELE BEFORE/AFTER</h3>
                <p>Transformări vizuale ale clienților reali - înainte și după (minim 3-6 transformări)</p>
                <p>Include: nume, vârstă, perioada transformării, kg pierdute/mușchi câștigați</p>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="testimonials">
        <div class="container">
            <h2 class="section-title">Ce Spun Clienții Noștri</h2>
            
            <div class="placeholder-box">
                <h3>💬 AICI VIN RECENZIILE ȘI TESTIMONIALELE REALE</h3>
                <p>Recenzii și testimoniale video sau text de la clienți reali</p>
                <p>Include: experiența lor, rezultate specifice, schimbări în viață</p>
            </div>
            
            <div class="testimonial-grid" style="margin-top: 40px;">
                <div class="testimonial-card">
                    <div class="testimonial-content">
                        <p class="testimonial-text">[PLACEHOLDER pentru testimonial text complet - experiența clientului, rezultate, sentimente]</p>
                        <p class="testimonial-author">[Nume Client]</p>
                        <p class="testimonial-details">[Vârstă] ani, [Oraș]</p>
                    </div>
                </div>
                
                <div class="testimonial-card">
                    <div class="testimonial-content">
                        <p class="testimonial-text">[PLACEHOLDER pentru testimonial text complet - experiența clientului, rezultate, sentimente]</p>
                        <p class="testimonial-author">[Nume Client]</p>
                        <p class="testimonial-details">[Vârstă] ani, [Oraș]</p>
                    </div>
                </div>
                
                <div class="testimonial-card">
                    <div class="testimonial-content">
                        <p class="testimonial-text">[PLACEHOLDER pentru testimonial text complet - experiența clientului, rezultate, sentimente]</p>
                        <p class="testimonial-author">[Nume Client]</p>
                        <p class="testimonial-details">[Vârstă] ani, [Oraș]</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Mentor Section -->
    <section class="mentor-section">
        <div class="container">
            <h2 class="section-title">Cine Te Va Ghida În Această Transformare?</h2>
            
            <div class="mentor-content">
                <div class="placeholder-box">
                    <h3>📷 AICI VINE POZA LUI CLAUDIU</h3>
                    <p>Poză profesională a mentorului principal</p>
                </div>
                
                <div class="mentor-story">
                    <div class="placeholder-box">
                        <h3>📝 AICI VINE POVESTEA LUI CLAUDIU</h3>
                        <p>Include:</p>
                        <p>- Cine este și experiența lui în fitness/culturism natural</p>
                        <p>- Transformarea personală și rezultatele sale</p>
                        <p>- De ce a creat acest program</p>
                        <p>- Pasiunea pentru prevenția osteoporozei și fitness post-40</p>
                        <p>- Realizări și competiții (campion culturism natural, etc.)</p>
                    </div>
                    
                    <div class="mentor-credentials">
                        <h3>Calificări și Expertiză</h3>
                        <div class="placeholder-box" style="margin-top: 15px;">
                            <p>AICI VIN CERTIFICĂRILE, EXPERIENȚA, COMPETIȚIILE CÂȘTIGATE</p>
                            <p>Lista cu bullet points a realizărilor profesionale</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Solution Section -->
    <section class="solution-section" id="solutie">
        <div class="container">
            <h2 class="section-title">Cum Funcționează Programul Nostru?</h2>
            
            <div class="solution-grid">
                <div class="solution-card">
                    <h3>🏋️ Antrenamente Structurate</h3>
                    <p>20-30 minute, 3-4 ori pe săptămână, acasă. Programe specifice pentru densitate osoasă, construire m
