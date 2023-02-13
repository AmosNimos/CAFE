

# CAFE 

<img src="https://cdn-icons-png.flaticon.com/512/924/924514.png" width="150" 
     height="150" alt="Png Free Stock Bean Cafe Flavor Svg Png Icon Free - Coffee Beans Png Black@nicepng.com" style="filter: invert(1) brightness(200%) ;">


Convert All File Extensions - converts a file to all supported formats using pandoc and Calibre

## Synopsis

cafe [file]

## Description
The cafe script takes a file as input and converts it to all other supported formats using pandoc and Calibre. The supported formats for conversion are markdown, html, latex, odt, epub, docx (using pandoc), and pdf, mobi, azw3 (using Calibre).

The script assumes that pandoc and Calibre are installed and available in the PATH. If they are installed in a different location, you need to specify the correct path to the executable.

## Options
### file
The input file to be converted.

## Examples

cafe file.txt

Convert the file.txt to all supported formats.

## See Also
- pandoc(1)
- ebook-convert(1)
