# Horiseon Assignment // Week 1 homework

## Aim // Introduction
Take the existing Html and CSS project files provided in the WAUS-CRAW-FSF-PT-02-2020-U-C-MW / Week1 / Day1 / Homework repository on GitLab and refractor it to meet a outline set by the Week 1 Homework Assignment. For extra flare, show addition understanding of principals discussed in Week 1 through application.

## Important Notice
The original Index.html and Style.css are attached to these projects for reference. They have been renamed to Indexcopy.html and Stylecopy.css. The edited versions submitted for this project are named Index.html and Style.css

## Key Concepts of Week 1
* HTML and CSS syntax
* Floats, Positioning and Box Models
* Using Github

## Table of Content
* [Semantic and Sequential Order of Elements](#Semantics)
* [Logical Structure Independent of style](#Logic)
* [Repair missing or broken elements](#Repair)
* [Cleaning up the code](#Cleanup)
* [Bonus: Make things pretty // Experimentation](#Bonus)

## Technology
* HyperText Markup Language
* Cascading Style Sheets
* Visual Studio Code ver 1.42.0
* GitHub
* Google Chrome ver 79.0.3945.130


### (#Semantics)Semantic and Sequential Order of Elements
The original index.html contained heavy use of the '<div>' elements that were using 'class' as an indicator of the structure.
In theory the original structure worked as following:'<head>', '<title>', '<body>', '<header>', '<div: nav>', '<div: img>', '<div: content>', '<div: benifit>', and '<div: footer>'. To make this structure more semantic and sequential the order was reworked into the following: '<head>','<title>','<body>', '<header>', '<nav>', '<figure>', '<section>', '<aside>', and '<footer>'. The '<nav>' root element was later removed as it served the same purpose as the '<header>' root element.

The original style.css contained similiar problems by over using the class tags and placing the '<aside>' elements before the '<content>' elements. Corresponding to the new structure implemented in the Html a numnber of classes were renamed, edited or merged.

Notes were applied to both the HTML and CSS between each section to clear indicate where one root element began and ended. 

### (#logic)Logical Structure Independent of Style
The logical structure of the original index.html was very clean. The only error I found might be the footer using '<H2>' after '<H3>' and the over use of div elements. 

The '<figure>' element which contained the '<div class= hero>' was changed to include the '<img src>' element from the Style.css. The arguement from a design perspective is your 'hero' image is important in indicating expectation and it made it easier to style the element within the CSS.  

### (#Repair)Repairing Missing or Broken Elements
* The link for '#search-engine-optimization' within the '<header>' was not work as the corresponding ID did not exist. This was inserted on line 40.
* Title was named 'Website' and later renamed 'Horiseon | Social Solutions'.
* Alt elements were applied to every img src attribute in the html. Larger pictures were given short discriptions whilst icons were simply named after the icons they were representing

### (#Cleanup)Cleaning up the code
As inidcated in the Semantic section I did start dramatically reducing the number of classes in the CSS and removed the '<nav>' section in the HTML. For contrast the original html was 83 lines of code and the edit was increased to 103 lines to accomadate additional spacing and notes. The original CSS was 200 lines of code and the edit become 182 regardless of the additional notes, spacing and styling. 

Key points of change was reducing the '<content>' and '<aside>' root elements, moving the '<img src>' to the HTML, adding additional elements to the new '<figure>' root element and changing some of the element style settings.

* Examples of an element name being shortened include '.header div ul' changing to 'header ul'. 
* Examples of elements being merged include '.benifit-something H3' merged to 'H3'
* Examples of elements being renamed include '.float-left' changed to '.left-content-image'

### (#Bonus) Making things pretty // Experimentation
There were some clear attempts within this project to implement leasons learned in Week 1 and attempt to future proof the website in some capacity. I made a list below of '<style>' changes I had made.

* Cropping the Hero element
* Applying Absolute, Flexible and Fixed position properties to all images for additional control. Absolute and Flexible set to Content/ Aside elements, Fixed for Footer element. Attempted to use Absolute/ Flexible for the Hero Img but failed. 
* Change the '<Aside>' and '<Content>' sizings to be more relative than absolute
* Adding 'Font-family' to all 'font' properties
* Didn't find a good use for a pseudo-element. 
* Didn't apply a CSS Reset but attempted

## Sources
Code was originally supplied in the WAUS-CRAW-FSF-PT-02-2020-U-C-MW / Week1 / Day1 / Homework repository on GitLab (https://waustralia.bootcampcontent.com/the-university-of-western-australia/WAUS-CRAW-FSF-PT-02-2020-U-C-MW/tree/master/Week%201/Day%201/Homework)

## Additional references
W3 Schools
Developer.mozilla.org
Bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project
Resources provided in Slack

## Contributor
Joshua K Bader







