# ASCII Bloom

A bouquet grows out of a vase, redrawn every frame as colored ASCII text.

Each frame of a procedurally drawn scene is downsampled to a character grid. Brightness picks a glyph from a 70-character ramp, a Sobel filter swaps strong edges for `- \ | /`, and each character keeps the color of the pixels under it. You can also drop in your own video; it is processed in the browser and never uploaded.

Single file, no build step: open `index.html`.
