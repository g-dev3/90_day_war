# 90 Days of War

## DAY 1

## HTML & CSS

### What is HTML?

HTML creates web pages. It provides structure and content like headings, paragraphs, links, and images.
HTML stands for HyperText Markup Language. Without HTML, browsers cannot display any content.

### What is HTML Element?

Anything you display on a webpage is an element. Example: `<button>`, `<p>`, `<img>`
Elements are the building blocks that make up a web page.

### What is HTML Tag?

Keyword in angle brackets `< >` that tells the browser what to display. Example: `<p>`, `<button>`, `<img>`
Most tags come in pairs: opening `<p>` and closing `</p>`. Some are self-closing like `<img/>` or `<br/>`.

### What is Anchor Element?

Creates links using `<a>` tag so users can click and go to other pages.
Example: `<a href="https://example.com">Click here</a>`
The `href` attribute tells where the link should go.

### What is Syntax?

Syntax means the rules for writing code correctly.
If you don't follow the rules, the browser won't understand your code.
Example:

```html
<button>hello</button>
```

### What is HTML Attribute?

Attributes modify element behavior and add extra information.
Example: `href="https://youtube.com"` - left side is name, right side is value.
You can use `target="_blank"` to open links in a new tab.

**Note:**
Extra spaces and line breaks in HTML are ignored by the browser. Format code for readability—it won't change how the page looks.
Example:

```html
<p>This is organized code.</p>
```

### What is Indent?

Indent means adding spacing before your code to make it organized.
This helps you see which tags are inside other tags.
Proper indentation makes code easy to read and understand.

## DAY 2

### What is CSS Selector?

CSS selector tells which HTML element you want to style.
Example: If you want to style all paragraphs, you use `p` as your selector.

### What is CSS Property?

CSS property is what you want to change about an element.
Example: `background-color`, `color`, `font-size`
You use properties to change how elements look.

### What is CSS Value?

CSS value is the result or choice you pick for a property.
Example: In `background-color: red`, red is the CSS Value.
You can use color names, hex codes, or rgb values as CSS values.

### What is Pixels?

Pixels are tiny dots on your screen used to measure size.
Images, videos, and screen sizes are all measured in pixels.
Example: A screen might be 1920 pixels wide and 1080 pixels tall.

## DAY 25

### What is Margin and Padding?

Margin is space outside an element (outside the border). It creates distance between elements.
Padding is space inside an element (inside the border). It creates distance between content and the border.
Think of margin as pushing things away, and padding as giving things breathing room inside.

### What is Box Model?

Box model describes how elements are structured with layers.
From inside out: content (text/image) → padding (inside space) → border (line) → margin (outside space).
Designers use box model to control spacing and layout.

### What is Transition?

Transition smoothly changes CSS properties over a time period.
Instead of changing colors instantly, transition makes it smooth and animated.
Example: `transition: background-color 0.3s;` (takes 0.3 seconds to change)

### What is Hover?

Hover is a pseudo-class that styles an element when you move your mouse over it.
Example: `button:hover { background-color: blue; }`
This creates interactive effects without needing JavaScript.

### What is Opacity?

Opacity controls how transparent or visible an element is.
Value 0 means completely invisible (hidden).
Value 1 means completely visible (fully opaque).

### What is Shadow?

Shadow adds a shadow effect to elements to make them look 3D.
Example: `box-shadow: 2px 2px 5px gray;`
Shadows can be on text or boxes to create depth effect.

### What is Chrome DevTool?

DevTool is a built-in browser tool to inspect web pages.
You can see HTML, CSS, and debug JavaScript.
Press F12 or right-click and select "Inspect" to open DevTools.

## DAY 26

### What is HTML Entity?

HTML entity is a special code for symbols that aren't on your keyboard.
Example: `&amp;` for ampersand (&), `&lt;` for less-than (<), `&nbsp;` for space
Browsers convert these codes to display the actual symbol.

### What is Paragraph Default Margin?

In HTML, paragraphs automatically have default margin (space around them).
Most browsers add about 14px margin on top and bottom.
You can change this margin using CSS if you want.

### What is CSS Specificity?

Specificity is a rule that decides which CSS style gets applied when there are conflicts.
More specific selectors have higher priority than general ones.
Example: ID selector has higher specificity than class selector.

### What is Text Element?

Text elements are HTML elements used to display text content.
Example: `<p>` for paragraph, `<h1>` for heading, `<span>` for inline text
These elements structure your text on the webpage.

### What is span Element?

Span is an inline element used to style or group small text.
It doesn't create a new line like `<div>` does.
Use span when you want to style text without breaking the flow.

## DAY 28

### What is Void Element?

Void elements are self-closing tags that don't have closing tags.
Example: `<img>`, `<br>`, `<input>`, `<hr>`
They are complete by themselves and don't wrap content.

### What is Filepaths?

Filepath is the location or address of a file on your computer.
Example: `../images/photo.jpg` or `./styles/main.css`
Filepaths help you link to images, stylesheets, and other files.

### What is title?

The `<title>` tag sets the name of your webpage.
This name appears in the browser tab and bookmarks.
Example: `<title>My Awesome Website</title>`

### What is Object-fit property?

Object-fit controls how an image fills its container space.
Example: `cover` fills container but crops image, `contain` fits entire image
Use object-fit to make images responsive and look good in any container.

### What is Object-position property?

Object-position sets exactly where the image is positioned inside its container.
Example: `center`, `top left`, `50% 50%`
Use this with object-fit to control image placement.

### What is Placeholder?

Placeholder is hint text shown inside input fields.
It disappears when user starts typing.
Example: `<input placeholder="Enter your name">`

## DAY 31

### What is block element?

Block elements take up full width and always start on a new line.
Example: `<div>`, `<p>`, `<h1>`, `<section>`
Block elements stack on top of each other.

### What is inline block element?

Inline block elements flow inline with text but also respect margin and padding.
Example: `<img>`, `<button>`
They have properties of both inline and block elements.

### What is inline element?

Inline elements flow within text on the same line without breaking.
They only take up as much width as necessary.
Example: `<span>`, `<a>`, `<strong>`, `<em>`


## DAY 32

### What is `<div>` element?

Div is a block element used as a container to group and organize other elements.
It doesn't have any visual appearance by itself, but you can style it with CSS.
Div is one of the most commonly used elements for creating layouts.

### What is Nested Layout technique?

Nested layout means putting elements inside other elements to create structure.
You place divs inside divs to create columns, rows, and sections.
This technique helps organize page layout and makes styling easier.