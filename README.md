Template Title
================
[Niccolò Salvini](https://niccolosalvini.netlify.app/)
2020-05-05

<img src="img/logo.png" style="position:absolute;top:0px;right:425px;" />
<br> <br>
    <br>

## upper right logo

top:0px;right:425px

    <img src="img/logo.png" style="position:absolute;top:0px;right:425px;" />

## opts\_chunk:

  - figures are centered 12X8
  - fig.path = “img” so that all readme files are stored there
  - 3 files are created:
      - .bib file for referencesse \_ libs.R for libraries
      - utils.R for userdefined iff you have not a personal package

<!-- end list -->

    knitr::opts_chunk$set(
      collapse = TRUE,
      comment = "#>",
      fig.path = "img",
      warning = FALSE,  
      fig.width=12,
      fig.height=8,
      fig.align = "center",
      cache = FALSE       # set to TRUE to save results from last compilation
    )
    
    file.create("references.bib")
    file.create("libs.R")
    file.create("utils.R")
    # libraries are in the libs.R pac
    source(file ='libs.R')
    # reusable functions are in the utils.R file
    source(file = "utils.R")
    
    
    set.seed(27) 

## Introduction

## Deployment happens

## Description

## Visuals

## Usage

## Project status

## Next features:

## License

## References
