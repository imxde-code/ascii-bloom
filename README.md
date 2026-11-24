# ASCII Tulip

A tulip grows out of a pot and blooms, rendered as colored ASCII text in a 16:9 frame, with the renderer's code scrolling alongside.

Water falls onto the soil, a sprout pushes up, the leaves unfold, a green bud turns red, and the petals open before the camera eases in and the picture dissolves and loops.

Each frame of the procedurally drawn scene is downsampled to a character grid. Brightness picks a glyph from a 70-character ramp, a Sobel filter swaps strong edges for `- \ | /`, and each character keeps a muted version of the color underneath.

- **Hide the code:** the tab on the panel's edge, the "Hide code" button or the `C` key slides it away and widens the screen to the full frame.
- **Your own video:** load one and it is converted the same way, in the browser, never uploaded.
- **Jump to a moment:** add `#t=12` to the URL to open paused at that second.

Single file, no build step: open `index.html`.
