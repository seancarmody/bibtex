# BibTeX reference list

Inspired by [this post](http://markelikalderon.com/2008/06/17/gitting-bibtex/)
I have decided to start managing my BibTeX reference file(s) using git,
keeping a public copy on github.

I manage by BibTeX files using [BibDesk][bibdesk] which explains some of 
the extra crufty fields (a good example is the Bdsk-File-1 field), which you
can safely ignore.

So far, the contents have an emphasis on extreme value statistics
and operational risk, which reflects a consulting project I am
working on. I will be adding other files, but have not yet decided
whether to keep them in one big .bib file or to have them separated
by subject.

PDF versions of many of the papers are in the same directory here locally, so I have put *.pdf in the .gitignore file so they don't all end up on github!

Note: because I use this repo across Windows and OSX machines, I have the git autocrlf option set to true. This can be done with the following command:

> git config --global core.autocrlf true

Sean Carmody.

[bibdesk]: http://bibdesk.sourceforge.net/ BibDesk
