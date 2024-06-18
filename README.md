

**JS + CSS Clock** https://sayeh92.github.io/Clock/

This is a simple yet stylish clock created using HTML, CSS, and JavaScript. It features:

- Clean and elegant design with a background image (customizable!)
- Clear distinction between the hour, minute, and second hands
- Smooth animation for hand movement

**Features:**

* Uses CSS for styling the clock face, hands, and background.
* Employs JavaScript to update the clock hands dynamically every second.

**Setup:**

1. Save the code as an HTML file (e.g., clock.html).
2. You can replace the background image URL in the CSS with your own preference (see the `background` property in the `html` selector).

**How it Works:**

The HTML structure defines the basic clock layout with a container for the clock face and hands. The CSS styles the clock elements, including the background, size, and shadows. The JavaScript code performs the following key tasks:

- Selects the clock hand elements using querySelector.
- Gets the current hour, minute, and second using the Date object.
- Calculates the degree rotations for each hand based on their positions.
- Applies the calculated rotations and other styles to the hand elements using JavaScript's DOM manipulation capabilities.
- Uses `setInterval` to update the clock hands every second, creating the smooth animation effect.

**Customization:**

Feel free to experiment with the CSS to customize the look and feel of the clock! You can change:

* Background image URL (see `background` property in `html` selector)
* Font styles (see `font-family` in `html` selector)
* Clock size (adjust width and height of `.clock` class)
* Hand colors (modify the `background` property for each hand class: `.hour-hand`, `.min-hand`, `.second-hand`)
* Shadow effects (play around with the `box-shadow` property in the `.clock` class)

**By making small adjustments to the CSS, you can create a clock that perfectly matches your style!**
