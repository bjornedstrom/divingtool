divingtool
==========

This program is a homeage to the wednesday of November 17:th 2010 when
I become a diving functionary by mistake.

Calculate points
----------------

`divingtool` can calculate points given a DoD (degree of difficulty)
and either 5 or 7 points from judges. The points are comma
separated. The DoD and points are separated by a `=`. Sample usage:

`$ ./divingtool -c 1.9=5,5,5,6,7.5`

This will print 30.4.

Decoding dive numbers
---------------------

`divingtool` can also decode dive numbers, and print them in human
readable form. Sample usage:

`$ ./divingtool --decode 6243A`

This will print "armstand back double somersault 1½ twists
(straight)".
