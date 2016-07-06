# End Zone Position

In this example, as the user scrolls down the page, a box slides into view if they get within 500 pixels of the footer. We will call this part of the page the end zone, and you need to work out the height at which the endZone starts. Every time the user scrolls, you then check the position of the scroll bar from the top of the page. If the scroll bar is further down the page than the start of the end zone, the box is animated into the page. If not, then the box is hidden.

## How to calculate the end zone

1. Getting the height from the top of the page to the top of the footer in pixels.
2. Subtracting the height of the viewport from this result.
3. Substracting a further 500px for the area where the box will come into view.
