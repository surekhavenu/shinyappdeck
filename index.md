---
title       : Simple Shiny Application
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

##  Application Requirements
1. Some form of input (widget: textbox, radio button, checkbox, ...)
2. Some operation on the ui input in server.R
3. Some reactive output displayed as a result of server calculations
4. You must also include enough documentation so that a novice user could use your application.
5. The documentation should be at the Shiny website itself. Do not post to an external link.

---  

## Application Design Details
1. Application contains a text box, radio buttons and check box.  
2. Server.r calculates the numbers of courses completed by student  
   in a reactive output.  
3. Application contains an embeded help.  

---  

## Application Implementation Details
1. It contain two tabs

```
## Enroll Student Details
## Help
```

2. Enroll Student Details Tab allows to enter student name, sex and 
   data science specialization courses completed. 
   
3. Enroll Student Details Tab calculates the number of courses 
   completed and displays the student details such as name, sex,
   number of course completed and percentage of data science courses 
   completed.
   
4. Help Tab provides the information required to use the application.

---  

##  Application Location Details
1. Application URL :  
   https://surekhavenu.shinyapps.io/ShinyApp
2. Source Code URL :  
   https://github.com/surekhavenu/shinyapp  

