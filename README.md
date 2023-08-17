# html-to-pdf v2.0.0
Converts HTMLs to PDF using iText7

## Requirements:
- iText7 v8.0.0
- itext7.bouncy-castle v8.0.0
- itext7.pdfhtml v5.0.0
- System.CommandLine Prerelease

## Input:
### Commandline arguments
- ```-htmls``` (where HTML files are stored)
- ```-pdfs``` (where PDF files are stored)
- ```-names``` (list of names separated by ';' (these are also the output and input file names))
- ```-threads``` (number of threads you would like to use; default = 2)

## Example (converting test.html to test.pdf using 2 threads):
```html-to-pdf.exe -htmls "path/to/htmls" -pdfs "path/to/pdfs" -names "test"```

## Output:
- PDF with "<name>.pdf" from "<name>.html"

## Notes:
- There are several newer style features to CSS that may not be recognized by iText7 but these can be easily worked around. 
