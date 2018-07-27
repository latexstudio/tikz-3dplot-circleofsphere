### The tikz-3dplot-circleofsphere Package: Drawing Circles of a Sphere with tikz-3dplot

#### Abstract
A _circle of a sphere_ is a circle drawn on a spherical surface like, for instance, circles of latitude or longitude. 
Circles in arbitrary 3D positions can be drawn with TikZ [2] very easily using a transformed coordinate system provided 
by the `tikz-3dplot` package [1] (that is because TikZ can only draw circles on the _xy_-plane). However, automatically 
distinguishing the parts of the circle lying on the front and back sides of the sphere, e.g. by drawing a solid arc on 
the front side and a dashed one on the back side, is a somewhat tricky feat. The `tikz-3dplot-circleofsphere` package 
will perform that feat for you.

<p style="text-align:center">
  <nobr><img width="400" alt="Example 1" src="https://rawgit.com/matthias-wolff/tikz-3dplot-circleofsphere/master/images/example_frontpage1.png">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img width="400" alt="Example 1" src="https://rawgit.com/matthias-wolff/tikz-3dplot-circleofsphere/master/images/example_frontpage2.png"></nobr>
</p><p style="text-align:center">
Examples: `example_frontpage1.tex` and `example_frontpage2.tex` 
</p>

#### Package Documentation
The package documentation including examples can be found [here](https://rawgit.com/matthias-wolff/tikz-3dplot-circleofsphere/master/tikz-3dplot-circleofsphere.pdf).

#### Installation
[Download](https://rawgit.com/matthias-wolff/tikz-3dplot-circleofsphere/master/tikz-3dplot-circleofsphere.sty) the `tikz-3dplot-circleofsphere.sty` file into your project folder and include the package with 
`\usepackage{tikz-3dplot-circleofsphere}`.

#### References
1. Jeff Hein. The tikz-3dplot package. http://mirror.ctan.org/graphics/pgf/contrib/tikz-3dplot/tikz-3dplot_documentation.pdf, 2012 Retrieved July 27, 2018.
2. Till Tantau. Tikz & pgf - manual for version 3.0.1a. http://mirror.ctan.org/graphics/pgf/base/doc/pgfmanual.pdf, 2015. Retrieved July 27, 2018.
