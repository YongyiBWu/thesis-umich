This is the file thesis-umich.cls.
It provides a LaTeX class that is consistent with the guidelines
provided by the Rackham Graduate School as described at
<http://www.rackham.umich.edu/downloads/oard-dissertation-format-guidelines.pdf>

This class is based on the LaTeX template provided at <http://aoss.engin.umich.edu/pages/current/dissertation-template>

The correct usage of this template is to use it as a documentclass.
The first line of the .tex file should be
```LaTeX
    \documentclass{thesis-umich}
```
if this file is in the same directory as the .tex file.  If the
two files are not in the same directory, the relative path from
the .tex file to this .cls file should be provided.  For example,
if the document is called thesis-dalle.tex and this file,
thesis-umich.cls is in a subfolder called 'tex', the command
should be
```LaTeX
    \documentclass{./tex/thesis-umich}
```
An example is distributed with this file that demonstrates all
of the features of the template.  The example is in a file called
thesis-sample.tex.


## VERSIONS:
 1988.01.01 @Jin Ji            : Initial version; reportx.sty
 1988.05.19 @Jin Ji            : Unrecorded changes
 1988.12.13 @Jin Ji            : Corrected table of contents to show
                                 "CHAPTER" and also \@makecaption
 1989.01.08 @Jin Ji            : Corrections for section headers
 1989.11.29 @?                 : Removed a spurious command
 1992.07.24 @Roque D. Oliveira : Modified \startappendices to work
                                 with the New Font Selection Scheme.
 2008.09.01 @Jason Gilbert     : Obsolete code removed for
                                 compatibility with LaTeX2e; list of
                                 abbreviations added, made copyright
                                 page cleaner, fixed appendices, 
                                 bibliography, margins, title page,
                                 frontispiece, bottom-center page
                                 numbers, two-side printing, added
                                 in-dissertation abstract and
                                 abstract that prints at the end.
 2011.04.09 @Derek Dalle       : Convert rac.sty --> thesis.umich.cls
 2019.08.30 @Umang Varma       : Remove various code that can be found
                                 in widely available packages. Address
                                 changes in Rackham guidelines.
 2021.05.04 @Zhan Jiang        : Added comments. Added codes for 
                                 Roman Chapter numbers in tex file

## Comments from Umang
This is a LaTeX template that tries (but does not guarantee) to meet the requirements of the Rackham Graduate School at the University of Michigan.

I got this copy of the template from [Derek Dalle's webpage](http://www-personal.umich.edu/~dalle/codes/thesis-umich/) and have modified it to remove various functionalities that can be found in standard LaTeX packages and added in code to address changes in the guidelines that Rackham posts.

Please make sure, of course, that you read Rackham's Handbook and formatting guidelines because they may change (or may become more strict about certain rules) over time.
