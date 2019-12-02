# New-York-Times-Clone

## Main Content Section

The main content of the page (being the actual article and the right side sections) was made by creating some `<section>` tags only divided by the *Advertisement* spaces which are individual `<div>` tags.

Since the main article container has already a *fixed* width and its container won't change even if the viewport does (because of it being at its minimal width already) the horizontal centering was achieved by using the `padding` property with an absolute value to its left and so allow the *aside* boxes to align using only the `float` property.

The top bar icons were made using [Font Awesome](https://fontawesome.com/) and were contained and aligned with *flexboxes*

As for each image, they were wrapped inside `<figure>` tags and took advantage of the `<figcaption>` elements to describe what was shown above.
