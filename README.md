Calzone
=======

## Better typesetting for EPUB (and HTML)

The aim of Calzone is to create a Javascript library which can be
dropped into EPUB files to greatly improve the typographic experience of
ebook readers. Most current e-reader software does not support lovely
typography. In particular, there is little if any support for
hyphenation, paragraph-level justification, keep and break controls, and
other typographic necessities in a reflowing ebook environment.
(See http://johndberry.com/blog/2012/03/06/what-is-needed/ for a full
list of gripes.)

But the EPUB standard, in particular EPUB3, grudging allows for readers
to support the execution of JavaScript, and many e-reader software
already executes inline Javascript in EPUB files. Which means that the
programmer already has a lot of control over what gets displayed on the
page.

Borrowing (extremely) heavily from http://www.bramstein.com/projects/typeset 
and http://search.cpan.org/perldoc?Text::Hyphen , Calzone fills in the 
gaps that reader software leaves behind, fiddling with the placement of
words and paragraphs on the page to make e-books prettier.

There's nothing particularly EPUB-specific about Calzone, so if you like
you can use it to improve the typography of ordinary web pages too. I
wouldn't, though.

See http://simoncozens.github.com/calzone/ for a rigged demo.
