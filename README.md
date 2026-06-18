<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fachinformatiker AE | GitHub Profil</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

  :root {
            --primary: #58a6ff;
            --secondary: #238636;
            --bg-dark: #0d1117;
            --bg-card: #161b22;
            --border: #30363d;
            --text-primary: #c9d1d9;
            --text-secondary: #8b949e;
            --accent: #f0883e;
        }

  body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;
            background-color: var(--bg-dark);
            color: var(--text-primary);
            line-height: 1.6;
        }

   .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 2rem;
        }

   /* Header / Hero Section */
        .hero {
            text-align: center;
            padding: 3rem 0;
            border-bottom: 1px solid var(--border);
            margin-bottom: 2rem;
        }

   .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 4px solid var(--primary);
            margin-bottom: 1rem;
            object-fit: cover;
        }

   .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
            background: linear-gradient(90deg, var(--primary), var(--secondary));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

   .hero .subtitle {
            color: var(--text-secondary);
            font-size: 1.2rem;
            margin-bottom: 1rem;
        }

  .badge-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 0.5rem;
            margin-top: 1rem;
        }

   .badge {
            display: inline-flex;
            align-items: center;
            padding: 0.4rem 0.8rem;
            border-radius: 20px;
            font-size: 0.85rem;
            font-weight: 600;
            border: 1px solid var(--border);
            background: var(--bg-card);
        }

   .badge.learning {
            border-color: var(--accent);
            color: var(--accent);
        }

  .badge.status {
            border-color: var(--secondary);
            color: var(--secondary);
        }

   /* Cards */
        .card {
            background: var(--bg-card);
            border: 1px solid var(--border);
            border-radius: 12px;
            padding: 1.5rem;
            margin-bottom: 1.5rem;
            transition: transform 0.2s, box-shadow 0.2s;
        }

  .card:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 24px rgba(0,0,0,0.3);
            border-color: var(--primary);
        }

  .card h2 {
            color: var(--primary);
            margin-bottom: 1rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

   .card h2 svg {
            width: 24px;
            height: 24px;
        }

   /* Skills Grid */
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 1rem;
        }

   .skill-item {
            display: flex;
            align-items: center;
            gap: 0.75rem;
            padding: 0.75rem;
            background: var(--bg-dark);
            border-radius: 8px;
            border: 1px solid var(--border);
        }

  .skill-icon {
            width: 32px;
            height: 32px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.2rem;
        }

   .skill-info h4 {
            font-size: 0.9rem;
            margin-bottom: 0.2rem;
        }

  .progress-bar {
            width: 100%;
            height: 6px;
            background: var(--border);
            border-radius: 3px;
            overflow: hidden;
        }

   .progress-fill {
            height: 100%;
            background: linear-gradient(90deg, var(--primary), var(--secondary));
            border-radius: 3px;
            transition: width 1s ease;
        }

   /* Timeline */
        .timeline {
            position: relative;
            padding-left: 2rem;
        }

   .timeline::before {
            content: '';
            position: absolute;
            left: 0;
            top: 0;
            bottom: 0;
            width: 2px;
            background: linear-gradient(to bottom, var(--primary), var(--secondary));
        }

   .timeline-item {
            position: relative;
            margin-bottom: 1.5rem;
            padding-left: 1rem;
        }

  .timeline-item::before {
            content: '';
            position: absolute;
            left: -1.4rem;
            top: 0.5rem;
            width: 12px;
            height: 12px;
            border-radius: 50%;
            background: var(--bg-dark);
            border: 2px solid var(--primary);
        }

  .timeline-item.active::before {
            background: var(--secondary);
            border-color: var(--secondary);
            box-shadow: 0 0 10px var(--secondary);
        }

   .timeline-date {
            font-size: 0.85rem;
            color: var(--text-secondary);
            margin-bottom: 0.3rem;
        }

   .timeline-title {
            font-weight: 600;
            color: var(--text-primary);
            margin-bottom: 0.3rem;
        }

  /* Project Cards */
        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
            gap: 1rem;
        }

  .project-card {
            background: var(--bg-dark);
            border: 1px solid var(--border);
            border-radius: 8px;
            padding: 1rem;
            transition: all 0.2s;
        }

  .project-card:hover {
            border-color: var(--primary);
        }

  .project-header {
            display: flex;
            justify-content: space-between;
            align-items: start;
            margin-bottom: 0.5rem;
        }

   .project-title {
            color: var(--primary);
            font-weight: 600;
            text-decoration: none;
        }

  .project-title:hover {
            text-decoration: underline;
        }

  .project-lang {
            font-size: 0.75rem;
            padding: 0.2rem 0.5rem;
            border-radius: 12px;
            background: var(--bg-card);
            border: 1px solid var(--border);
        }

  .project-desc {
            color: var(--text-secondary);
            font-size: 0.9rem;
            margin-bottom: 0.75rem;
        }

   .project-stats {
            display: flex;
            gap: 1rem;
            font-size: 0.8rem;
            color: var(--text-secondary);
        }

   .stat {
            display: flex;
            align-items: center;
            gap: 0.3rem;
        }

  /* Contact Section */
        .contact-links {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            justify-content: center;
        }

  .contact-btn {
            display: inline-flex;
            align-items: center;
            gap: 0.5rem;
            padding: 0.75rem 1.5rem;
            border-radius: 8px;
            text-decoration: none;
            color: var(--text-primary);
            background: var(--bg-dark);
            border: 1px solid var(--border);
            transition: all 0.2s;
            font-weight: 500;
        }

   .contact-btn:hover {
            background: var(--primary);
            color: var(--bg-dark);
            border-color: var(--primary);
        }

  /* Stats Grid */
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1rem;
            margin-bottom: 1.5rem;
        }

   .stat-card {
            background: var(--bg-card);
            border: 1px solid var(--border);
            border-radius: 8px;
            padding: 1rem;
            text-align: center;
        }

   .stat-number {
            font-size: 2rem;
            font-weight: 700;
            color: var(--primary);
        }

 .stat-label {
            color: var(--text-secondary);
            font-size: 0.9rem;
        }

  /* Footer */
        footer {
            text-align: center;
            padding: 2rem;
            border-top: 1px solid var(--border);
            color: var(--text-secondary);
            font-size: 0.9rem;
        }

  /* Animations */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

   .card {
            animation: fadeIn 0.6s ease forwards;
        }

   .card:nth-child(1) { animation-delay: 0.1s; }
        .card:nth-child(2) { animation-delay: 0.2s; }
        .card:nth-child(3) { animation-delay: 0.3s; }
        .card:nth-child(4) { animation-delay: 0.4s; }

   /* Responsive */
        @media (max-width: 600px) {
            .hero h1 { font-size: 1.8rem; }
            .skills-grid { grid-template-columns: 1fr; }
            .projects-grid { grid-template-columns: 1fr; }
            .container { padding: 1rem; }
        }
    </style>
