# my-ai-project

## Metro Rush

A mobile-friendly, subway-style endless runner built with HTML, CSS, and vanilla JavaScript.

[Play the private hosted game](https://metro-rush-giacomo.escp-busines-5695.chatgpt.site) (ChatGPT sign-in required).

### Run locally

No build step or package installation is required. Open `index.html` in a browser, or serve this directory:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

### Controls

| Action | Keyboard | Phone |
| --- | --- | --- |
| Change lane | Left / Right arrows or A / D | Swipe left / right |
| Jump | Up arrow or W | Swipe up |
| Slide | Down arrow or S | Swipe down |
| Boost | Space after collecting 15 coins | Tap the lightning button |
| Pause / resume | P or Escape | Tap pause / resume |

### Features

- Three lanes with trains, barriers, and overhead obstacles
- Coin trails, shields, coin magnets, and a rush boost
- Increasing speed and endless obstacle generation
- High scores and total coins saved in browser local storage
- Optional synthesized sound effects
- Touch buttons as an alternative to swipes

`index.html` contains the responsive interface and styling; `game.js` contains the canvas renderer and game logic. Fonts load from Google Fonts, with system fallbacks.

### Publish with GitHub Pages

The static game is ready to serve directly from the repository root. `.nojekyll` disables Jekyll processing.

1. Open this repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then click **Save**.
4. Wait for GitHub to finish the Pages deployment. The Pages settings will show the live game URL.

Future updates pushed to `main` will publish automatically.
