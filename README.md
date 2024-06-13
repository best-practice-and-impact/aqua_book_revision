# aqua_book_revision

The [AQuA Book](https://www.gov.uk/government/publications/the-aqua-book-guidance-on-producing-quality-analysis-for-government) is a good practice guide for those working with analysis and analytical models in the UK government. This project is the main repository for the working draft of the next revision of the AQUA Book, which will be provided as an HTML website.

This version of the AQuA book is a preliminary ALPHA draft.  It is still in development, and we are still working to ensure that it meets user needs. 

**The draft currently has no official status**. It is a work in progress and is subject to further revision and reconfiguration (possibly substantial change) before it is finalised. 

This repository contains these folders:  
 
1) **_book**: This directory stores the rendered website and PDF outputs created by Quarto when the .qmd files in the main folder are processed. This website is rendered automatically to Github.io. You should not need to manually edit any of the files in **_book**.

The main folder contains the following key files:

**_quarto.yml** - YAML file containing configuration information for the Quarto engine to render the website. Includes page structure and source files.    
**.gitignore** - List of files not to upload to git repository.   
**LICENSE** - licensing for re-use of the repository and its content. This repository is licensed under the [MIT license](https://opensource.org/license/MIT) in line with [Government Digital Service](https://gds-way.digital.cabinet-office.gov.uk/manuals/licensing.html) recommendations. The content of the AQuA Book itself is licensed under the [Open Government License](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/) in line with GDS guidance about how to license documentation.    
**aqua_style.css** - HTML style sheet which sets up table rendering formatting. Edit this to change the way the site renders tables and other non text content to HTML.       
**README.md** - Repository README file (this document) written in markdown format.    
**index.qmd** - Main index to the Quarto book.    
**intro.qmd** - AQuA Chapter One - introduction.    
**definitions_and_key_concepts.qmd** - AQuA Chapter Two - definitions and key concepts.    
**references.bib** - Bibliography in Quarto supported bib format.    
**references.qmd** - List of references.    
**summary.qmd** - Document summary.    

# Working with the project code

We recommend using [Visual Studio Code](https://code.visualstudio.com/) to work with this project. Open the code workspace in VS Code to load the project. To render the website, open any of the .qmd documents and select the Preview button. Edits to qmd files will only be reflected in the project website after you have re-rendered using Preview.

# Software requirements  
Python 3.8 or later    
[Visual Studio Code](https://code.visualstudio.com/) with the Quarto, Python and autopep8 extensions    
[Quarto](https://quarto.org/docs/get-started/)

# Useful links
HM Government [AQuA book analytical quality assurance manual](https://www.gov.uk/government/publications/the-aqua-book-guidance-on-producing-quality-analysis-for-government). HM Government.

HM Government Analysis Function. (2020). [Quality assurance of code for analysis and research](https://best-practice-and-impact.github.io/qa-of-code-guidance/ ). Office for National Statistics, Quality and Improvement division.

Quarto.org [Quarto books guide](https://quarto.org/docs/books/)