</head>
<body>

  <div class="container">
        <!-- Hero Section -->
        <div class="hero">
            <!-- Ersetze den src durch dein GitHub Profilbild -->
            <img src="https://github.com/github.png" alt="Profilbild" class="profile-img" id="profile-img">
            <h1>Hallo, ich bin [Dein Name] 👋</h1>
            <p class="subtitle">Umschulung zum Fachinformatiker für Anwendungsentwicklung</p>
            
  <div class="badge-container">
                <span class="badge status">🎓 In Ausbildung</span>
                <span class="badge learning">📚 Lernend</span>
                <span class="badge">💻 Java & Python</span>
                <span class="badge">🌐 Webentwicklung</span>
                <span class="badge">🗄️ Datenbanken</span>
            </div>
        </div>
 <!-- Quick Stats -->
        <div class="stats-grid">
            <div class="stat-card">
                <div class="stat-number" id="repo-count">0</div>
                <div class="stat-label">Repositories</div>
            </div>
            <div class="stat-card">
                <div class="stat-number" id="commit-count">0</div>
                <div class="stat-label">Commits</div>
            </div>
            <div class="stat-card">
                <div class="stat-number">2+</div>
                <div class="stat-label">Jahre Erfahrung</div>
            </div>
            <div class="stat-card">
                <div class="stat-number">5+</div>
                <div class="stat-label">Technologien</div>
            </div>
        </div>
  <!-- About Me -->
        <div class="card">
            <h2>
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                    <path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path>
                    <circle cx="12" cy="7" r="4"></circle>
                </svg>
                Über mich
            </h2>
            <p>
                Ich absolviere aktuell eine Umschulung zum <strong>Fachinformatiker für Anwendungsentwicklung</strong> 
                und entwickle mich stetig zum professionellen Softwareentwickler weiter. 
                Meine Leidenschaft gilt der Entwicklung robuster, skalierbarer Anwendungen 
                und der kontinuierlichen Erweiterung meines technischen Horizonts.
            </p>
            <br>
            <p>
                <strong>Schwerpunkte meiner Ausbildung:</strong>
            </p>
            <ul style="margin-left: 1.5rem; color: var(--text-secondary);">
                <li>Objektorientierte Programmierung (Java, Python)</li>
                <li>Webentwicklung (HTML, CSS, JavaScript, React)</li>
                <li>Datenbankdesign und SQL</li>
                <li>Softwarearchitektur und Design Patterns</li>
                <li>Versionskontrolle mit Git/GitHub</li>
                <li>Agile Entwicklungsmethoden (Scrum)</li>
            </ul>
        </div>
 <!-- Skills -->
       <!-- Skills-Sektion für dein GitHub Profil -->
