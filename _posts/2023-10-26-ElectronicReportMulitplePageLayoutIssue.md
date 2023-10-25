---
layout: post
title: "Electronic Reporting : Layout issue : Report data is overlapping on other pages while printing in pdf format"
sitemap:
    priority: 0.7
    changefreq: 'monthly'
    lastmod: 2021-10-05T12:49:30-05:00
---
## Details :
- Electronic Reporting in Dynamics finance and operations
- PDF Format
- Layout Issue
- Electronic Reporting Template based on excel

## Issue :
When Multiple pages are being printed in a PDF format, the pages were overlapping each other.

## Report Details:
- Template based on Excel

## Resolution
The above issue got resolved. 
 
###For future reference, we needed to adjust the Excel template using the "View->Page Break Preview" and realign the size.

![ExcelTemplate](./images/ElectronicReportMulitplePageLayoutIssue_template.png)
 
###set Adjust Row Height to true in the designer

 ![AdjustRowHeight](./images/ElectronicReportMulitplePageLayoutIssue_AdjustRowHeight.png)
 
###Keep Rows Together in the range

 ![KeepRowsTogether](./images/ElectronicReportMulitplePageLayoutIssue_KeepRowsTogether.png)