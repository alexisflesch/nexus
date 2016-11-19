# nexus.sty
This is a style file for LaTeX.

Hyperref is currently pointing to the wrong pages in the TOC for some reason: 
feel free to contact me if you figure it out!

You can load the package with two optional arguments:
- the colormap via "palette=whatever" (open nexus.sty to see a list of available colormaps)
- the length of the rectangles in the footer via "reclength=whatever"

Example:

\usepackage[palette=ebis,reclength=.08\paperwidth]{nexus}


The file "example.pdf" is, well, an example of what you can expect using this style file.
The boxes were made with xeboiboites.sty which can be found here:

http://alexisfles.ch/en/latex/boites2.html

https://github.com/alexisflesch/xeboiboites
