<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fachinformatiker AE – GitHub Profil</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        
      body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
            background: #0d1117;
            color: #c9d1d9;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
            padding: 2rem 1.5rem;
        }

        /* Header */
        .header {
            text-align: center;
            margin-bottom: 2.5rem;
            padding-bottom: 2rem;
            border-bottom: 1px solid #30363d;
        }

        .header img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 3px solid #58a6ff;
            margin-bottom: 1rem;
        }

        .header h1 {
            font-size: 1.8rem;
            color: #fff;
            margin-bottom: 0.3rem;
        }

        .header p {
            color: #8b949e;
            font-size: 1.1rem;
        }

        .badges {
            margin-top: 1rem;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 0.5rem;
        }

        .badge {
            background: #161b22;
            border: 1px solid #30363d;
            padding: 0.3rem 0.8rem;
            border-radius: 20px;
            font-size: 0.85rem;
            color: #58a6ff;
        }

        /* Sections */
        section {
            margin-bottom: 2rem;
        }

        h2 {
            color: #58a6ff;
            font-size: 1.2rem;
            margin-bottom: 1rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        h2::before {
            content: '';
            display: inline-block;
            width: 4px;
            height: 20px;
            background: #58a6ff;
            border-radius: 2px;
        }

        /* Skills */
        .skill-tag {
            display: inline-block;
            background: #161b22;
            border: 1px solid #30363d;
            padding: 0.5rem 1rem;
            border-radius: 6px;
            margin: 0.3rem;
            font-size: 0.9rem;
            transition: all 0.2s;
        }

        .skill-tag:hover {
            border-color: #58a6ff;
            color: #fff;
        }

        .skill-tag .level {
            color: #8b949e;
            font-size: 0.75rem;
            margin-left: 0.3rem;
        }

        /* Timeline */
        .timeline {
            position: relative;
            padding-left: 1.5rem;
        }

        .timeline::before {
            content: '';
            position: absolute;
            left: 0;
            top: 0;
            bottom: 0;
            width: 2px;
            background: #30363d;
        }

        .timeline-item {
            position: relative;
            margin-bottom: 1.5rem;
        }

        .timeline-item::before {
            content: '';
            position: absolute;
            left: -1.6rem;
            top: 0.4rem;
            width: 10px;
            height: 10px;
            border-radius: 50%;
            background: #161b22;
            border: 2px solid #58a6ff;
        }

        .timeline-item.done::before {
            background: #238636;
            border-color: #238636;
        }

        .timeline-date {
            color: #8b949e;
            font-size: 0.85rem;
        }

        .timeline-title {
            color: #fff;
            font-weight: 600;
            margin: 0.2rem 0;
        }

        .timeline-desc {
            color: #8b949e;
            font-size: 0.9rem;
        }

        /* Projects */
        .project {
            background: #161b22;
            border: 1px solid #30363d;
            border-radius: 8px;
            padding: 1rem;
            margin-bottom: 0.8rem;
            transition: border-color 0.2s;
        }

        .project:hover {
            border-color: #58a6ff;
        }

        .project-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 0.5rem;
        }

        .project-name {
            color: #58a6ff;
            text-decoration: none;
            font-weight: 600;
        }

        .project-name:hover {
            text-decoration: underline;
        }

        .project-lang {
            font-size: 0.75rem;
            color: #8b949e;
            background: #0d1117;
            padding: 0.2rem 0.5rem;
            border-radius: 4px;
        }

        .project-desc {
            color: #8b949e;
            font-size: 0.9rem;
        }

        /* Contact */
        .contact {
            display: flex;
            gap: 1rem;
            flex-wrap: wrap;
        }

        .contact a {
            color: #c9d1d9;
            text-decoration: none;
            background: #161b22;
            border: 1px solid #30363d;
            padding: 0.6rem 1.2rem;
            border-radius: 6px;
            font-size: 0.9rem;
            transition: all 0.2s;
        }

        .contact a:hover {
            background: #58a6ff;
            color: #0d1117;
            border-color: #58a6ff;
        }

        /* Footer */
        footer {
            text-align: center;
            color: #8b949e;
            font-size: 0.85rem;
            margin-top: 3rem;
            padding-top: 2rem;
            border-top: 1px solid #30363d;
        }

        /* Responsive */
        @media (max-width: 500px) {
            body { padding: 1rem; }
            .header h1 { font-size: 1.4rem; }
            .project-header { flex-direction: column; align-items: flex-start; gap: 0.3rem; }
        }
    </style>
