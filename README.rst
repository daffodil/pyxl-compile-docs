pyxl-compile-docs
=================

This is a project specific repos to compile the docs for python-excel.org

The repos contains the script to  create the documentation
and spit them out

It uses sphinx as a build system
and it has to run twice... as there are "lookups"

eg attempting to link from libA to libC when they dont exits

It maybe uses git submodules

we shall see what happens..

End goal for the author is to have a nice cool
website at python-excel.org

and a quick links to everything..

issue one, it that they all need to "interconnect",
eg clicking on a link in utils, read from xlrd and using xlwt

So one need to interchange mode, and suddently in another "manual"
for reader Cell, not writer cell..

So to get around this we color code
eg
green = read
orange = write
purple = utils

or alike whatever,,, but we need the color shema to diff the lib..
maybe.. said pedro..

Problems
===============
The docs need to compile twice for interlinking..
Its gonna use sphinx which means not compat with doc book..
we need to style its and make it clean and cool for adopters






