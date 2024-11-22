# Introduction to Web Development

An introduction to the core concepts of web development, covering HTML and CSS basics.

## Basics of Web Development

- Web development involves creating websites and web applications.
- Core languages include **HTML** for structure and **CSS** for styling.

---

## What is HTML?

HTML (HyperText Markup Language) is the standard language for creating web pages. It defines the structure and content of a webpage.

### Basic Rules in HTML

- HTML is composed of elements enclosed in tags.
- Tags typically come in pairs: an opening tag `<tagname>` and a closing tag `</tagname>`.
- HTML documents must start with a `<!DOCTYPE html>` declaration to define the document type.

---

## Basic Tags in HTML

### `html`

Defines the root of an HTML document.

### `head`

Contains metadata and links to resources such as stylesheets and scripts.

#### Common Elements in the `head` Tag

- **`title`**: Defines the title shown in the browser tab.
- **`favicon`**: The small icon displayed in the browser tab, linked via `<link rel="icon">`.
- **`link` Tag**: Links external resources like CSS files.
- **`script` Tag**: Embeds or links JavaScript files.

### `body`

Contains all the visible content on the webpage.

#### Common Elements in the `body` Tag

- **Heading Tags**: `<h1>` to `<h6>` define headings, with `<h1>` being the largest.
- **Paragraph Tags**: `<p>` for paragraphs.
- **Text Formatting Tags**: `<b>`, `<i>`, `<u>`, `<strong>`, etc., for styling text.
- **Tags and Attributes**: Tags can have attributes that define additional properties.
- **Images**: `<img src="url" alt="description">` to embed images.
- **Links**: `<a href="url">link text</a>` to add links.
- **Input Elements**: `<input>`, `<textarea>`, `<button>` for forms.
- **List Tags**: `<ul>`, `<ol>`, and `<li>` for unordered and ordered lists.
- **Div and Section Tags**: `<div>` and `<section>` to create container sections.
- **Classes and IDs**: Used for styling and selecting elements in CSS. Defined with `class="name"` and `id="name"`.

---

## What is CSS?

CSS (Cascading Style Sheets) is used to style and layout HTML elements, defining the visual appearance of a webpage.

### Why We Use CSS

- CSS separates content from design.
- It allows for consistent styling and responsive layouts.

### Basic Rules in CSS

- CSS is composed of selectors and properties, written in `{}` brackets.
- Properties define the styles, and values define the specifics of each property.

---

## CSS Box Model

CSS uses a box model to define the layout and spacing of elements. The box model consists of:

- **Content**: The actual content (text, images).
- **Padding**: Space between content and border.
- **Border**: The edge of the element.
- **Margin**: Space outside the border, separating elements.

---

## Basic Properties in CSS

- **`height` and `width`**: Define the size of elements.
- **`margin`**: Space outside an element’s border.
- **`padding`**: Space between content and border.
- **`border`**: Outline of the element.
- **`color`**: Text color.
- **`background`**: Background color or image.
- **`font`**: Font style, size, and family.
- **Text Formatting**: Properties like `text-align`, `text-transform`, `line-height`.

---

## CSS Selectors

### Simple Selectors

Select elements based on name, ID, or class:

- `element` (e.g., `p { ... }`)
- `#id` (e.g., `#header { ... }`)
- `.class` (e.g., `.button { ... }`)

### Combinator Selectors

Select elements based on relationships:

- **Descendant** (e.g., `div p { ... }`)
- **Child** (e.g., `div > p { ... }`)
- **Adjacent sibling** (e.g., `h1 + p { ... }`)
- **General sibling** (e.g., `h1 ~ p { ... }`)

### Pseudo-Class Selectors

Select elements in a specific state:

- `:hover`, `:focus`, `:active`, `:first-child`, `:last-child`

### Pseudo-Element Selectors

Select and style part of an element:

- `::before`, `::after`, `::first-line`, `::first-letter`

### Attribute Selectors

Select elements based on attribute values:

- `[type="text"]`, `[href^="https"]`, `[class*="btn"]`

---

## CSS Display Properties

### Flex Properties

CSS Flexbox is used to create flexible and responsive layouts. Common properties include:

- **`display: flex;`**
- **`justify-content`**: Aligns items horizontally.
- **`align-items`**: Aligns items vertically.
- **`flex-direction`**: Controls the direction (row or column).

### Grid Properties

CSS Grid is used for complex layouts with rows and columns. Common properties include:

- **`display: grid;`**
- **`grid-template-columns`**: Defines columns.
- **`grid-template-rows`**: Defines rows.
- **`gap`**: Space between grid items.

---

This guide provides an overview of foundational HTML and CSS concepts to create and style web pages.
