# MY-GAME<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FunGames - Jeux Gratuits</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            text-align: center;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 50px 20px;
        }
        h1 {
            margin: 0;
            font-size: 2.5em;
        }
        .description {
            font-size: 1.2em;
            margin-top: 10px;
        }
        .games-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            padding: 40px 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .game-card {
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            padding: 20px;
            text-align: center;
        }
        .game-card h3 {
            margin-top: 0;
        }
        .play-button {
            background-color: #28a745;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1em;
        }
        .play-button:hover {
            background-color: #218838;
        }
        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header>
        <h1>FunGames - Jeux Gratuits</h1>
        <p class="description">Découvrez une collection de jeux gratuits et amusants directement dans votre navigateur. Pas besoin d'installation !</p>
    </header>
    
    <section class="games-grid">
        <div class="game-card">
            <h3>Tic-Tac-Toe</h3>
            <p>Un jeu classique pour deux joueurs. Marquez trois en ligne pour gagner !</p>
            <button class="play-button" onclick="window.open('https://playtictactoe.org/', '_blank')">Jouer</button>
        </div>
        <div class="game-card">
            <h3>Snake</h3>
            <p>Contrôlez un serpent pour manger des pommes et grandir. Évitez les murs !</p>
            <button class="play-button" onclick="window.open('https://snake-game.js.org/', '_blank')">Jouer</button>
        </div>
        <div class="game-card">
            <h3>Tetris</h3>
            <p>Arrangez les blocs tombants pour former des lignes complètes.</p>
            <button class="play-button" onclick="window.open('https://tetris.com/play-tetris', '_blank')">Jouer</button>
        </div>
        <div class="game-card">
            <h3>Pac-Man</h3>
            <p>Mangez les points tout en évitant les fantômes dans ce jeu d'arcade classique.</p>
            <button class="play-button" onclick="window.open('https://freepacman.org/', '_blank')">Jouer</button>
        </div>
        <div class="game-card">
            <h3>2048</h3>
            <p>Fusionnez les tuiles pour atteindre le nombre 2048.</p>
            <button class="play-button" onclick="window.open('https://play2048.co/', '_blank')">Jouer</button>
        </div>
        <div class="game-card">
            <h3>Frogger</h3>
            <p>Aidez la grenouille à traverser la route et la rivière en toute sécurité.</p>
            <button class="play-button" onclick="window.open('https://froggerclassic.appspot.com/', '_blank')">Jouer</button>
        </div>
    </section>
    
    <footer>
        <p>&copy; 2023 FunGames. Tous droits réservés.</p>
    </footer>
</body>
</html>
