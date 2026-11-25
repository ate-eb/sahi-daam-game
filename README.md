# Sahi Daam: Beat the model (standalone game)

A static website, no Python or server needed. It is just `index.html` and `cars.js` (the cars, with the real asking price and the model's guess for each).

How it plays: 10 random real listings per round. The player guesses each asking price, the model's guess is revealed, and each side scores up to 100 points per car (minus 2 points for every 1% missed). Best score and rounds won are saved in the player's browser.

## Try it on your PC
Keep `index.html` and `cars.js` in the same folder and double-click `index.html`.

## Put it online (free)
Any of these works because it is only static files:
- **Vercel:** install the CLI (`npm i -g vercel`), open a terminal in this folder, run `vercel`, press Enter through the questions. Or drag the folder onto vercel.com/new.
- **Netlify:** go to app.netlify.com/drop and drag this folder in.
- **GitHub Pages:** push the two files to a repo, then Settings > Pages > deploy from the main branch.

## Before you make money from it
- **The data:** the cars come from PakWheels listings. Check PakWheels' terms and the dataset's license on Kaggle before charging for anything built on it. The game shows only specs and prices (no photos, text or links), but that does not by itself make commercial use allowed. If the license does not allow it, collect your own data or ask PakWheels for permission.
- **Your partner:** the project was made with Waleed, so agree with him on ownership and revenue. Also check your university's rules on coursework projects.
- **Honesty:** the footer says these are asking prices and the model is an estimate. Keep that.
- **Data stays in sync:** `cars.js` is a snapshot from September 2026. For a real product you would refresh it with new listings and retrain.
