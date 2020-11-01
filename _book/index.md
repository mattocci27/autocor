---
knitr: bookdown::render_book
title: "Autocorrelaion and likelihood methods"
author: "Masatoshi Katabuchi"
date: "2020-11-01"
description: "This book is a practical introduction for how to
manage autocorrelation using R."
url: 'https\://dcl-prog.stanford.edu'
github-repo: dcl-docs/prog
site: bookdown::bookdown_site
documentclass: book
#bibliography: references.bib
link-citations: true
---

# Welcome {-}

This book is a practical introduction for modeling autocorrelaition using R.

## An evolving book {-}

This book is not intended to be static. Starting in April 2019, we use this book to teach functional programming in the Stanford [Data Challenge Lab](https://datalab.stanford.edu/challenge-lab) (DCL) course. The DCL functions as a testing ground for educational materials, as our students give us routine feedback on what they read and do in the course. We use this feedback to constantly improve our materials, including this book. The [source for the book](https://github.com/cl-docs/prog) is also available on GitHub where we welcome suggestions for improvements.

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/). d



## Objective {}

- A quick review for likelihood methods
- Understanding what autocorrelation is  
- Getting an idea for handling autocorrelation

```
system.time(bookdown::render_book("index.Rmd"))
```

