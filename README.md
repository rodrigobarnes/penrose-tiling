# README

This is a quick and dirty project to generate SVG images for [Penrose tile](https://en.wikipedia.org/wiki/Penrose_tiling) as a precursor to cutting out the shapes via [CNC router](https://en.wikipedia.org/wiki/CNC_router).

[Kites and Darts](https://en.wikipedia.org/wiki/Penrose_tiling#/media/File:Kite_Dart.svg) are complementary shapes that tile in nice ways.

Just open the file 'svg.html' in a modern browser to see the shapes.

The overall workflow is:

1. Generate SVG of Kite and Dart shapes in HTML using Javascript.
2. Save the SVG code into another file e.g [`tile.svg`](./tile.svg) - use inspect element
3. Load image as template into a CNC control programme like [Easel](https://easel.inventables.com)
4. Cut/paste as appropriate in that tool to get the shapes needed.

