# NukeThoseNaughtyVariables

If you code in golang and you're doing just a quick little program, the compilation is often disrupted because you have unused variables floating around.


This script comments them out automagically, leaving them easy to find later on, so you do not have to hide them with the (useless) '_ = foo' trick.


The script also repeatedly tries to compile your code until all the offending variables are removed, and barring any other (genuine) errors, it will then run your experiment and present you with a complete compiler errors list.


Happy hacking!


Ps.: Human time is the most valuable thing in the world. 
