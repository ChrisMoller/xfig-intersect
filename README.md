xfig-intersect
==============

Intersect, chop, and keyboard patch to xfig.


These source files implement some enhancements to the xfig utility shipped with a
lot of Linux distros.  I wrote them four or five years ago and they provide three
new capabilities:

  snap:   The ability to select as the current point things like the intersections
          of two objects (computing the intersection of two arbitrary ellipses 
          requires solving fourth-degree polynomials in complex space), the foci 
          of ellipses, mid-points of segments, tangents and normals to ellipses,
          and so on.

  chop:   The ability to decompse objects into subordinate objects--circles into
          arcs, lines into segments, etc.

  keyboard input:  The ability to enter precise relative or absolute or coordinates
                   in either rectangular or polar notation via the keyboard.

