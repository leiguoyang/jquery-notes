# jQuery notes
This is my understanding of jQuery.

## What is jQuery
jQuery is a JavaScript library to deal with the DOM. To traverse, manipulate, handle event and add effect.

- DOM traversal. `$('p')`
- DOM manipulation. `$('p').text('Some text here')`

## Why use jQuery
As the official statement,

> jQuery is a fast, small, and feature-rich JavaScript library. It makes things like HTML document traversal and manipulation, event handling, animation, and Ajax much simpler with an easy-to-use API that works across a multitude of browsers. With a combination of versatility and extensibility, jQuery has changed the way that millions of people write JavaScript.

- **Solve the browser compatability.** For example, the `addEventListener()` method is not supported in IE7. `getElementByClassName()` is not supported in versions of IE prior to 9.

- **Write less code.** For example, select all the `<p/>` element from the page.
  - Raw JavaScript: `document.querySelectorAll('p')`
  - jQuery: `$("p")`

- **Others**

## Part1 Selecting elements

Selector, filter and Method

## Part2 Manipulation

## Part3 Event handling

## Part4 Effect

## Part5 Ajax
