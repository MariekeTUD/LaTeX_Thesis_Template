# LaTeX_Thesis_Template
A LaTeX template for PhD theses

For anyone struggling to write their PhD thesis using LaTeX, I am sharing my template, free to use, Thesis template (LaTeX). 
The template is compiled by the main file: main-thesis.tex. The other source files are the sections that serve as input to 
the main file, the bibliography (a BiBTeX file), and a class file containing all the layout specifications. I added comments 
in the LaTeX documents to explain the details.

Main-thesis is the main document where all other files are included. 
This is also the file that should be compiled to get the PDF.

mythesis.cls is the class file containing most of the lay-out and editing.
If you wish to make changes in the fonts, headings, table of contents,
etc. This file is the place to do that. It's sort of the preamble of the 
document.

ref-thesis.bib is your bib-file. This is where you keep all your references.

IntroP1 is an example file that you can include at the start of a new part. 
It provides a way to include a separate abstract for that part.

IntroAp can be used to separate your main document from the appendices.

Siks.tex is only useful if you are a member of the SIKS research school.
It contains a list of all the previous dissertations starting from 2009 
till early 2014. Members of SIKS must include this list at the end of their
thesis.

Use the figures folder to document all your images.

Comments are placed in the files themselves for more details. (always after a %)
