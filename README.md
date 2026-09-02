# University Website Practice

## Technologies

- HTML5
- CSS3
- Flexbox
- CSS Media Queries
- Google Fonts
- Font Awesome

## Project Overview

This project is a university website interface created as an HTML and CSS practice project.

The main purpose of the project is to reinforce fundamental frontend development concepts by building a complete website structure from scratch and applying CSS styling in a practical project.

The project was developed before moving on to JavaScript, with a focus on understanding HTML structure, CSS layout, Flexbox, positioning and responsive design.

## Sections

The website includes the following sections:

- Hero / Header section
- Navigation menu
- Courses section
- Global Campus section
- Facilities section
- Testimonials section (work in progress)

## Features

- Full-screen hero section with background image
- Navigation menu
- Google Fonts integration
- Font Awesome integration
- Course cards
- Global campus cards with hover effects
- Facilities section with image cards
- Flexbox-based layouts
- Responsive design using CSS media queries
- CSS hover and transition effects

## Project Preview

### Hero Section

![Hero Section](image/hero-preview.png)

### Courses Section

![Courses Section](image/courses-preview.png)

### Global Campus

![Global Campus](image/campus-preview.png)

### Facilities

![Facilities](image/facilities-preview.png)

## What I Practiced

### HTML

During the project, I practiced:

- HTML document structure
- Semantic sections
- Navigation structure
- Lists and links
- Images and relative file paths
- Headings and paragraphs
- Nested elements
- Element hierarchy

### CSS

I practiced:

- CSS selectors
- Box model
- Flexbox
- `display: flex`
- `justify-content`
- `flex-basis`
- `position`
- `transform`
- `background-image`
- `background-position`
- `background-size`
- `transition`
- `:hover`
- Media queries
- Typography
- Spacing and sizing

## Problems Encountered

During the development process, I encountered several problems and used them as debugging practice.

### Background Image

The hero background image did not initially appear.

I checked:

- The `background-image` declaration
- `rgba()` syntax
- Relative image paths
- The project folder structure
- Whether the CSS file had been saved

The issue was ultimately related to the file not being saved correctly.

### Navigation Links

The navigation menu initially had problems with the structure of the anchor elements.

This helped reinforce the difference between the `href` attribute and the content of an `<a>` element.

### Flexbox Layout

The campus and facilities sections required checking the relationship between the `.row` container and the child elements.

This helped me understand that:

- `.row` acts as the flex container.
- The elements inside `.row` become flex items.
- Properties such as `flex-basis` affect the size of those flex items.

### Responsive Design

The project also includes a responsive structure using CSS media queries.

Some responsive layout issues remain, especially in the mobile view.

Since the main purpose of this project was to reinforce HTML and CSS fundamentals before moving to JavaScript, the project was stopped at this stage rather than spending additional time polishing every responsive detail.

## What I Learned

This project helped me understand how HTML and CSS work together in a real project instead of studying individual properties separately.

The most important concepts I practiced were:

- Building a complete HTML page structure
- Organizing elements with Flexbox
- Understanding parent and child relationships
- Working with relative file paths
- Using background images
- Creating hover effects
- Using media queries
- Debugging HTML and CSS problems
- Checking whether a problem comes from the code, file structure or development environment

I also learned that debugging is not always about changing code. Sometimes the problem can be caused by a simple issue such as an unsaved file or an incorrect file path.

## Current Status

The project is complete as an HTML and CSS practice project.

Some parts are intentionally left unfinished, including:

- Final responsive/mobile polishing
- JavaScript-based navigation functionality
- Completion of the testimonials section
- Connecting navigation links to separate pages

These areas are planned for future projects or further practice.

## Project Structure

```text
university-website-practice/
│
├── image/
│   ├── banner.png
│   ├── logo.png
│   ├── london.png
│   ├── newyork.png
│   ├── washington.png
│   ├── library.png
│   ├── basketball.png
│   └── cafeteria.png
│
├── index.html
├── style.css
└── README.md
