# HTML CSS Git Challenge: Code Refactor

Bootcamp assignment 1: Refactoring given HTML and CSS file as acceptance criteria.
## Deployed Application
https://d104601.github.io/bootcamp_assignment1/

## Acceptance Criteria
* Accessibility standards
* Semantic HTML elements
* Logical structure independent of styling and positioning
* Alt attributes for image elements
* Heading attributes fall in sequential order
* Concise and descriptive title

## Sample Website
![Sample](https://github.com/d104601/bootcamp_assignment1/blob/master/sample_website.jpg?raw=true)

## Refactoring
### index.html
Following changes applied to the HTML file.
* Replaced title to "Horiseon Social Services".
* Added "main" tag to group contents with "content" or "benefits" classes.
* Replaced "div" tag with "header" class to "header".
* Replaced "div" tag with "content" class to "section".
* Replaced "div" tag with "benefits" class to "aside".
* Replaced "div" tags inside "content" class and "benefits" class to "article".
* Added alt to all "img" tags.
* Replaced "div" tag with "footer" class to "footer".

### style.css
Following changes applied to the CSS file.
* Sorted selectors as order of contents in html.
* Replaced all div selectors to appropriate selectors, such as header, section, aside, and footer.
* Merged selectors with repeated properties to one.
