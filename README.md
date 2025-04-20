<!DOCTYPE html>
<html lang="de">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>PC Jockel - PC Builds</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #1c1c1c;
            color: #f0f0f0;
        }

        header {
            background-color: #121212;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            color: #ff9800;
            margin: 0;
        }

        .category {
            padding: 20px;
            margin: 20px 0;
            background-color: #333;
            border-radius: 8px;
        }

        .category h2 {
            color: #ff9800;
            text-align: center;
            margin-bottom: 20px;
        }

        .build-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-evenly;
            gap: 15px;
        }

        .build-item {
            background-color: #444;
            padding: 15px;
            border-radius: 8px;
            width: 30%;
            text-align: center;
            transition: 0.3s;
        }

        .build-item:hover {
            background-color: #555;
            transform: translateY(-5px);
        }

        .build-item img {
            width: 100%;
            border-radius: 8px;
            height: auto;
        }

        .build-item h3 {
            color: #ff9800;
            margin-top: 10px;
        }

        .build-item p {
            color: #bbb;
            margin-top: 10px;
        }

        .build-item a {
            text-decoration: none;
            color: #ff9800;
            margin-top: 10px;
            display: block;
            transition: color 0.3s ease;
        }

        .build-item a:hover {
            color: white;
        }

        @media (max-width: 768px) {
            .build-item {
                width: 45%;
            }
        }

        @media (max-width: 480px) {
            .build-item {
                width: 90%;
            }
        }
    </style>
</head>

<body>
    <header>
        <h1>PC Jockel - PC Builds</h1>
    </header>

    <!-- Einsteiger Build -->
    <section class="category">
        <h2>Einsteiger Build - Unter 800€</h2>
        <div class="build-list">
            <div class="build-item">
                <img src="https://via.placeholder.com/400x300.png?text=Build+1" alt="Einsteiger Build 1">
                <h3>PC Build 1</h3>
                <p>Ideal für den Einstieg! Schneller und günstiger Gaming-PC.</p>
                <a href="https://geizhals.de/wishlists/4408887" target="_blank">Jetzt Kaufen</a>
            </div>
            <!-- Weitere Einsteiger Builds hier hinzufügen -->
        </div>
    </section>

    <!-- Midrange Build -->
    <section class="category">
        <h2>Midrange Build - 800€ bis 1500€</h2>
        <div class="build-list">
            <div class="build-item">
                <img src="https://via.placeholder.com/400x300.png?text=Build+2" alt="Midrange Build 1">
                <h3>PC Build 2</h3>
                <p>Ideal für Gaming und anspruchsvolle Anwendungen.</p>
                <a href="https://geizhals.de/wishlists/4408922" target="_blank">Jetzt Kaufen</a>
            </div>
            <!-- Weitere Midrange Builds hier hinzufügen -->
        </div>
    </section>

    <!-- Highend Build -->
    <section class="category">
        <h2>Highend Build - Ab 1500€</h2>
        <div class="build-list">
            <div class="build-item">
                <img src="https://via.placeholder.com/400x300.png?text=Build+3" alt="Highend Build 1">
                <h3>PC Build 3</h3>
                <p>Für extrem leistungsfähige Gaming- und Workstation-Anwendungen.</p>
                <a href="https://geizhals.de/wishlists/4408923" target="_blank">Jetzt Kaufen</a>
            </div>
            <!-- Weitere Highend Builds hier hinzufügen -->
        </div>
    </section>

</body>

</html>

