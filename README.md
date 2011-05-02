README
======

This repository houses the source code to generate my resume. If you'd
like to use the source code to make your own resume, the following
contains information about the resources I used to make it. (Right now
I'm using a resume template from someone else but might shift over to my own eventually.)

I'm running ubuntu on my machine, but this should work on other debian
systems.

Install texlive-full (most important is the xelatex that comes along):

        sudo apt-get install texlive-full

Create a local fonts dir if you haven't already
       
       mkdir ~/.fonts

Copy the fonts in the fonts dir to your local fonts dir:

       cp fonts/* ~/.fonts

Install the fontspec package from CTAN.  This step was sorta annoying
so I'll leave it to you to figure it out.

Compile with xelatex.

      xelatex resume.tex

Should work :p