<div class="card">
    <h2>
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
            <polyline points="16 18 22 12 16 6"></polyline>
            <polyline points="8 6 2 12 8 18"></polyline>
        </svg>
        Während der Umschulung gelernt
    </h2>
    
    <!-- IDE & Tools -->
    <h3 style="color: var(--text-secondary); margin: 1.5rem 0 1rem; font-size: 0.9rem; text-transform: uppercase; letter-spacing: 1px;">
        Entwicklungsumgebung
    </h3>
    <div class="skills-grid">
        <div class="skill-item">
            <div class="skill-icon">🛠️</div>
            <div class="skill-info" style="width: 100%;">
                <div style="display: flex; justify-content: space-between; margin-bottom: 0.3rem;">
                    <h4>PyCharm / IntelliJ IDEA</h4>
                    <span style="color: var(--text-secondary); font-size: 0.85rem;">IDE-Nutzung, Debugging, Refactoring</span>
                </div>
                <div class="progress-bar"><div class="progress-fill" style="width: 80%"></div></div>
            </div>
        </div>
    </div>

    <!-- Programmiersprachen -->
    <h3 style="color: var(--text-secondary); margin: 1.5rem 0 1rem; font-size: 0.9rem; text-transform: uppercase; letter-spacing: 1px;">
        Programmierung
    </h3>
    <div class="skills-grid">
        <div class="skill-item">
            <div class="skill-icon">☕</div>
            <div class="skill-info" style="width: 100%;">
                <div style="display: flex; justify-content: space-between; margin-bottom: 0.3rem;">
                    <h4>Java</h4>
                    <span style="color: var(--text-secondary); font-size: 0.85rem;">OOP, Collections, Streams, JavaFX</span>
                </div>
                <div class="progress-bar"><div class="progress-fill" style="width: 75%"></div></div>
            </div>
        </div>
        <div class="skill-item">
            <div class="skill-icon">🐍</div>
            <div class="skill-info" style="width: 100%;">
                <div style="display: flex; justify-content: space-between; margin-bottom: 0.3rem;">
                    <h4>Python</h4>
                    <span style="color: var(--text-secondary); font-size: 0.85rem;">Grundlagen, Datenstrukturen, Scripting</span>
                </div>
                <div class="progress-bar"><div class="progress-fill" style="width: 70%"></div></div>
            </div>
        </div>
    </div>

    <!-- Datenbanken -->
    <h3 style="color: var(--text-secondary); margin: 1.5rem 0 1rem; font-size: 0.9rem; text-transform: uppercase; letter-spacing: 1px;">
        Datenbanken
    </h3>
    <div class="skills-grid">
        <div class="skill-item">
            <div class="skill-icon">🗄️</div>
            <div class="skill-info" style="width: 100%;">
                <div style="display: flex; justify-content: space-between; margin-bottom: 0.3rem;">
                    <h4>SQL</h4>
                    <span style="color: var(--text-secondary); font-size: 0.85rem;">MySQL, PostgreSQL, JOINs, Normalisierung</span>
                </div>
                <div class="progress-bar"><div class="progress-fill" style="width: 72%"></div></div>
            </div>
        </div>
    </div>

    <!-- Webentwicklung -->
    <h3 style="color: var(--text-secondary); margin: 1.5rem 0 1rem; font-size: 0.9rem; text-transform: uppercase; letter-spacing: 1px;">
        Webentwicklung
    </h3>
    <div class="skills-grid">
        <div class="skill-item">
            <div class="skill-icon">🌐</div>
            <div class="skill-info" style="width: 100%;">
                <div style="display: flex; justify-content: space-between; margin-bottom: 0.3rem;">
                    <h4>HTML5</h4>
                    <span style="color: var(--text-secondary); font-size: 0.85rem;">Semantik, Struktur, Accessibility</span>
                </div>
                <div class="progress-bar"><div class="progress-fill" style="width: 85%"></div></div>
            </div>
        </div>
        <div class="skill-item">
            <div class="skill-icon">🎨</div>
            <div class="skill-info" style="width: 100%;">
                <div style="display: flex; justify-content: space-between; margin-bottom: 0.3rem;">
                    <h4>CSS3</h4>
                    <span style="color: var(--text-secondary); font-size: 0.85rem;">Flexbox, Grid, Responsive Design, Animationen</span>
                </div>
                <div class="progress-bar"><div class="progress-fill" style="width: 78%"></div></div>
            </div>
        </div>
    </div>
