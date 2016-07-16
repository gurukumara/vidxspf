# vidxspf

This Python Script generates [XSPF](http://www.xspf.org/) playlist of all videos nested inside a directory and its subdirectories. To read each video's time duration, [hsaudiotag](https://pypi.python.org/pypi/hsaudiotag) python package is used.

## usage

		Usage: vidxspf videodir [xspfname]

**videodir**: The root directory containing the videos that you want in the playlist

**xspfname**: The path/name of the xspf file that will be generated (optional. A default name `playlist.xspf` will be used when not provided)

Videos in the playlist are sorted by file name.


