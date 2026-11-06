# Assignment 2.4 - HTML Validation & Debugging

## Errors Found in before.html

1. The `html` tag has no `lang` attribute.
2. The `head` has no `meta charset` tag.
3. The `title` tag is not closed.
4. The heading starts with `h1` but ends with `h2`.
5. The `strong` and `em` tags are nested incorrectly. The `em` tag must close before `strong`.
6. The `p` tags are not closed.
7. The `img` tag has no `alt` attribute.
8. The `a` tag has no `href` attribute.
9. The `li` tags are not closed.
10. The `div` and `span` tags are not closed.

## How I Checked

I opened before.html in the browser and inspected it in the Elements panel of DevTools. I also checked the markup with the W3C Markup Validation Service.

## Result

All errors are fixed in index.html with proper indentation. The original buggy code is in before.html.

## Screenshot of the Fixed Webpage

![Fixed webpage](browser.png)