</div>

<!-- Zusätzliche "Was ich gelernt habe" Sektion -->
<div class="card">
    <h2>
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
            <path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"></path>
            <polyline points="14 2 14 8 20 8"></polyline>
            <line x1="16" y1="13" x2="8" y2="13"></line>
            <line x1="16" y1="17" x2="8" y2="17"></line>
            <polyline points="10 9 9 9 8 9"></polyline>
        </svg>
        Detaillierte Lernerfolge
    </h2>
    
 <div style="display: grid; gap: 1.2rem;">
        <!-- Java -->
        <div style="background: var(--bg-dark); padding: 1rem; border-radius: 8px; border-left: 3px solid #b07219;">
            <h4 style="color: #b07219; margin-bottom: 0.5rem;">☕ Java-Entwicklung</h4>
            <ul style="margin-left: 1.2rem; color: var(--text-secondary); font-size: 0.9rem; line-height: 1.8;">
                <li>Objektorientierte Programmierung (Klassen, Vererbung, Polymorphie, Encapsulation)</li>
                <li>Java Collections Framework (List, Set, Map, Streams API)</li>
                <li>Ausnahmebehandlung (try-catch, eigene Exceptions)</li>
                <li>JavaFX für Desktop-GUIs (FXML, Controller, Event-Handling)</li>
                <li>Datei-Ein-/Ausgabe (IO-Streams, Serialization)</li>
                <li>Unit-Testing mit JUnit</li>
            </ul>
        </div>
     <!-- Python -->
        <div style="background: var(--bg-dark); padding: 1rem; border-radius: 8px; border-left: 3px solid #3572A5;">
            <h4 style="color: #3572A5; margin-bottom: 0.5rem;">🐍 Python-Grundlagen</h4>
            <ul style="margin-left: 1.2rem; color: var(--text-secondary); font-size: 0.9rem; line-height: 1.8;">
                <li>Grundlegende Syntax, Datenstrukturen (Listen, Dictionaries, Tupel)</li>
                <li>Funktionen und Module</li>
                <li>Objektorientierte Konzepte in Python</li>
                <li>Dateiverarbeitung und CSV-Handling</li>
                <li>Erste Schritte mit Flask (Web-Framework)</li>
            </ul>
        </div>
 <!-- SQL -->
        <div style="background: var(--bg-dark); padding: 1rem; border-radius: 8px; border-left: 3px solid #e38c00;">
            <h4 style="color: #e38c00; margin-bottom: 0.5rem;">🗄️ Datenbanken & SQL</h4>
            <ul style="margin-left: 1.2rem; color: var(--text-secondary); font-size: 0.9rem; line-height: 1.8;">
                <li>Datenbankdesign und ER-Modelle</li>
                <li>DDL (CREATE, ALTER, DROP) und DML (SELECT, INSERT, UPDATE, DELETE)</li>
                <li>Komplexe JOIN-Operationen (INNER, LEFT, RIGHT, FULL)</li>
                <li>Subqueries und Views</li>
                <li>Normalisierung (1NF, 2NF, 3NF)</li>
                <li>Transaktionen und ACID-Prinzipien</li>
                <li>JDBC-Verbindung Java ↔ Datenbank</li>
            </ul>
        </div>
 <!-- HTML/CSS -->
        <div style="background: var(--bg-dark); padding: 1rem; border-radius: 8px; border-left: 3px solid #e34c26;">
            <h4 style="color: #e34c26; margin-bottom: 0.5rem;">🌐 Webentwicklung (HTML & CSS)</h4>
            <ul style="margin-left: 1.2rem; color: var(--text-secondary); font-size: 0.9rem; line-height: 1.8;">
                <li>Semantisches HTML5 (header, nav, main, article, section, footer)</li>
                <li>Formulare und Validierung</li>
                <li>CSS Layout-Techniken (Flexbox, CSS Grid)</li>
                <li>Responsive Design (Media Queries, Mobile-First)</li>
                <li>CSS-Variablen und Custom Properties</li>
                <li>Animationen und Transitions</li>
                <li>Dark Mode Implementierung</li>
            </ul>
        </div>
  <!-- PyCharm/IDE -->
        <div style="background: var(--bg-dark); padding: 1rem; border-radius: 8px; border-left: 3px solid #00d9ff;">
            <h4 style="color: #00d9ff; margin-bottom: 0.5rem;">🛠️ PyCharm & Entwicklungswerkzeuge</h4>
            <ul style="margin-left: 1.2rem; color: var(--text-secondary); font-size: 0.9rem; line-height: 1.8;">
                <li>Projekt-Setup und virtuelle Umgebungen</li>
                <li>Debugging (Breakpoints, Step-Through, Watch-Expressions)</li>
                <li>Code-Refactoring und automatische Code-Vervollständigung</li>
                <li>Version Control Integration (Git-Commits, Branches, Merge)</li>
                <li>Datenbank-Tools direkt in der IDE</li>
                <li>Terminal- und Docker-Integration</li>
            </ul>
        </div>
    </div>
