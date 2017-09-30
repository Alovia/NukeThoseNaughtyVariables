# NukeThoseNaughtyVariables
Why do the legwork if you can have a shell script take care of things?

If you code in golang and you're doing just a quick little program,
the compilation is often disrupted because you have unused variables
floating around.  

This script comments them out, so you do not have to hide them with 
the '_ = foo' trick, and, repeatedly tries to compile until they all
are gone, and barring any other (genuine) errors, runs your experiment.

Happy hacking!
