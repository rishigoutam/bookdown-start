--- 
title: "A Rishi Bookdown Book"
author: "Rishi Goutam"
date: "2022-04-24"
site: bookdown::bookdown_site
documentclass: book
bibliography: [book.bib]
biblio-style: apalike
link-citations: yes
github-repo: rishigoutam/bookdown-start
url: 'https\://goutam.io/'
description: "Everything you need (and nothing more) to start a bookdown book."
cover-image: memoji.png
---

# Preface {-}

This is the very first part of the book.

I am using RStudio with the `bookdown` package for creating this book. Sean Kross's [blog article](https://seankross.com/2016/11/17/How-to-Start-a-Bookdown-Book.html) was extremely helpful in getting me to understand how this works with GitHub Pages for automatic hosting.

This is a _sample_ book written in **Markdown**. You can use anything that Pandoc's Markdown supports, e.g., a math equation $a^2 + b^2 = c^2$.

The **bookdown** package can be installed from CRAN or Github:


```r
install.packages("bookdown")
```

Remember each Rmd file contains one and only one chapter, and a chapter is defined by the first-level heading `#`.

To compile this example to PDF, you need XeLaTeX. You are recommended to install TinyTeX (which includes XeLaTeX): <https://yihui.name/tinytex/>. However, I am using MacTeX, a more complete TeX package. 




