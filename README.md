# html-folder-to-epub
convert a folder of html files into an epub. The order of the html files can be selected by a provided list.
If no list is provided the files are sorted by ls.

usage: epub-convert [Options] Input Output [List]
Input can be a file or a folder filled with html files
the list can be used to choose the order of the html files in the output epub
If no list is provided the html files are ordered by the ls command
-c coverImage adds a cover image to the epub
