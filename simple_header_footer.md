---
title: this is title
chrome:
    format: "A4"
    headerTemplate: '<div style="width:100%; text-align:center; border-bottom: 1pt solid #eeeeee; margin: 20px 10px 10px; font-size: 10pt"> 
    <span class=title></span></div>'
    footerTemplate: '<div style="width:100%; text-align:right; border-top: 1pt solid #eeeeee; margin:  10px 10px 20px; font-size: 8pt;"> 
    <span class=pageNumber></span> of <span class=totalPages></span></div>'
    displayHeaderFooter: true
    margin:
        top: '80px'
        bottom: '80px'
        left: '60px'
        right: '60px'
---

# Demo of PDF footer header


## page 1

- text 1 

- text 1 

- text 1[^1]

[^1]: this is demo text 

`markdown分页` :

<div STYLE="page-break-after: always;"></div>

## page 2

- text 2

- text 2

- text 2


<div STYLE="page-break-after: always;"></div>

## page 3

- text 3

- text 3



