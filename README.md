## Smooth Scrolling Library (Vanilla JS)

```Javascript
// Get Triggers Element
let scrollToggle = document.querySelectorAll(<triggers-links>);

// For each smooth scroll link
scrollToggle.forEach(function (toggle) {

    // When the smooth scroll link is clicked
    toggle.addEventListener('click', function (e) {
        // Prevent the default link behavior
        e.preventDefault();
        
        // Get anchor link and calculate distance from the top
        let dataID = toggle.getAttribute('href');
        let dataTarget = document.querySelector(dataID);
        
        // If the anchor exists
        if (dataTarget) {
            // Scroll to the anchor
            smoothScroll(dataTarget, <duration>);
        }
    }, false);
});
```


## WA Spam (Vanilla JS)

```Javascript
let text = string
let message = message

//Lyrics Prank
lyricsPrank(text)

//Bomb Prank
bombPrank(message, count)
```
