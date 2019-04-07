# oxo
Oxo.sty - Latex Style File for Oxocard drawings using tikz\
This Latex Style File is still under development.\
The version provided is a first functioning one, which has still plenty of room for extensions.\
It provides functions to easily draw 8x8 rgb color matrices using tikz.\
This can be very helpful, when writing documents about the oxocard, such as lecture notes or worksheets.

Lualatex is required.\
Short codes for colors: r=red, y=yellow, b=blue, g=green, w=white, bl=black, o=orange, p=purple, c=cyan, m=magenta\
Colors are provided to the style file using comma separated short codes starting at the top left linewise to the right bottom.\
Not yet implemented: Provide Colors using RGB.\
The state of the six button can also be provided to the function \texttt{oxofull}. To do this, add a second argument and provide 6 comma separated binaries, where 1 stands for pressed (appers red in Picture) and 0 for unpressed (no fill).

Examples can be found in the Readme PDF.
