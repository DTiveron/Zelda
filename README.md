# DHS SHIELD Lost Forest — GitHub Pages

This folder is ready to host as a static GitHub Pages site. No PHP, build tools, frameworks, images, or audio files are required.

## Change the clue

Open `config.js` and edit only this line:

```js
finalClue: "YOUR NEXT CLUE GOES HERE",
```

You can also change the headings there.

The current puzzle solution is:

**North → West → South → West**

## Test locally

You can double-click `index.html` and it should run in a browser. Keyboard controls are Arrow Keys or WASD. Phones/tablets get an on-screen D-pad.

## Publish with GitHub Pages

1. Create a new GitHub repository, for example `dhs-lost-forest`.
2. Upload `index.html` and `config.js` to the top level of the repository.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then save.
6. GitHub will provide the published URL. It normally looks like:
   `https://YOUR-USERNAME.github.io/dhs-lost-forest/`
7. Use that URL directly or turn it into a QR code for the race.

## Why this version is different from the older source

The older page relied on separate Zelda image/audio files, an old jQuery dependency, and a PHP answer form. GitHub Pages is static hosting, so this version keeps the navigation mechanic but is completely self-contained and reveals your custom clue directly after the correct route.


## Zelda-style revision
This version makes the playable hero and forest much more immediately recognizable as a classic 8-bit fantasy-adventure homage: green pointed cap/tunic, blond hair, shield, sword, LIFE hearts, rupee-style HUD, Triforce-like marker, and NES-like forest tiles. No external image files are required; the art is drawn directly by the canvas code.
