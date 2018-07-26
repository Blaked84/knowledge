## Crop all pages in a pdf

Useful to send a pdf book with strange formating to a Kindle

* Open pfd in Preview
* Select all pages in the thumbnail side bar
* Use the crop tool

[Source ](http://www.techademic.co/blog/2015/8/cropping-multiple-pdf-pages-in-previewapp)

## Compress PDF

```bash
gs -sDEVICE=pdfwrite -dCompatibilityLevel=1.4 -dPDFSETTINGS=/printer -dNOPAUSE -dQUIET -dBATCH -sOutputFile=output.pdf input.pdf
````