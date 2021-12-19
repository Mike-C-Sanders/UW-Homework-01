# UW-Homework-01

## Description

First homework assignment for the UW boot camp. This is a refactoring assignment, meaning we are making changes to existing code. For this particular assignment, a marketing agency has hired me to refactor an existing site, which currently doesn't follow accessibility standards. My objective is to change the codebase to follow accessibility standards so that the site is optimized for search engines.

For more information on web accessibility check out the references and resources section in this readme file.

To access the published site follow this GitHub Pages link:<https://mike-c-sanders.github.io/UW-Homework-01/>

![01-html-css-git-homework-demo](https://user-images.githubusercontent.com/71601403/146661670-f873947c-0647-48de-8b10-d74f6bd80f0f.png)

## Table of Contents

```
README.md - primary Readme file

index.html - primary html file

(file) 02-Homework

    * Assets

        1. 01-html-css-git-homework-demo.png

    * Develop\assets

        1. CSS
            * style.css - style sheet called in index.html

        2. Images
            * brand-awareness.png
            * cost-management.png
            * digital-marketing-meeting.jpg
            * lead-generation.png
            * online-reputation-management.jpg
            * search-engine-optimization.jpg
            * social-media-marketing.jpg
    * Homework-Guide
        1. README.md - Homework guide/criteria 

    *README.md - Homework instructions and prompt
```

## Refactored Changes

All changes to the source code are logged via comments in the given file. For a detailed list of these changes see below.

### Index.html

    * Removed all div tags/elements
    
    * Added Header, Main, and Footer Tags for structuring the body

    * Added nav element to the page

    * Added 3 section tags: one for the hero image, one for the main articles for the page and the third for the side bar. 

    * Wrapped images with figure tags and added an alt text for all images for better screen reader accessibility. 

    * Under the section tags div tags were changed to article tags. 

    * Links from the navigation bar weren't navigating to the correct article. The fix required a change from class to id

### Style.css

    * Exchanged the div references for the related tag change. For instance, in the header changing the style from header div to header nav

    * Changed the class references to ID references to match the index.html file references: search-engine-optimization, online-reputation-management and social-media-marketing
    
## References & Resources

For more information regarding web accessibility, visit:

1. WCAG Guide: <https://www.w3.org/TR/UNDERSTANDING-WCAG20/>

2. Usability.gov: <https://www.usability.gov/what-and-why/accessibility.html>

3. Mozilla Developer: <https://developer.mozilla.org/en-US/docs/Web/Accessibility/Understanding_WCAG>
