## Bitsy Image Converter

[Direct link](https://ker0chan.github.io/bitsy-image-converter/)

This is a hacky, unoptimized and largely untested tool to easily import images into Bitsy.
It renders an image into a 128x128 canvas, dithers it and cuts it into 8x8 pieces, then exported as tiles.
Duplicate tiles in a single image are re-used.

### Instructions
* Drop an image on the canvas;
* Adjust the Brightness and Contrast;
* Set the colors to the Background and Tile colors you chose in Bitsy;
* Invert the colors if needed;
* Copy the result and paste it in Bitsy;

### Paste it WHERE in Bitsy?
There's a panel called "Game Data" in the Bitsy editor. In it, you'll find the data for your palettes, rooms, tiles, sprites and more.
Paste it between the last room and the first tile.

### Can I import multiple images?
Yes, but,
* You'll have to change the Room identifier (`ROOM 0`) manually;
* Duplicate tiles across different images will be ignored (you might end up with multiple identical tiles, sorry)

### Can I change the palette?
Yep. Right under the Room definition (the first paragraph in the output), you'll find the line `PAL 0`. You can change that to another palette id.

### Can I import an animated image?
### Can I use animated tiles?
### Can I export my image as a set of sprites, instead of tiles?
Not yet.
