README
======
This repository houses the source code to generate my resume. If you'd
like to use the source code to make your own resume, the following
contains information about the resources I used to make it.

I'm running ubuntu on my machine, but this should work on other debian
systems.

Install texlive-full (most important is the xetex that comes along):

        sudo apt-get install texlive-full

Create a local fonts dir if you haven't already
       
       mkdir ~/.fonts

Copy the fonts in the fonts dir to your local fonts dir:

       cp fonts/* ~/.fonts

LaTeX Stuff
===========

You need to fontspec package:

      wget http://mirror.ctan.org/macros/latex/contrib/fontspec.zip
