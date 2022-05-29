# html-folder-to-epub
Converts a folder of html files into an epub. <br />
The order of the html files can be selected by a provided list. <br />
If no list is provided the files are sorted by ls. <br />
<br />
This programm can also accepts a html file as input and converts it to epub. <br />
However it does not split the html in multible chapters in the epub. <br />
For converting a single html file to epub calibres ebook-convert might be better.<br />
<br />
usage: epub-convert [Options] Input Output [List] <br />
Input can be a file or a folder filled with html files <br />
the list can be used to choose the order of the html files in the output epub <br />
If no list is provided the html files are ordered by the ls command <br />
-c coverImage adds a cover image to the epub
