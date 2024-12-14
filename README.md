<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Save The Capybaras</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #ff6347;
            color: #fff;
            padding: 20px 0;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }
        .header-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 20px;
        }
        .logo {
            font-size: 1.5em;
            font-weight: bold;
        }
        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            text-decoration: none;
            color: #fff;
            font-weight: bold;
        }
        .banner {
            text-align: center;
            padding: 100px 20px 20px;
            background-color: #f39c12;
            color: #fff;
        }
        .banner h2 {
            font-size: 2.5em;
        }
        .game-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .game-card {
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
            padding: 20px;
        }
        .game-card img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .game-card h3 {
            margin: 10px 0;
            font-size: 1.2em;
        }
        .play-button {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 15px;
            background: #ff6347;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
            transition: background 0.3s;
        }
        .play-button:hover {
            background: #e55337;
        }
        footer {
            text-align: center;
            padding: 10px;
            background: #333;
            color: #fff;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="header-container">
            <h1 class="logo">Save The Capybaras</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#games">Games</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section class="banner">
            <h2>Welcome to Save The Capybaras</h2>
            <p>Your ultimate hub for unblocked games. Play and enjoy anywhere!</p>
        </section>

        <div class="game-grid" id="game-list">
            <div class="game-card">
                <img src="game1.png" alt="Game 1 Logo">
                <h3>Super Shooter</h3>
                <a href="games/super-shooter.html" class="play-button">Play Now</a>
            </div>
            <div class="game-card">
                <img src="game2.png" alt="Game 2 Logo">
                <h3>Racing Mania</h3>
                <a href="games/racing-mania.html" class="play-button">Play Now</a>
            </div>
            <div class="game-card">
                <img src="game3.png" alt="Game 3 Logo">
                <h3>Block Builder</h3>
                <a href="games/block-builder.html" class="play-button">Play Now</a>
            </div>
            <div class="game-card">
                <img src="game4.png" alt="Game 4 Logo">
                <h3>Puzzle Challenge</h3>
                <a href="games/puzzle-challenge.html" class="play-button">Play Now</a>
            </div>
        </div>
    </main>

    <footer>
        <p>&copy; 2024 Save The Capybaras. All rights reserved.</p>
    </footer>
</body>
</html>

