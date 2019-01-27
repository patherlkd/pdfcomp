# pdfcomp
A very simple bash script that shrinks pdf document sizes without affecting quality (too much)

For example
```
$ pdfcomp example_pdf.pdf example_pdf_compressed.pdf
```
leads to:

```
Shrinking pdf example_pdf.pdf into example_pdf_compressed.pdf
Original file size:
44M	example_pdf.pdf
GPL Ghostscript 9.07: Set UseCIEColor for UseDeviceIndependentColor to work properly.
Compressed file size:
20M	example_pdf_compressed.pdf
```
