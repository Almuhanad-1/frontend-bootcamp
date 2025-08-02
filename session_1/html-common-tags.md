# HTML TAGS

This document provides a brief overview of some common HTML tags used in web development.

## Basic Structure

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <h1>This is a Heading</h1>
    <p>This is a paragraph.</p>
  </body>
</html>
```

## Tags Overview

HTML tags are used to create elements on a web page. Each tag has a specific purpose and can contain attributes to modify its behavior or appearance. Below is a categorized list of common HTML tags:

## Tags anatomy

- `<tagname>`: Opening tag, used to start an element.
- `</tagname>`: Closing tag, used to end an element.
- `<tagname attribute="value">`: Opening tag with attributes, used to provide additional information about the element.
- `<tagname />`: Self-closing tag, used for elements that do not have any content between opening and closing tags, such as `<img />` or `<br />`.

## Text Content

- `<h1>` to `<h6>`: Headings, where `<h1>` is the highest level and `<h6>` is the lowest.
- `<p>`: Paragraph, used for blocks of text.
- `<span>`: Inline container, used to style a part of text or a document.
- `<strong>`: Strong importance, typically displayed in bold.
- `<em>`: Emphasis, typically displayed in italics.
- `<br>`: Line break, used to insert a line break in text.
- `<hr>`: Horizontal rule, used to create a thematic break in the content.
- `<del>`: Deleted text, typically displayed with a strikethrough.
- `<ins>`: Inserted text, typically displayed with an underline.

## Lists

- `<ul>`: Unordered list, used for bullet points.
- `<ol>`: Ordered list, used for numbered lists.
- `<li>`: List item, used within `<ul>` or `<ol>` to define each item.

## Links and Embedded Content

- `<a href="url">`: Anchor tag, used to create hyperlinks.
- `<img src="image.jpg" alt="description">`: Image tag, used to embed images.
- `<iframe src="url">`: Inline frame, used to embed another document within the current HTML document.

## Tables

- `<table>`: Table, used to display tabular data.
- `<tr>`: Table row, used within `<table>` to define a row.
- `<th>`: Table header cell, used within `<tr>` to define a header cell in a table.
- `<td>`: Table data cell, used within `<tr>` to define a cell in a table.

## Forms

- `<form>`: Form, used to collect user input.
- `<input type="text">`: Input field, used for text input.
- `<textarea>`: Text area, used for multi-line text input.
- `<button>`: Button, used to create clickable buttons.
- `<label>`: Label, used to define a label for an input element.
- `<select>`: Dropdown list, used to create a selection box.
- `<option>`: Option, used within `<select>` to define each option in a dropdown list.

## Containers

- `<div>`: Division, used to group content for styling or layout purposes.

## Attributes

Attributes provide additional information about HTML elements. They are always specified in the opening tag and come in name/value pairs like `name="value"`. Common attributes include:

- `class`: Used to assign a class to an element for styling.
- `id`: Used to assign a unique identifier to an element.
- `style`: Used to apply inline CSS styles to an element.
- `title`: Used to provide additional information about an element, typically displayed as a tooltip.
- `lang`: Used to specify the language of the element's content.
- `dir`: Used to specify the text direction (e.g., `ltr` for left-to-right, `rtl` for right-to-left).
- `data-*`: Custom data attributes, used to store extra information on an element without affecting its presentation or behavior.
- `tabindex`: Used to specify the tab order of an element when navigating with the keyboard.
- `role`: Used to define the role of an element in accessibility contexts, helping assistive technologies understand its purpose.
- `aria-*`: ARIA attributes, used to enhance accessibility by providing additional information about the element's role, state, and properties to assistive technologies.
- `hidden`: Used to indicate that an element is not yet, or is no longer, relevant. It can be used to hide elements from the user interface without removing them from the DOM.

## Conclusion

This document provides a brief overview of common HTML tags and their uses. Understanding these tags is essential for creating structured and accessible web content. For more detailed information, refer to the [HTML Living Standard](https://html.spec.whatwg.org/multipage/).

## Additional Resources

- [MDN Web Docs - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [W3Schools - HTML Tutorial](https://www.w3schools.com/html/)
- [Can I use](https://caniuse.com/) - Browser support for HTML features
- [Harmash - Learn HTML (Arabic)](https://harmash.com/tutorials/html/overview)
