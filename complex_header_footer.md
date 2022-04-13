---
title: this is title 

chrome:
    format: "A4"
    headerTemplate: '<div style="position: relative; width:100%; text-align:center; border-bottom: 1pt solid #eeeeee; margin: 30px 0px 10px; font-size: 10pt"></span>
    
    <div style="position: absolute; width:100%; text-align: center; bottom: 5px;"><span class=title></div>
    
    <div style="position: absolute; text-align: right; bottom: 5px;right: 20px;">version: 1.0</div>
    </div>'
    footerTemplate: '<div style="position: relative; width: 100%; text-align: left; border-top: 1pt solid #eeeeee; margin:  10px 0px 30px; font-size: 8pt;">
    <div style="position: absolute; text-align: left; top: 5px;left: 60px;">YYYY-MM-DD</div>
    <div style="position: absolute; width: 100%; text-align: center; top: 5px;">&copy;2022 ABCD</div>
    <div style="position: absolute; text-align: right;top: 5px;right: 20px;"> <span class=pageNumber></span> of <span class=totalPages></span></div></div>'
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
- text 1 
- text 1 
- text 1 
- text 1 
- text 1 
- text 1 
- text 1 
- text 1 
- text 1 
- text 1 
- text 1 
- text 1 
- text 1 
- text 1 
- text 1 
- text 1 
- text 1 
- text 1 
- text 1 
- text 1 
- text 1 
- text 1 
- text 1 
- text 1 
- text 1 
- text 1 
- text 1 
- text 1 
- text 1 

[^1]: footnote text

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

