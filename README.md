explain
=======

Explain console commands

example
------

>explain ls -la

	-l:
		 use a long listing format

		   -L, --dereference
				  when showing file information for a symbolic link, show informa-
				  tion for the file the link references rather than for  the  link
				  itself

	-a:
	, --all
				  do not ignore entries starting with .

		   -A, --almost-all
				  do not list implied . and ..


As you can see above, it's pretty dumb right now. It just gives you the 5 lines after the option.

It also sometimes fails to find option descriptions. 

If you think this could potentially be useful, feel free to work on it!
