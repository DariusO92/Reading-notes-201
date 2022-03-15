# Reading Notes

## CH.15 Layout

-<div> elements are often used as containing element to group together sections of a page
- Browsers display pages in normal flow unless you specify relative, absolute, or fixed positioning
- The float property moves content to ther left or right of the page
- Pages can be fixed width or liqud layouts.
- Grids help create professional and flexible designs.
- You can include multiple css files in one page.
- CSS frameworks aim to make your life easier by providing code for common task such as creating layout grids, styling forms, creating printer-friendly version of pages.

## Layout

-The display property does two things. The first thing it does is determine if the box it is applied to acts as inline or block.


.my-element {
  display: inline;
}
Inline elements behave like words in a sentence. They sit next to each other in the inline direction. Elements such as <span> and <strong>, which are typically used to style pieces of text within containing elements like a <p> (paragraph), are inline by default. They also preserve surrounding whitespace.