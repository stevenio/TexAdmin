TexAdmin
========

LaTex admin commands


[Mac OS X]
URL: http://stackoverflow.com/questions/1390828/how-do-i-install-a-latex-sty-file-on-osx

In Mac OS X (Snow Leopard 10.6.7) put your .sty file in

/usr/local/texlive/2011/texmf-dist/tex/latex/base/
or
/opt/local/share/texmf-texlive/tex/latex/base/

Then, run texhash command. Don't forget to stay as a root user (like sudo -s )
