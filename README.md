# End Zone Position

In this example, as the user scrolls down the page, a box slides into view if they get within 500 pixels of the footer. We will call this part of the page the end zone, and you need to work out the height at which the endZone starts. Every time the user scrolls, you then check the position of the scroll bar from the top of the page. If the scroll bar is further down the page than the start of the end zone, the box is animated into the page. If not, then the box is hidden.

## How to calculate the end zone

1. Getting the height from the top of the page to the top of the footer in pixels.
2. Subtracting the height of the viewport from this result.
3. Substracting a further 500px for the area where the box will come into view.

![000](https://cloud.githubusercontent.com/assets/18538482/16627450/5f9b2b24-437b-11e6-9fdd-b259fa80212f.png)

## How to run the app in local machine?

1. In your own terminal type:
```
git clone https://github.com/bostonhuman/end-zone-position
```
2. Open `position.html` to run the app.
