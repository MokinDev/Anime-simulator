# Anime Simulator

A single-file HTML "Anime Simulator" that lets you customize a simple anime-style character and scene:
- Animated day/night sky gradient
- Parallax clouds and drifting particles
- Character customization: hair styles (short, long, ponytail, bangs), outfit styles (T-shirt, hoodie, dress)
- Accessories: glasses and hat with color picker
- Export current scene to PNG

## Files
- `anime-simulator.html` — the complete single-file simulator (open in your browser).
- `LICENSE` — MIT license.

## Usage (locally)
1. Save `anime-simulator.html` in a folder and open it with a modern browser (Chrome, Firefox, Edge).
2. Use the controls on the left to change sky, hair, outfit, accessories.
3. Click "Apply" to update the character, or "Randomize" to generate a look.
4. Click "Download PNG" or "Preview Screenshot" to export the scene.

## Create a GitHub repository and push (recommended)
From the folder containing the files, you can create the repository and push using either the GitHub website or CLI.

Option A — using the GitHub website
1. Go to https://github.com/new and create a new repository named `anime-simulator` under `MokinDev`.
2. Initialize repository (no files necessary because you'll push an existing local repo).
3. Follow the "…or push an existing repository from the command line" instructions GitHub shows after creation.

Option B — using the GitHub CLI (recommended)
1. Install Git and the GitHub CLI (`gh`) and authenticate (`gh auth login`).
2. Run these commands from the project folder:
```bash
git init
git add anime-simulator.html LICENSE README.md
git commit -m "Initial commit — anime simulator"
gh repo create MokinDev/anime-simulator --public --source=. --remote=origin --push
```

Option C — using git + manual remote
1. Create repository on GitHub (https://github.com/new) named `anime-simulator` under `MokinDev`.
2. Then in your local folder:
```bash
git init
git add .
git commit -m "Initial commit — anime simulator"
git branch -M main
git remote add origin git@github.com:MokinDev/anime-simulator.git
git push -u origin main
```

## GitHub Pages (optional)
If you want a hosted demo:
1. Go to repository Settings → Pages, select `main` branch and `/ (root)` folder, then Save.
2. The page will be available at `https://MokinDev.github.io/anime-simulator/` (may take a minute).

## License
This project is released under the MIT license. See `LICENSE`.

Enjoy! If you want, I can:
- Create extra presets,
- Add drag-and-drop accessory placement,
- Add GIF export,
- Or prepare a ready-to-import repository (if you give me permission to create it for you).
