!!! IMPORTANT !!!
-----------------

**!!! MOVED TO: http://github.com/akavel/polyclip-go !!!** 

As of Go version "Go 1 RC1" (March 2012), projects are not allowed to have names ending ".go", so this project was moved to: http://github.com/akavel/polyclip-go - please update your bookmarks.

Your imports shall need only small change - from:

    "github.com/akavel/polyclip.go" // wrong now

to:

    "github.com/akavel/polyclip-go" // OK!

About
-----

Library polyclip.go is a pure Go, MIT-licensed implementation of an [algorithm for Boolean operations on 2D polygons] [fmartin] (invented by F. Martínez, A.J. Rueda, F.R. Feito) -- that is, for calculation of polygon intersection, union, difference and xor.

The original paper describes the algorithm as performing in time _O((n+k) log n)_, where _n_ is number of all edges of all polygons in operation, and _k_ is number of intersections of all polygon edges.

  [fmartin]: http://wwwdi.ujaen.es/~fmartin/bool_op.html

  ![](http://img684.imageshack.us/img684/5296/drawqk.png "Polygons intersection example, calculated using polyclip.go")

Example
-------

PLEASE SEE NEW LOCATION: http://github.com/akavel/polyclip-go
