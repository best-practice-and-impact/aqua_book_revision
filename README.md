# aqua_book_revision

The [AQuA Book](https://www.gov.uk/government/publications/the-aqua-book-guidance-on-producing-quality-analysis-for-government) is a good practice guide for those working with analysis and analytical models in the UK government. This project is the main repository for the working draft of the next revision of the AQUA Book, which will be provided as an HTML website.

This version of the AQuA book is a preliminary ALPHA draft.  It is still in development, and we are still working to ensure that it meets user needs. 

**The draft currently has no official status**. It is a work in progress and is subject to further revision and reconfiguration (possibly substantial change) before it is finalised. 

This repository contains these folders:  
 
1) **_docs**: This directory stores the rendered website and PDF outputs created by Quarto when the .qmd files in the main folder are processed. This website is rendered automatically to Github.io when the **_docs** folder is updated. You should not need to manually edit any of the files in **_docs**.

The main folder contains the following key files:

**_quarto.yml** - YAML file containing configuration information for the Quarto engine to render the website. Includes page structure and source files.    
**.gitignore** - List of files not to upload to git repository.
**.nojekyll** - Tells Github not to use jekyll when auto-rendering the website.
**LICENSE** - licensing for re-use of the repository and its content. This repository is licensed under the [MIT license](https://opensource.org/license/MIT) in line with [Government Digital Service](https://gds-way.digital.cabinet-office.gov.uk/manuals/licensing.html) recommendations. The content of the AQuA Book itself is licensed under the [Open Government License](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/) in line with GDS guidance about how to license documentation.    
**aqua_style.css** - HTML style sheet which sets up table rendering formatting. Edit this to change the way the site renders tables and other non text content to HTML.       
**README.md** - Repository README file (this document) written in markdown format.
**forward.qmd** - Definitions of Functional Standard terms ("shall", "should" etc.)  
**index.qmd** - Start page for the Quarto book (required by Quarto). Includes the Preface and Acknowledgements.    
**intro.qmd** - AQuA Chapter 1 - introduction.    
**definitions_and_key_concepts.qmd** - AQuA Chapter 2 - definitions and key concepts.
**proportionality.qmd** - AQuA Chapter 3 - Proportionality.
**quality_assurance_culture.qmd** - AQuA Chapter 4 - Quality assurance culture.
**analytical_lifecycle.qmd** - AQUA Chapter 5 - Overview of the analytical lifecycle.
**engagement_and_scoping.qmd** - AQuA Chapter 6 - Engagement and Scoping.
**design.qmd** - AQuA Chapter 7 - Design.
**analysis.qmd** - AQuA Chapter 8 - Analysis.
**delivery_and_communication.qmd** - AQuA Chapter 9 - delivery and communication.
**additional_resources.qmd** - AQuA Chapter 10 - Additional resources.
**accessibility_statement.qmd** - Standard accessibility statement.    
**references.bib** - Bibliography in Quarto supported bib format.    
**references.qmd** - List of references.    
**JPEG images** - JPEG files are diagrams rendered in the Quarto book.

# Working with the project code

We recommend using [Visual Studio Code](https://code.visualstudio.com/) to work with this project. Open the code workspace in VS Code to load the project. To render the website, open any of the .qmd documents and select the Preview button, or run `quarto preview` (which will generate a local preview site to look at) or `quarto render` from the terminal. Edits to qmd files will only be reflected in the project website after you have re-rendered and pushed the updated repo to Github.

When adding issues to the repo, give the issue a name starting with the first word of the chapter heading to which it refers (unless it is a multi-chapter issue)

# Software requirements     
[Visual Studio Code](https://code.visualstudio.com/) with the [Quarto VSCode extension](https://marketplace.visualstudio.com/items?itemName=quarto.quarto).   
[Quarto](https://quarto.org/docs/get-started/)

# Useful links
HM Government [AQuA book analytical quality assurance manual](https://www.gov.uk/government/publications/the-aqua-book-guidance-on-producing-quality-analysis-for-government). HM Government.

HM Government [Functional Standard GovS 010: Analysis](https://www.gov.uk/government/publications/government-analysis-functional-standard--2)

HM Government Analysis Function. (2020). [Quality assurance of code for analysis and research](https://best-practice-and-impact.github.io/qa-of-code-guidance/ ). Office for National Statistics, Quality and Improvement division.

Quarto.org [Quarto books guide](https://quarto.org/docs/books/)
