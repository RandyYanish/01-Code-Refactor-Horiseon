# 01 HTML, CSS, and Git: Code Refactor

## Description
**On-the-job ticket:** Given starter code to modify and a User Story to follow and acceptance criteria to complete.

Acceptance criteria for the webpage:

```
- Meet accessiblity standards
- Define semantic HTML elements
- Elements must follow logical structure independent of styling and positioning
- Alt attributes must be added to the images and icons
- Heading attributes fall in sequential order
- Add concise and descriptive title
```
## Visuals
![Horiseon's webpage has a navigation bar, hero image, and cards with text and images.](./assets/images/01-html-css-git-homework-demo.png)

## Breakdown
To accomplish the objective, the following steps were done:
- Read and understand the functionality of the website.
- Research the User Story issues and Acceptance Criteria to complete the objective. What is:
    - Code Refactoring

    - HTML Accessibility

    - HTML Semantic Elements

    - Web accessibility standards

    - Markdown and Visual Studio Code

    - Standard README practices

- Apply researched concepts to the html, css, and markdown files
  
\
## Modifications to the HTML file
```
Structure and descriptive comments were added

<!-- Header -->

<!-- Main Content -->

<!-- Hero banner -->

<!-- Additional Content -->

<!-- Footer -->



Changed <div> to header and removed class header

Changed <div> to <nav>



Changed <div> to <main> and removed class content

Removed class online-reputation-management

Removed class social-media-marketing



Changed <div> to <aside> and removed class benefits

Changed class benefit-lead, benefit-brand, and benefit-cost to id



Changed <div> to footer and removed class footer

Added alt text for all images and icons

```
\
## Modifications to the CSS file
```
Structure and descriptive comments were added

/* -------- General Styling --------*/

/*-------- Header --------*/

/*-------- Hero Banner --------*/

/*-------- Main Content --------*/

/*-------- Additional Content --------*/

/*-------- Footer --------*/



Changed .header to header

Changed .content to main

Changed .benefits to aside

Changed .footer to footer

Changed header div to nav



Rules that were simplified into one rule:

background: url("../images/digital-marketing-meeting.jpg") center / cover;

#benefit-lead,
#benefit-brand,
#benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}

#benefit-lead h3,
#benefit-brand h3,
#benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
}

#benefit-lead img,
#benefit-brand img,
#benefit-cost img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

#search-engine-optimization,
#online-reputation-management,
#social-media-marketing {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

#search-engine-optimization img,
#online-reputation-management img,
#social-media-marketing img {
    max-height: 200px;
}

#search-engine-optimization h2,
#online-reputation-management h2,
#social-media-marketing h2 {
    margin-bottom: 20px;
    font-size: 36px;
}
```

## Installation
The project was uploaded to [GitHub](https://github.com/) at the following repository:
[https://github.com/RandyYanish/01-Code-Refactor-Horiseon/](https://github.com/RandyYanish/01-Code-Refactor-Horiseon/)

You can access the deployed application with the GitHub Pages link: [https://randyyanish.github.io/01-Code-Refactor-Horiseon](https://randyyanish.github.io/01-Code-Refactor-Horiseon)


## References
[Code refactoring](https://en.wikipedia.org/wiki/Code_refactoring)

[HTML Accessibility](https://www.w3schools.com/html/html_accessibility.asp)

[HTML Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)

[Web accessibility standards](https://www.w3.org/TR/WCAG21/)

[Markdown and Visual Studio Code](https://code.visualstudio.com/docs/languages/markdown#_markdown-preview)

[Make a README](https://www.makeareadme.com/#template)
