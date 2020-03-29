# Presentation

[Demo Site](https://xboudsady.github.io/presentation/)

Static HTML site for presentation using keyframes to take advantage of transitioning pages to pages.

Presentation website, that can be used at conferences, in lieu of Power Points. There is no scroll bar, will need to use button to transitions to next content.

* CSS Variables
* CSS Keyframe Animations
* CSS Transitions
* JavaScript for Smooth Scrolling
* Font Icon

## Technology Used
* [jQuery](https://jquery.com/) - jQuery is a fast, small, and feature-rich JavaScript library.
* [Font Awesome](https://fontawesome.com/) - Get vector icons and social logos on your website with Font Awesome, the web's most popular icon set and toolkit.

## Page Setup

Consisting of 4 view panels using the `section` element to group contents together. Set the view of each page of `height: 100vh` to take up the whole screen, and used `overflow: hidden` to turn off browser vertical scrolling.

Using **flexbox** we can set `display: flex` and `flex-direction: column` to stack the pages on top of each other.

Each `button` will use relative `<a>` to handle transitions between each section, and using the CSS properties of `transform: translateX()` and `transform: translateY()` to move between the pages via the link using `@keyframes` to handling the transitions smoothly.

### Sample Images

![Screen Capture](images/screen-capture-1.gif)