</head>
<body>

    <!-- Header -->
   <div class="header">
        <img src="https://github.com/github.png" alt="Profilbild">
        <h1>Max Mustermann</h1>
        <p>Umschulung zum Fachinformatiker für Anwendungsentwicklung</p>
        <div class="badges">
            <span class="badge">🎓 In Ausbildung</span>
            <span class="badge">📍 Deutschland</span>
            <span class="badge">🔍 Praktikumssuche</span>
        </div>
    </div>

    <!-- Über mich -->
   <section>
        <h2>Über mich</h2>
        <p>
            Ich bilde mich aktuell zum <strong>Fachinformatiker für Anwendungsentwicklung</strong> um. 
            Mein Fokus liegt auf sauberem Code, verständlichen Datenbanken und modernen Webseiten. 
            Ich lerne täglich dazu und dokumentiere meinen Fortschritt hier.
        </p>
    </section>

    <!-- Was ich kann -->
   <section>
        <h2>Meine Skills</h2>
        <div>
            <span class="skill-tag">☕ Java <span class="level">●●●○○</span></span>
            <span class="skill-tag">🐍 Python <span class="level">●●●○○</span></span>
            <span class="skill-tag">🗄️ SQL <span class="level">●●●○○</span></span>
            <span class="skill-tag">🌐 HTML5 <span class="level">●●●●○</span></span>
            <span class="skill-tag">🎨 CSS3 <span class="level">●●●●○</span></span>
            <span class="skill-tag">🛠️ PyCharm <span class="level">●●●●○</span></span>
            <span class="skill-tag">🐙 Git/GitHub <span class="level">●●●○○</span></span>
        </div>
        <p style="color: #8b949e; font-size: 0.85rem; margin-top: 0.8rem;">
            ●●●●● = Experte &nbsp;|&nbsp; ●●●●○ = Fortgeschritten &nbsp;|&nbsp; ●●●○○ = Gut &nbsp;|&nbsp; ●●○○○ = Grundlagen
        </p>
    </section>

    <!-- Mein Weg -->
  <section>
        <h2>Mein Weg</h2>
        <div class="timeline">
            <div class="timeline-item done">
                <div class="timeline-date">2023</div>
                <div class="timeline-title">Erste Schritte</div>
                <div class="timeline-desc">Selbststudium: HTML, CSS, Python-Grundlagen</div>
            </div>
            <div class="timeline-item done">
                <div class="timeline-date">2024 – Heute</div>
                <div class="timeline-title">Umschulung Fachinformatiker AE</div>
                <div class="timeline-desc">Berufsschule + Praxis: Java, SQL, OOP, Datenbanken</div>
            </div>
            <div class="timeline-item">
                <div class="timeline-date">2026</div>
                <div class="timeline-title">IHK-Abschluss & Berufseinstieg</div>
                <div class="timeline-desc">Ziel: Junior Developer oder Ausbildungsplatz</div>
            </div>
        </div>
    </section>

    <!-- Projekte -->
   <section>
        <h2>Meine Projekte</h2>
        
   <div class="project">
            <div class="project-header">
                <a href="#" class="project-name">📁 Todo-App</a>
                <span class="project-lang">Java + SQLite</span>
            </div>
            <p class="project-desc">Aufgabenverwaltung mit JavaFX-Oberfläche und lokaler Datenbank.</p>
        </div>

   <div class="project">
            <div class="project-header">
                <a href="#" class="project-name">📁 Portfolio-Seite</a>
                <span class="project-lang">HTML / CSS</span>
            </div>
            <p class="project-desc">Diese Seite – responsive, Dark Mode, ohne Frameworks.</p>
        </div>

   <div class="project">
            <div class="project-header">
                <a href="#" class="project-name">📁 Wetter-Tool</a>
                <span class="project-lang">Python</span>
            </div>
            <p class="project-desc">API-Abfrage und Datenverarbeitung mit Python-Script.</p>
        </div>
    </section>

    <!-- GitHub Stats -->
   <section>
        <h2>GitHub Aktivität</h2>
        <p style="text-align: center;">
            <img src="https://github-readme-stats.vercel.app/api?username=DEIN_USERNAME&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9" 
                 alt="Stats" style="max-width: 100%; border-radius: 8px;">
        </p>
    </section>

    <!-- Kontakt -->
   <section>
        <h2>Kontakt</h2>
        <div class="contact">
            <a href="https://github.com/DEIN_USERNAME" target="_blank">🐙 GitHub</a>
            <a href="azizihamid199@gmail.com">📧 E-Mail</a>
        </div>
   </section>

   <footer>
        <p>Erstellt während der Umschulung zum Fachinformatiker AE</p>
    </footer>

</body>
</html>
