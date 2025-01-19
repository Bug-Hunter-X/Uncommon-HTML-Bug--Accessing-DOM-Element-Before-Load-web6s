# Uncommon HTML Bug: Accessing DOM Element Before Load

This repository demonstrates a less common HTML bug related to accessing DOM elements before they're fully loaded by the browser.  The bug occurs when JavaScript code attempts to manipulate a DOM element (in this case, setting the display style to "none") before the browser has parsed and rendered that element.

The solution involves using the `DOMContentLoaded` event to ensure the JavaScript code only executes after the HTML has been fully parsed and the DOM is ready.