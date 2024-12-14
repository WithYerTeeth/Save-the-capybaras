<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Save The Capybaras</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="header-container">
            <h1 class="logo">Save The Capybaras</h1>
            <nav>
                <ul class="nav-links">
                    <li><a href="#">Home</a></li>
                    <li><a href="#categories">Games</a></li>
                    <li><a href="#popular">Popular</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
            <div class="dropdown">
                <button class="dropbtn">More</button>
                <div class="dropdown-content">
                    <a href="#new">New Games</a>
                    <a href="#top-rated">Top Rated</a>
                    <a href="#support">Support</a>
                </div>
            </div>
        </div>
    </header>

    <main>
        <section class="banner">
            <h2>Play Your Favorite Unblocked Games!</h2>
            <p>Discover a world of fun with our selection of unblocked games. Enjoy anytime, anywhere!</p>
        </section>

        <div class="game-grid" id="game-list">
            <div class="game-card">
                <img src="game1.jpg" alt="Game 1">
                <h3>Super Shooter</h3>
                <a href="games/super-shooter.html" class="play-button">Play Now</a>
            </div>
            <div class="game-card">
                <img src="game2.jpg" alt="Game 2">
                <h3>Car Racer X</h3>
                <a href="games/car-racer-x.html" class="play-button">Play Now</a>
            </div>
            <div class="game-card">
                <img src="game3.jpg" alt="Game 3">
                <h3>Block Builder</h3>
                <a href="games/block-builder.html" class="play-button">Play Now</a>
            </div>
            <div class="game-card">
                <img src="game4.jpg" alt="Game 4">
                <h3>Puzzle Master</h3>
                <a href="games/puzzle-master.html" class="play-button">Play Now</a>
            </div>
        </div>
    </main>

    <footer>
        <p>&copy; 2024 Save The Capybaras. All rights reserved.</p>
    </footer>

    <script>
        // JavaScript to handle search functionality
        const searchInput = document.getElementById('search');
        const gameCards = document.querySelectorAll('.game-card');

        searchInput.addEventListener('input', function () {
            const searchValue = searchInput.value.toLowerCase();
            gameCards.forEach(card => {
                const title = card.querySelector('h3').textContent.toLowerCase();
                if (title.includes(searchValue)) {
                    card.style.display = 'block';
                } else {
                    card.style.display = 'none';
                }
            });
        });
    </script>
</body>
</html>
