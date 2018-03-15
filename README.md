# webtoon-viewer
## Motivation
Default image viewer on ubuntu is really bad at viewing images that are really tall and narrow.
`webtoon-viewer` alleviates this problem by stitching the images together and then rendering it on a webpage
at 50% page width and centered.

## Usage
Works with jpgs with numbered filenaming scheme padded with 0's. So like:
`00.jpg` or `99.jpg`. Set `n` in the html file as the last image file you'd like to stitch.
