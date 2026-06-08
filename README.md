# Money Money Money synced talk player: cleaned deck video mode

Updates:
- Removed caption and outro buttons.
- Captions remain visible as dynamic overlay when cues are available.
- Removed outro behavior.
- Mobile UI is simplified.
- Mobile hides slide chapter navigation.
- Mobile has fixed Previous / Next controls at the bottom.
- Config updated to the revised 29-slide mapping.

Expected paths:
- `media/talk.mp4`
- `media/slides.mp4`
- `media/2.png` through `media/30.png` for desktop chapter thumbnails
- `data/captions.en.vtt`

Run locally:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.
