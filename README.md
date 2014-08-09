# bison.py

## Intro

'''WARNING''': this document assumes the reader has
significant experience with Bison. Bison
version 3.0 or later is required.
Experience with the language of interest (e.g. python)
is also required.

The goal of this project is allow the use of ''Bison'' to
generate parsers for a variety of languages.
The Gnu Bison system
(http://www.gnu.org/software/bison/) is an extremely
powerful compiler generator system.  In its recent
incarnations, it has been extended from its original C
orientations to support the generation of additional parsers
in C++ and Java.

This project extends that support to new languages including:
* Python

Ideally, the languages supported here would be included in
the standard Bison distribution. That would entail, however,
that the Bison development team have experience in those
languages and the resources to maintain the parser
skeletons. Neither of these is true, so this project
provides support independent of the Bison project.

Interesting per-language features:
* Python -- principled support for SAX parsing in python. See
https://github.com/Unidata/yax.git for a discussion of the
''yax'' project.

