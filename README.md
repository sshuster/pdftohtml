This is a modified version of the [pdftohtml project](http://pdftohtml.sourceforge.net/).
It includes rectangles and paths in the XML output so that we can detect lines.
Also information about images in the document.
We can split the strings or coalesce them as they are processed.

sample.pdf is generated from mkPDF.R. This illustrates rectangles and lines.
Using pdftohtml to convert this to XML gives us these elements.

See examples/
