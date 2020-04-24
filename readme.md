
Book files based on https://github.com/rstudio/bookdown-demo

A good reference is also http://seankross.com/2016/11/17/How-to-Start-a-Bookdown-Book.html 

###  info on how to best save the figures 
https://www.jumpingrivers.com/blog/r-knitr-markdown-png-pdf-graphics/


Build the html book with 

bookdown::render_book(input = "index.Rmd", output_format = "bookdown::gitbook")

Build the PDF with 
bookdown::render_book(input = "index.Rmd", output_format = "bookdown::pdf_book")

one can directly run the (executable) builder.sh to do that (or use that to "build the book" in RStudio) 

## the output wil be in the docs/ folder - so we can easily built a github page website from this 

TOC of the paper was 

01 Introduction
02 The benefits and advantages of using R in hydrology
03 R packages in a typical hydrological workflow
04 Challenges and solutions when using R in hydrology
05 A roadmap for the future of R in hydrology
06 Conclusions 

I think this could be a sensible start - Section 3 could probably become some chapters and we should have case studies? 


