This is a custom web framework in process.  

# Pattern Requirements

This document will describee the structure of each pattern and its behaviour under various screen sizes.

---

## Grid System

**Description**

- 12 Columns
- Responsive and Fluid
- Columns are wrapped in a container .row
- Each column will have a class of .col-$
- A .container class that wraps all content on the page.  Must be fluid in width.

**Responsive Behaviour**

- In medium screen sizes (default at <1024px) the columns will have their gutter width halved.
- In small screen sizes (default at <768px) all columns will get a full (100%) width.


## Typography

**Elements**

- Headings
- Paragraphs
- Bold, em, strike, link
- Code blocks
- Lists
- Blockquotes

## Buttons

**Description**

- 2 styles: default, primary
- 3 sizes: small, default, large
- Styles for all HTML elements: '<a>, <button>, <input type="button">, <input type="submit">'

## Form Elements

**Elements**

- Inputs
- Radios and checkboxes (custom controls)
- Pre-Made forms: sign-in, sign-up, contact

## Icons

**Description**

- FontAwesome fonts
- Styles for bordered icons
- Styles for square, rounded or circle border
- 4 sizes: small, default, large, huge

## Feedback

**Description**

- 4 message boxes: info, success, error, warning

## Navigation

**Elements and characteristics**

- Navbar
- Contains logo on the left side and menu on the right side
- The menu will be powered by the Superfish jQuery plugin

**Responsive Behaviour**

- On page load, the main menu will be cloned via jQuery into a responsive menu
- On small screen sizes (default at <768px) the main menu will be hidden, the logo moves to the center and the responsive meny will be displayed below the logo

## Animations

**Description**

- Uses the animate.css library b Dan Eden

## Tabs and Accordians 

**Description**

- Custom

## Carousels

**Description** 

- Uses the owl-carousel jQuery plugin
