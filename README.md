xxpaper
=======

Installation dependency:

	     PsFile: http://www.seehuhn.de/pages/psfile
	     PyVer: https://github.com/clearclaw/pyver

Unfortunately PsFile is not available via setuptools and the cheese
factory.  I'll get around to putting PyVer in the Cheese Shop at some
point.

XXPaper generates Postscript files representing charters, privates,
shares, station markers, trains and (linear) stock markets (2D stock
markets coming later) as defined by a configuration passed on the
command line.  All art is made using a format which is friendly to
die-cutting.  Default component sizes for shares, privates and
trains fit the ~$20 test die provided with Ellison Prestige Pro die
cutters.  Cut-lines are provided in the "outline" files for hand
cutting.  Alignment lines are provided for all files that allow
accurate die placement when using a die cutter.

The resulting Postscript files can be converted to PDFs using the
`ps2pdf` utility that comes with Ghostscript.

A sample configuration file can be found in the "samples" directory
of the source tree.  The sample file produces privates, shares and
train art sized suitably for the test die that comes with an Ellison
Pro die cutter.

-- JCL
