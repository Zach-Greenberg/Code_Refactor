# Code_Refactor

## Description
The User wanted a codebase that followed accessibility standards so their website is optimized for search engines. To ensure search engine optimization and accessibility standards where met, I implimented semantic HTML elements that were structured logically, added alt attributes for each image that was on the webpage, and made sure that the webpage had a descriptive and concise title.

I learned that you can style and organized multiple articles within one section or aside to allow for cleaner and concise css coding. This alone allowed me to delete any duplicate code that was shown in the css page before. Below are most of the changes that occured in index.html and style.css.

## Table of Contents

* [HTML Changes/Notes](#HTML)
* [Style.css Changes/Notes](#Style.css)
* [Bugs/Fixes](#Other)

## HTML

Rename first div to header to indentify it to the top of the page at a glance div -> header

Rename second div to nav for indentification of the links that navigate the webpage div -> nav

Changed div class="content" to just section class="content"

Changed div class="benefits" to aside class="benefits"

Changed div class="footer" to footer

Changed each div with its own id and class to article to show its a self-contained article

Deleted all class="" within section class="content" and had an id="" for each article

I kept the classes for section and aside incase there was an addition of another section or aside in HTML in the future.



## Style.css

Reorganized the order to match the semantic layout of the webpage.

changed .header to just header

deleted hi .seo to just .seo since it was redundent

Changed div in the header to nav so our ul and the following li stayed organized.

Deleted header nav ul since I could add list-style-type into nav ul li

Consolidated all of section class="content" into just some .content article

Repeated the last step with everything inside of our aside

changed .footer to just footer

## Other

deleted unnecessary / at the end of img

deleted unnecessary /img
