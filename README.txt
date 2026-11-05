AI Perception localhost website

1. Open a terminal in this folder.
2. Run: python serve.py
3. Open: http://localhost:8000

The page opens with a game title screen. Start Game fades the title out and opens the how-to-play tutorial, followed by player setup. Each player completes one 30-second round and can submit early. After the reveal, Next player returns to the splash. The sample rounds rotate between players.

Put accident_1.jpg and accident_2.jpg in the images folder, or use the in-game Load images button. Edit CONFIG near the top of index.html to replace the indicative sample data. The leaderboard lives in your browser's local storage for localhost:8000; clear site data to reset it.

The supplied Allianz logo is stored locally as allianz-logo.webp. The splash and game stage use black with Allianz blue accents. No packages or internet access are required. Press Ctrl+C in the terminal to stop the server.

The approved motor-accident title image is bundled locally as splash-accident.png and appears under a dark overlay.
