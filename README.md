<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Team Time Wizard - Yu-Gi-Oh! Kaarten en Decks</title>
    <style>
        /* Algemene styling */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            background-color: #f4f4f9;
            color: #333;
        }

        header {
            background-color: #3f51b5;
            color: #fff;
            padding: 1.5rem 0;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            font-size: 2.5rem;
        }

        nav {
            background-color: #303f9f;
            text-align: center;
            padding: 1rem;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.2rem;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: #f3e5f5;
        }

        .hero {
            background: url('https://source.unsplash.com/1600x900/?yu-gi-oh') no-repeat center center/cover;
            height: 60vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
            position: relative;
        }

        .hero h2 {
            font-size: 3rem;
            background-color: rgba(0, 0, 0, 0.5);
            padding: 1rem;
            border-radius: 10px;
        }

        .container {
            max-width: 1200px;
            margin: 3rem auto;
            padding: 0 2rem;
            text-align: center;
        }

        .cards {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            margin-top: 2rem;
        }

        .card {
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 1rem;
            margin: 1rem;
            width: 30%;
            text-align: left;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }

        .card img {
            max-width: 100%;
            border-radius: 8px;
        }

        .card h3 {
            margin-top: 0.5rem;
        }

        footer {
            background-color: #303f9f;
            color: white;
            text-align: center;
            padding: 1.5rem 0;
            margin-top: 3rem;
        }

        footer p {
            margin: 0;
        }

        .btn {
            display: inline-block;
            background-color: #3f51b5;
            color: white;
            padding: 0.8rem 1.5rem;
            border: none;
            border-radius: 5px;
            font-size: 1rem;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .btn:hover {
            background-color: #303f9f;
        }

        /* Responsiveness */
        @media (max-width: 768px) {
            .cards {
                flex-direction: column;
                align-items: center;
            }

            .card {
                width: 90%;
            }

            .hero h2 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Team Time Wizard</h1>
        <p>De beste Yu-Gi-Oh! kaarten en decks!</p>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">Over ons</a>
        <a href="#">Producten</a>
        <a href="#">Contact</a>
    </nav>

    <section class="hero">
        <h2>Verken Onze Unieke Yu-Gi-Oh! Kaarten</h2>
    </section>

    <div class="container">
        <h2>Onze Populaire Producten</h2>
        <div class="cards">
            <div class="card">
                <img src="https://source.unsplash.com/300x200/?yu-gi-oh,deck" alt="Yu-Gi-Oh! Deck">
                <h3>Yu-Gi-Oh! Decks</h3>
                <p>Kies uit een breed assortiment van sterke decks om je tegenstanders te verslaan.</p>
                <button class="btn" onclick="alert('Bestel nu je deck!')">Bestel Nu</button>
            </div>

            <div class="card">
                <img src="https://source.unsplash.com/300x200/?yu-gi-oh,card" alt="Losse Kaarten">
                <h3>Losse Kaarten</h3>
                <p>Vind zeldzame en krachtige losse kaarten voor je verzameling.</p>
                <button class="btn" onclick="alert('Bestel nu je losse kaarten!')">Bestel Nu</button>
            </div>

            <div class="card">
                <img src="https://source.unsplash.com/300x200/?yu-gi-oh,booster" alt="Booster Packs">
                <h3>Booster Packs</h3>
                <p>Ontdek nieuwe kaarten met onze spannende booster packs.</p>
                <button class="btn" onclick="alert('Bestel nu je booster pack!')">Bestel Nu</button>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Team Time Wizard. Alle rechten voorbehouden.</p>
    </footer>
</body>
</html>

