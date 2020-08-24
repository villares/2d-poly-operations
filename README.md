# 2D Polygon operations with pure Python or Java (and a Processing demo)

Based on Helder Correia's work https://github.com/helderco/univ-polyclip
Based on the paper "Efficient Clipping of Arbitrary Polygons" by Günther Greiner (greiner[at]informatik.uni-erlangen.de) and Kai Hormann (hormann[at]informatik.tu-clausthal.de), ACM Transactions on Graphics 1998;17(2):71-83.

Available at: <http://www.inf.usi.ch/hormann/papers/Greiner.1998.ECO.pdf>

## Motivation

Processing does not have built in "boolean" operations for 2D polygons. Maybe this can help.

Supported operations are: union, intersection and difference.

### About this repo

This is the **Python branch** you might want to have a look at the **Java branch**

To study the algorithm, inspect the file `polygon.py`. It can be imported and used in other contexts (i.e., not Processing Python mode).

### Import

```python
> import polygon
> help(polygon)
> from polygon import *
```
## The original command line demo (might be removed)

The original command line interface will not be mantained (`polyclip.py`) and may be removed later, it was provided by Helder Correia for demonstration or testing purposes, using OpenGL and equires **PyOpenGL** (version 3 as of this writing). If you have pip, install is easy:

`pip install pyopengl`

Type `polyclip.py -h` for available options. Press `Esc` to exit.


