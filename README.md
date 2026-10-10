# web-tek

Coursework repository for an introductory web development class (IFSC 1100).
Each assignment lives in its own folder, and the root `index.html` links to all of them.

## Assignments

### Prototype (`prototype/`)
An "HTML Basics" page built with plain semantic HTML. It covers:
- Headings, paragraphs, and in-page navigation using anchor links (`#accessibility`, `#resources`, `#contact`)
- Ordered and unordered lists
- A description list (`<dl>`) of HTML terms
- An inline quotation (`<q>`)
- A footer section

### CSS Demo (`css-demo/`)
A blog-style layout called "Building the Modern Web," styled with an external stylesheet. It covers:
- Semantic layout elements: `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`, `figure`, `time`
- An accessible "Skip to main content" link using a `.visually-hidden` utility class
- A reusable `.container` class for centered, max-width content
- Flexbox layouts for the navigation, blog posts, and sidebar widgets
- A media query for small screens (max-width: 500px)

## Project Structure

    web-tek/
    ├── index.html              # Landing page linking to each assignment
    ├── assets/css/style.css    # Root stylesheet (box-sizing reset, skip-link utility)
    ├── prototype/
    │   ├── index.html
    │   └── assets/css/style.css
    └── css-demo/
        ├── index.html
        └── assets/css/style.css

## Viewing the Site

No build tools or dependencies are needed. Open `index.html` in a web browser
and use the links to go to each assignment.

## Technologies

- HTML5
- CSS3 (Flexbox, media queries)

## Author

Bryson Selby
