# BROKEN 2D Polygon operations - I NEED HELP!

### Should be a pure Python or Java implementation with a Processing demo - but it just doesn't work :(

Based on Helder Correia's work https://github.com/helderco/univ-polyclip that is based on the paper "Efficient Clipping of Arbitrary Polygons" by Günther Greiner (greiner[at]informatik.uni-erlangen.de) and Kai Hormann (hormann[at]informatik.tu-clausthal.de), ACM Transactions on Graphics 1998;17(2):71-83. Available at: <http://www.inf.usi.ch/hormann/papers/Greiner.1998.ECO.pdf>

## Motivation

Processing does not have built in "boolean" operations for 2D polygons. Maybe this can help.

Supported operations are: union, intersection and difference.
But at this point no holes or treatment of degenerate paths...

Maybe someone will want to **port this to P5.js**, open an issue and send a PR?

### About this repo

This work was created for educational purposes by Helder Correia for a class in Graphical Computation, now Alexandre Villares would like to use this with Processing. This is the **Python branch** you might want to have a look at the **Java branch** too.

To study the algorithm, inspect the file `polygon.py`. It can be imported and used in other contexts (i.e., not Processing Python mode).

Other ideas we could pursue:

- Building a Processing library (with a `jar` file that could be imported)
- Creating an interface for use with PShapes
- Porting this to JavaScript for use with P5.js

## Processing demo

    TO BE DONE!

## The original command line demo (might be removed)

The original command line interface will not be mantained (`polyclip.py`) and may be removed later, it was provided by Helder Correia for demonstration or testing purposes, using OpenGL and equires **PyOpenGL** (version 3 as of this writing). If you have pip, install is easy:

`pip install pyopengl`

Type `polyclip.py -h` for available options. Press `Esc` to exit.


