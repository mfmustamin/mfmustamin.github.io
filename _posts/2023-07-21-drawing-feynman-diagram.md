---
layout: post
title: "Drawing Feynman diagram"
date: 2023-07-21
---
<p>
Feynman diagrams are collection of lines that representation particle interaction in a spacetime. It is fun to write them down by pencil on the paper. 
The need to share our work with others makes translating the diagrams into digital versions essential. 
Accordingly, I personally would like to address two packages: JaxoDraw and feynMF.
</p>
<h2> JaxoDraw </h2>
<p>
The packages is based on Java with full graphical user interface (GUI). Resulted diagrams can be converted into a postscript format, suitable for publication.
The powerfull WYSIWYG fashion make it relatively easy to naviagte the tools to create the graph we are interested in. Publication of this work can be found in 
Ref. [1], from which detail of how to use the package can be found.
</p>
<h2> feynMF </h2>
<p>
The feynMF package generates Feynman diagrams in a pure LATEX environment. Users need to define components of a diagram according to the feynMF definition.
Output diagram follows the format we are interested in. Personally I like to compile the output as a separated document, to be called later as a figure in
a LATEX document. I recommend a compact documentation in Ref. [2] to generate diagrams you want.
</p>
<ul>
<li>[1] D. Binosi and L. Theussl, 2004. "JaxoDraw: A graphical user interface for drawing Feynman diagrams", Comput.Phys.Commun. 161 (2004) 76-86. </li>
<li>[2] T. Yamanaka, 2006. "feynMP / feynMF Examples". </li>
</ul>
