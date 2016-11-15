# Javascript Position
In this example, as the user scrolls down the page, a box slides into view if they get within 500 pixels of the footer. We will call this part of the page the end zone, and you need to work out the height at which the endZone starts. Every time the user scrolls, you then check the position of the scroll bar from the top of the page. If the scroll bar is further down the page than the start of the end zone, the box is animated into the page. If not, then the box is hidden. The HTML for this example contains an extra div element at the end of the page containing the advert. A lot of items have been added to the list to create a long page that scrolls.

## Components that make the app run
* Cache the window and advert.
* The height of the end zone is calculated, and stored in variable called endZone.
* The scroll event triggers an anonymous function every time the user scrolls up or down.
* A conditional statement checks if the user's position is further from the top of the page than the start of the end zone.
* If the condition returns true, the box slides in from the right-hand edge of the page. This takes 250 milliseconds.

## How to run the app?
* In your terminal:
```
git clone https://github.com/bostonhuman/javascript-position
```
* Open `position.html` to run the app.
