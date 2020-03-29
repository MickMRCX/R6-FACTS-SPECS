# README

This repository contains the specifications for the 3 projects I plan to work around R6-FACTS.  

Those specifications are written in AsciiDoc to keep track of evolutions.  

## Convert in PDF
To do the convertion we use AsciiDoctor-pdf.  
:warning: Firstly you need to install Ruby on your computer.  

`gem install asciidoctor-pdf --pre`

Next you should go to the project's root and update bundles with this command :   
`bundle --path=.bundle/gems`


Then you can generate the PDF with this command :     
`asciidoctor-pdf pages/index.adoc`

The generated file will be in pages/index.pdf  



-----
AsciiDoc formating tutorial : https://asciidoctor.org/docs/asciidoc-writers-guide/

-----
Asciidoctor-pdf installation tuturial : https://asciidoctor.org/docs/asciidoctor-pdf/