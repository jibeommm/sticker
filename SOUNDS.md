# Animal Sound Assets

Place MP3 sound files here for each animal:

| File | Animal | Description |
|------|--------|-------------|
| `cat.mp3` | 고양이 | Meow |
| `dog.mp3` | 강아지 | Bark / Woof |
| `rabbit.mp3` | 토끼 | Soft squeak |
| `bear.mp3` | 곰 | Low growl |

## Usage in the app

In `src/data/animals.js`, update each animal's `soundUri`:

```js
// For local bundled assets (recommended):
soundUri: require('../../assets/sounds/cat.mp3'),

// For remote URL:
soundUri: 'https://example.com/cat.mp3',
```

Then copy the MP3 files into the `-Paw` repo under `assets/sounds/`.

## Free sound resources

- [Pixabay](https://pixabay.com/sound-effects/) — free, no attribution required
- [Freesound](https://freesound.org/) — Creative Commons
- [Zapsplat](https://www.zapsplat.com/) — free with account