</div>
 <!-- Ausbildungsverlauf -->
        <div class="card">
            <h2>
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                    <path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"></path>
                    <polyline points="22 4 12 14.01 9 11.01"></polyline>
                </svg>
                Ausbildungsverlauf
            </h2>
            <div class="timeline">
                <div class="timeline-item active">
                    <div class="timeline-date">2024 - Heute</div>
                    <div class="timeline-title">Umschulung Fachinformatiker AE</div>
                    <p style="color: var(--text-secondary); font-size: 0.9rem;">
                        Berufsfachschule + Praktikum. Fokus auf Java, Datenbanken und Webentwicklung.
                    </p>
                </div>
                <div class="timeline-item">
                    <div class="timeline-date">2023 - 2024</div>
                    <div class="timeline-title">Vorbereitung & Grundlagen</div>
                    <p style="color: var(--text-secondary); font-size: 0.9rem;">
                        Selbststudium: Python, HTML/CSS, erste Projekte auf GitHub.
                    </p>
                </div>
                <div class="timeline-item">
                    <div class="timeline-date">Zukunft</div>
                    <div class="timeline-title">Abschluss & Berufseinstieg</div>
                    <p style="color: var(--text-secondary); font-size: 0.9rem;">
                        IHK-Abschlussprüfung und Start als Junior Developer.
                    </p>
                </div>
            </div>
        </div>
 <!-- Projekte -->
        <div class="card">
            <h2>
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                    <path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path>
                </svg>
                Projekte
            </h2>
            <div class="projects-grid" id="projects-container">
                <!-- Projekte werden dynamisch geladen oder manuell eingefügt -->
                <div class="project-card">
                    <div class="project-header">
                        <a href="#" class="project-title">📁 Todo-App</a>
                        <span class="project-lang">Java</span>
                    </div>
                    <p class="project-desc">Eine Aufgabenverwaltung mit JavaFX und SQLite-Datenbank.</p>
                    <div class="project-stats">
                        <span class="stat">⭐ 3</span>
                        <span class="stat">🍴 1</span>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-header">
                        <a href="#" class="project-title">📁 Portfolio-Website</a>
                        <span class="project-lang">HTML/CSS/JS</span>
                    </div>
                    <p class="project-desc">Responsive Portfolio mit Dark Mode und Animationen.</p>
                    <div class="project-stats">
                        <span class="stat">⭐ 5</span>
                        <span class="stat">🍴 2</span>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-header">
                        <a href="#" class="project-title">📁 Weather-API</a>
                        <span class="project-lang">Python</span>
                    </div>
                    <p class="project-desc">REST-API zur Abfrage von Wetterdaten mit Flask.</p>
                    <div class="project-stats">
                        <span class="stat">⭐ 2</span>
                        <span class="stat">🍴 0</span>
                    </div>
                </div>
            </div>
        </div>
 <!-- GitHub Activity -->
        <div class="card">
            <h2>
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                    <polyline points="22 12 18 12 15 21 9 3 6 12 2 12"></polyline>
                </svg>
                GitHub Aktivität
            </h2>
            <p style="text-align: center; margin-bottom: 1rem;">
                <img src="https://github-readme-stats.vercel.app/api?username=DEIN_GITHUB_USERNAME&show_icons=true&theme=dark&hide_border=true&bg_color=161b22&title_color=58a6ff&text_color=c9d1d9" 
                     alt="GitHub Stats" style="max-width: 100%; border-radius: 8px;">
            </p>
            <p style="text-align: center;">
                <img src="https://github-readme-streak-stats.herokuapp.com/?user=DEIN_GITHUB_USERNAME&theme=dark&hide_border=true&background=161b22&stroke=58a6ff&ring=58a6ff&fire=f0883e&currStreakNum=58a6ff&sideNums=c9d1d9&currStreakLabel=c9d1d9&sideLabels=c9d1d9&dates=8b949e" 
                     alt="GitHub Streak" style="max-width: 100%; border-radius: 8px;">
            </p>
        </div>
 <!-- Kontakt -->
        <div class="card">
            <h2>
                <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                    <path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"></path>
                    <polyline points="22,6 12,13 2,6"></polyline>
                </svg>
                Kontakt
            </h2>
            <div class="contact-links">
                <a href="https://github.com/DEIN_GITHUB_USERNAME" class="contact-btn" target="_blank">
                    🐙 GitHub
                </a>
                <a href="mailto:deine.email@example.com" class="contact-btn">
                    📧 E-Mail
                </a>
                <a href="https://linkedin.com/in/DEIN_LINKEDIN" class="contact-btn" target="_blank">
                    💼 LinkedIn
                </a>
                <a href="https://DEIN_GITHUB_USERNAME.github.io" class="contact-btn" target="_blank">
                    🌐 Portfolio
                </a>
            </div>
        </div>

  <footer>
            <p>Made with ❤️ | Fachinformatiker für Anwendungsentwicklung (in Ausbildung)</p>
            <p style="margin-top: 0.5rem; font-size: 0.8rem;">Letztes Update: Juni 2026</p>
        </footer>
    </div>
  <script>
        // Animation für Progress Bars beim Laden
        document.addEventListener('DOMContentLoaded', () => {
            const progressBars = document.querySelectorAll('.progress-fill');
            progressBars.forEach(bar => {
                const width = bar.style.width;
                bar.style.width = '0';
                setTimeout(() => {
                    bar.style.width = width;
                }, 300);
            });
            // Counter Animation für Stats
            const animateValue = (id, start, end, duration) => {
                const obj = document.getElementById(id);
                if (!obj) return;
                let startTimestamp = null;
                const step = (timestamp) => {
                    if (!startTimestamp) startTimestamp = timestamp;
                    const progress = Math.min((timestamp - startTimestamp) / duration, 1);
                    obj.innerHTML = Math.floor(progress * (end - start) + start);
                    if (progress < 1) {
                        window.requestAnimationFrame(step);
                    }
                };
                window.requestAnimationFrame(step);
            };

  // Hier kannst du deine echten Werte eintragen
            animateValue('repo-count', 0, 12, 2000);
            animateValue('commit-count', 0, 150, 2000);
        });
 // Dynamisches Laden der GitHub Repos (optional)
        const username = ; // <-- HIER DEINEN USERNAME EINTRAGEN
        
   async function fetchGitHubRepos() {
            try {
                const response = await fetch(`https://api.github.com/users/${username}/repos?sort=updated&per_page=6`);
                const repos = await response.json();
                
  if (repos.length > 0) {
                    const container = document.getElementById('projects-container');
                    container.innerHTML = repos.map(repo => `
  <div class="project-card">
                            <div class="project-header">
                                <a href="${repo.html_url}" class="project-title" target="_blank">📁 ${repo.name}</a>
                                <span class="project-lang">${repo.language || 'Mixed'}</span>
                            </div>
                            <p class="project-desc">${repo.description || 'Keine Beschreibung vorhanden'}</p>
                            <div class="project-stats">
                                <span class="stat">⭐ ${repo.stargazers_count}</span>
                                <span class="stat">🍴 ${repo.forks_count}</span>
                                <span class="stat">📅 ${new Date(repo.updated_at).toLocaleDateString('de-DE')}</span>
                            </div>
                        </div>
                    `).join('');
                }
            } catch (error) {
                console.log('GitHub API nicht erreichbar, zeige Beispielprojekte');
            }
        }

   // Kommentiere diese Zeile ein, wenn du echte GitHub-Daten laden möchtest:
        // fetchGitHubRepos();
    </script>
</body>
</html>
