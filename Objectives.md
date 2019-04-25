# HTML_CSS_I

## HTML

- Student can use the head tag to put meta information about the page
- Student can use the body tag to specify what will be displayed
- Student can use div, p, h1-h6, and span tags to layout a flow of information
- Student can use ol, ul, and li tags
- Student can use nav, footer, and header tags
- Student can use img tags to bring in pictures
- Student can use a tags to route to another webpage
- Student can use link tag to bring in css filesCSS

## CSS

- Student can apply properties to an element, class, and id
- Student can use the font and color to change font properties
- Student can use text-align property
- Student can use background property to give colors or images for backgrounds
- Student can use height, width, margin, padding, and box-sizing properties
- Student can use the float property
- Student can use a reset file
- Student can bring in a new font into a project

# to remember

## HTML tag properties

`display: block;`:
  - starts on a new line and takes up the whole width of the row
  - respects height, width, margin-top, margin-bottom

  commonly used block-level elements: 
  ```html
  <!-- Paragraph tags -->
  <p>For Paragraphs</p>
  <!-- div tags -->
  <div>no semantical purpose, helps with content layout</div>
  <!-- section tags -->
  <section>To logically separate content </section>
  <!-- heading tags -->
  <h1>For Section headings</h1>
  <h2>Sub Heading</h2>
  <h3>Sub Sub heading</h3>
  ```

`display: inline`:
  - allows elements to sit next to eachother by default
  - generally used for text
  - Inline elements are those which only occupy the space bounded by the tags defining the element, instead of breaking the flow of the content.
  - doesnt respect height, width, margin-top, margin-bottom

 commonly used inline elements: 
  ```html
  <!-- Anchor tags  -->
    <a href='http://google.com'>will send you to another document</a>
  <!-- Span -->
  <span>No semantical purpose, (div tag for text)</span>
  <!-- Button -->
  <button>Generally used for initiating an action</button>
  ```

`display: inline-block`:
  - allows elements to sit next to eachother by default
  - respects height, width, margin-top, margin-bottom
  - mixture between inline and block-level elements
  - no elements default to inline-block

## Linking HTML and CSS

In order to separate document structure and document style concerns (seperation of concerns) we put CSS in a separate file and link it with a `<link>`

```md
application/
    - index.html
    - index.css
```
in index.html
```html
<link rel="stylesheet" href="./index.css">
```

## Selectors

### **classes**

- can add multiple of the same class selector in the same document to select many elements

```html
<div class="my-class">my div</div>
<div class="my-class">my other div</div>
```

- denoted by a '.' at the beginning of the selector name in CSS documents

```css
.my-class {
  color: red;
}
```

**id's**

- can only be applied once per document page

```html
<div id="my-id">my div</div>
```

- denoted by a '#' at the beginning of the selector name in CSS documents

```css
#my-id {
  color: red;
}
```

## Floats
