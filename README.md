Get Going Grid
==============

__A lightweight, mobile first grid.__

_If you want a nestable grid, use this: https://github.com/joshnh/lightweight-nestable-grid_

To use the grid you will need a parent element with a class of `grid`. Columns are then implemented by using a class equal to the desired percentage width (`grid__col--{width}`).

Also, and this is _important_, due to the use of inline-block you will need to comment out the white space between the column elements. This is the most consistent way to deal with this space.

The available widths are:

| Width  | Class             |
| ------ | ----------------  |
| 20%    | `.grid__col--20`  |
| 25%    | `.grid__col--25`  |
| 30%    | `.grid__col--30`  |
| 33.3%  | `.grid__col--33`  |
| 40%    | `.grid__col--40`  |
| 50%    | `.grid__col--50`  |
| 60%    | `.grid__col--60`  |
| 66.6%  | `.grid__col--66`  |
| 70%    | `.grid__col--70`  |
| 75%    | `.grid__col--75`  |
| 80%    | `.grid__col--80`  |
| 100%   | `.grid__col--100` |

Live demo: http://jsfiddle.net/joshnh/fcKcW/

_Note: make sure that you are using the `grid` and `grid__col--{width}` classes on block level elements._
