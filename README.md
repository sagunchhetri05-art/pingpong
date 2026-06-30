<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pong Game</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Pong Game</h1>
        <div class="scoreboard">
            <div class="player-score">
                <span>Player</span>
                <p id="playerScore">0</p>
            </div>
            <div class="vs">VS</div>
            <div class="computer-score">
                <span>Computer</span>
                <p id="computerScore">0</p>
            </div>
        </div>
        
        <canvas id="pongCanvas" width="1000" height="500"></canvas>
        
        <div class="controls">
            <p><strong>Controls:</strong></p>
            <p>🖱️ Mouse: Move left paddle vertically</p>
            <p>⬆️⬇️ Arrow Keys: Move left paddle vertically</p>
            <p>Press <strong>SPACE</strong> to start/pause the game</p>
        </div>
    </div>
    
    <script src="script.js"></script>
</body>
</html>
