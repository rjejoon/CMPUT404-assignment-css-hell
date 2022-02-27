Assignment: CSS Hell
====================

You will skin 3 project gutenberg stories with custom CSS.

You will skin 2 versions of a possible professional homepage for your
self with 2 versions of CSS.

Read requirements.org

Read this comic http://theoatmeal.com/comics/design_hell

git clone https://github.com/abramhindle/CMPUT404-assignment-css-hell.git

Part I
=================
**Modifications**

1. In line 95 of *3.html*, added an image caption.

Before:
```html
<img src="images/cover.jpg" style="width:100%;" alt="cover" />
```
After: 
```html
<figure>
    <img src="images/cover.jpg" style="width:100%;" alt="cover" />
    <figcaption>Book Cover</figcaption>
</figure>
```

2. Added css stylesheet to each gutenberg HTML files.
```html
<link rel="stylesheet" href="./theme.css">
```

License/Copyright
=================

Textual content is copyright Abram Hindle (C) 2013 under the CC-BY-SA
4.0 unported license. Attribution should be a hyperlink to the
repository and (C) 2013 Abram Hindle visibile in the text.

Code is licensed under the Apache 2.0 license.


