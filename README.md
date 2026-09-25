[![Build website](https://github.com/AaronGullickson/aarongullickson.github.io/actions/workflows/build-site.yml/badge.svg)](https://github.com/AaronGullickson/aarongullickson.github.io/actions/workflows/build-site.yml)

This repository generates my professional website at <https://aarongullickson.github.io>. The website is produced as a [quarto](https://quarto.org) website. 

## Posts

Posts go in separate subdirectories of the `post` directory and the post itself is written as `index.qmd` within each subdirectory.

## Generating the CV

The CV is generated in both html and pdf format from data kept in [this google sheet](https://docs.google.com/spreadsheets/d/1scjvE65qm5YXS-JG4-CRPiLEqsz6p4y34WX6ipEct_w/edit?usp=sharing). The pdf version uses the [curVe](https://ctan.org/pkg/curve?lang=en) latex class. Additional files needed for its creation are kept in `pdf-cv`. 

## Automation

The website is built via a GH action at daily intervals or whenever a push is made.