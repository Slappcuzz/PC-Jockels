<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PC-Beratung by Slappcuzz</title>
    <style>
        :root {
            --rgb-blue: #00a2ff;
            --rgb-purple: #b700ff;
            --dark-bg: #0d0d12;
            --card-bg: #1a1a24;
            --text-light: #e0e0e0;
        }
        
        body {
            font-family: 'Segoe UI', sans-serif;
            background-color: var(--dark-bg);
            color: var(--text-light);
            line-height: 1.6;
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            text-align: center;
            margin-bottom: 40px;
            border-bottom: 2px solid var(--rgb-blue);
            padding-bottom: 20px;
        }
        
        h1 {
            font-size: 2.5rem;
            background: linear-gradient(90deg, var(--rgb-blue), var(--rgb-purple));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            margin-bottom: 10px;
        }
        
        .subtitle {
            font-style: italic;
            opacity: 0.8;
        }
        
        .discord-btn {
            display: inline-block;
            background: #5865F2;
            color: white;
            padding: 10px 20px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 15px;
            transition: transform 0.2s;
        }
        
        .discord-btn:hover {
            transform: translateY(-3px);
        }
        
        section {
            background-color: var(--card-bg);
            border-radius: 10px;
            padding: 25px;
            margin-bottom: 30px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
        }
        
        h2 {
            color: var(--rgb-blue);
            border-left: 4px solid var(--rgb-purple);
            padding-left: 10px;
        }
        
        .build-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .build-card {
            background-color: rgba(0,0,0,0.2);
            border-radius: 8px;
            padding: 15px;
            border-top: 3px solid var(--rgb-purple);
        }
        
        .build-card h3 {
            margin-top: 0;
            color: var(--rgb-blue);
        }
        
        .game-tag {
            display: inline-block;
            background: rgba(0,162,255,0.2);
            padding: 3px 8px;
            border-radius: 20px;
            font-size: 0.8rem;
            margin-right: 5px;
            margin-bottom: 5px;
        }
        
        footer {
            text-align: center;
            margin-top: 50px;
            font-size: 0.9rem;
            opacity: 0.7;
        }
        
        @media (max-width: 768px) {
            .build-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>PC-Beratung by Raphael / Slappcuzz</h1>
        <p class="subtitle">Gaming-Setups & Hardware-Tipps von einem, der selbst zockt</p>
        <a href="https://discord.gg/yjUKJ33F" class="discord-btn">Join me on Discord</a>
    </header>
    
    <section id="about">
        <h2>🎮 Kurz zu mir</h2>
        <p>Moin! Ich bin Raphael, aka Slappcuzz – das hier ist mein kleines Herzensprojekt neben Job und Zocken.</p>
        <p>Ich stelle PC-Systeme zusammen, die aus jedem Budget das Maximum rausholen. Kein Verkauf, kein Shop – einfach nur ehrliche Empfehlungen aus Leidenschaft.</p>
        <p>Ich mach das nicht professionell, sondern für Freunde, Bekannte und deren Freunde. Manchmal schraub ich die Kisten auch zusammen, wenn jemand aus der Nähe kommt �</p>
    </section>
    
    <section id="services">
        <h2>🔧 Was ich dir bieten kann</h2>
        <div class="build-grid">
            <div class="build-card">
                <h3>💻 Komplette Systeme</h3>
                <p>Optimierte Builds für verschiedene Budgets:</p>
                <ul>
                    <li><a href="https://geizhals.de/wishlists/4408924" target="_blank">Budget Gaming (500-700€)</a></li>
                    <li><a href="#" target="_blank">Midrange (1000-1500€)</a></li>
                    <li><a href="#" target="_blank">High-End (2000€+)</a></li>
                </ul>
            </div>
            
            <div class="build-card">
                <h3>🔄 PC-Upgrades</h3>
                <p>Was lohnt sich für bestehende Systeme:</p>
                <ul>
                    <li><a href="https://geizhals.de/wishlists/4420684" target="_blank">GPU-Upgrades</a></li>
                    <li><a href="#" target="_blank">CPU-Upgrades</a></li>
                    <li><a href="#" target="_blank">RAM/SSD-Optimierungen</a></li>
                </ul>
            </div>
            
            <div class="build-card">
                <h3>🎧 Peripherie</h3>
                <p>Das beste Preis/Leistungs-Verhältnis:</p>
                <ul>
                    <li><a href="https://geizhals.de/wishlists/4427677" target="_blank">Mäuse & Tastaturen</a></li>
                    <li><a href="#" target="_blank">Monitore</a></li>
                    <li><a href="#" target="_blank">Headsets</a></li>
                </ul>
            </div>
        </div>
    </section>
    
    <section id="example-build">
        <h2>📊 Beispiel-Build: Midrange 1440p</h2>
        <div class="build-card">
            <h3>Ideal für diese Spiele:</h3>
            <span class="game-tag">WoW</span>
            <span class="game-tag">CoD</span>
            <span class="game-tag">Path of Exile</span>
            <span class="game-tag">Conan Exiles</span>
            <span class="game-tag">Dota 2</span>
            
            <h3 style="margin-top: 20px;">Performance:</h3>
            <p>1440p | Hohe Details | 60-100 FPS (je nach Spiel)</p>
            <p>Perfekt für kommende Titel wie <strong>Dune: Awakening</strong> und <strong>Light No Fire</strong></p>
            
            <h3>Upgrade-Potenzial:</h3>
            <p>Einfacher GPU-Tausch möglich für zukünftige Anforderungen</p>
        </div>
    </section>
    
    <section id="community">
        <h2>👥 Über unsere Community</h2>
        <p>Aktuell zocken wir mit etwa 60 Leuten in verschiedenen Spielen zusammen:</p>
        <div style="margin-top: 15px;">
            <span class="game-tag">World of Warcraft</span>
            <span class="game-tag">Call of Duty</span>
            <span class="game-tag">Conan Exiles</span>
            <span class="game-tag">Dota 2</span>
            <span class="game-tag">Path of Exile</span>
        </div>
        <p style="margin-top: 20px;">Du bist herzlich willkommen in unserem Discord!</p>
    </section>
    
    <section id="contact">
        <h2>🤝 Kontakt</h2>
        <p>Bei Fragen oder für eine persönliche Beratung:</p>
        <p>Discord: <strong>Slappcuzz#9841</strong></p>
        <p>Oder join direkt: <a href="https://discord.gg/yjUKJ33F" style="color: var(--rgb-blue);">discord.gg/yjUKJ33F</a></p>
    </section>
    
    <footer>
        <p>© 2025 by Slappcuzz / Raphael — No Profit. Just Passion.</p>
        <p><em>"Ich bin kein Shop. Ich bin dein Kumpel mit Ahnung von Grafikkarten."</em></p>
    </footer>
</body>
</html>
