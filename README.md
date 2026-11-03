# Chess Coach

Enter your friend's moves, get the engine's best reply. Runs fully in the browser (Stockfish + chess.js), no server.

## Put it live on GitHub Pages
1. Create a repo (e.g. `chess-coach`) and upload everything in this folder, keeping the `lib/` folder.
2. Repo → Settings → Pages → Source: "Deploy from a branch" → `main` / root → Save.
3. After a minute it's live at `https://<your-username>.github.io/chess-coach/`.

Test locally first: `python3 -m http.server` in this folder, then open http://localhost:8000. (Double-clicking index.html shows the board but the engine can't start from a file.)
