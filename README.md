# ASCII Bloom

A bouquet that grows and changes vases, rendered as colored ASCII text, with the renderer's code scrolling underneath.

A thin stream falls onto a single flower, which turns into a bouquet on a glass flute, then into a pink urn, a purple urn with gold handles, a striped vase, and finally an overflowing arrangement before it dissolves and loops.

Each frame of the procedurally drawn scene is downsampled to an 84-column grid. Brightness picks a glyph from a 70-character ramp, a Sobel filter swaps strong edges for `- \ | /`, and each character keeps a muted version of the color underneath. You can also load your own video; it is processed in the browser and never uploaded.

Add `#t=12` to the URL to open paused at a given second.

Single file, no build step: open `index.html`.
