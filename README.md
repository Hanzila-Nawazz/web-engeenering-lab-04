LAB 04 - WEB ENGINEERING

HOW TO RUN
1. Extract the ZIP folder.
2. Open index.html in Chrome, Edge or Firefox.
3. Hover over the last button to see its transition. Tab focus also works.
No installation, internet connection or server is needed.

FILES
index.html: Page structure and all seven widgets.
style.css: Page styling and animations, with opening braces on the next line.

WIDGETS AND CONCEPTS
1. Pacman: Two semicircles rotate in opposite directions. The food moves left.
   transform-origin places the mouth's rotation point at the centre of Pacman.
2. Bouncing ball: translateY moves the ball down and up. ease-in accelerates
   its fall; ease-out slows its rise. This creates the required variable speed.
   A second animation moves it from right to left in 6 seconds (four bounces).
   It exits completely on the left and reappears from the right, repeating.
3. Windmill: rotate(360deg) turns the blades around their centre.
4. Loading spinner: A differently coloured top border rotates continuously.
5. Jumping dots: animation-delay staggers the dots to produce a sequence.
6. Colourful text: Keyframes change the colour and scale of the text.
7. Hover button: A transition smoothly changes the colour, scale and rotation
   when the button is hovered or focused.

BASIC CSS TERMS
@keyframes: Defines the stages of an animation during the whole process of animation.
transform: Moves, rotates or scales an element.
animation-duration: Time taken for one cycle (written in the animation shorthand aswell).
infinite: Repeats the animation continuously.
alternate: Plays successive cycles forwards and backwards for a particular animation.
transition: Smoothly changes a property when its value changes, e.g. on hover.

