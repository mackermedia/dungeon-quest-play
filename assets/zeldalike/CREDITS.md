# assets/zeldalike

- `overworld.png`, `cave.png`, `inner.png`, `objects.png`, `log.png`, `npc_test.png`, `font.png`, `hero-red.png`: "Zelda-like tilesets and sprites" by ArMM1998, CC0. https://opengameart.org/content/zelda-like-tilesets-and-sprites
- `hero-green.png`, `hero-steel.png`, `hero-blue.png`: palette swaps of `hero-red.png` (shirt colors only), made here.
- `spider.png`: from "16x16 animated critters" by HelplessIsland (patvanmackelberg), CC0, background keyed out. https://opengameart.org/content/16x16-animated-critters

Frame layouts:
- hero-*.png is 272x256. Walk frames are 16x32 (grid 17 cols): rows 0..3 = down, left, up, right; frames 0..3 of each row walk. Attack frames are 32x32 (grid 8 cols): rows 4..7 (in 32px rows) = down, up, right, left; frames 0..3.
- log.png is 192x128, 32x32 frames, 6 cols x 4 rows: rows = down, right, up, left (verify); frames 0..3 walk, 4..5 sleep.
- spider.png is 64x64, 16x16 frames, 4 rows x 4 frames.
