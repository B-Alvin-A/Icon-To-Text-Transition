# Icon-To-Text-Transition
HTML and CSS snippet for creating buttons with an icon-to-text transition effect.

*: It sets the CSS box model to border-box for all elements, ensuring that padding and borders are included in the element's total width and height.

body: Styles the body element with a dark background color and centers its content both horizontally and vertically using flexbox.

button: Defines the common styles for the buttons. It sets the position to relative, sets the width and height, and removes default styles such as background, border, and outline. The buttons are displayed as flex containers, centering their content both horizontally and vertically. The --color CSS variable is used to control the color of the button.

button span: Styles the four spans inside the button, which are used for the transition effect. They are positioned absolutely and given a background gradient that starts transparent and ends with the --color variable. The animation properties are used to animate the spans in different directions (moveRight, moveDown, moveLeft, moveUp).

button p: Styles the paragraph element inside the button, which displays the text. Initially, it is scaled down to 0 and has a transition delay. When the button is hovered, it scales up to 1 and changes its color.

button i: Styles the <i> element inside the button, which represents the Font Awesome icon. It has a transition property for the icon to fade out when the button is hovered.

button:hover: Specifies the styles when the button is hovered. It changes the cursor to a pointer and adds a box-shadow effect.

button::before: Adds a pseudo-element before the button's content, which is used to create a diagonal transition effect. Initially, it has a width of 0, and when the button is hovered, its width expands to 100%.

The provided CSS code creates visually appealing buttons with a transition effect where the icons fade out, and the corresponding text slides in. You can customize the button styles by changing the --color variable and adjusting other CSS properties to match your desired design.
