# COLLOQUIUM'26 - Debugging Challenge

## 🐛 Bug Summary
1. Easy: Missing closing tag in the Hero section paragraph (<p> instead of </p>).

2. Challenging (Mid): The Specificity Wall. A high-specificity CSS selector is used to style the navigation links, making it impossible for participants to change link colors using a standard class until they understand CSS weight.

3. Challenging (Mid): The "Z-Index" Stacking Context. A transform property is added to a parent container. In CSS, applying a transform creates a new Stacking Context, which can cause elements with a lower z-index to suddenly appear on top of things they shouldn't.

4. Hard: An invisible div with pointer-events: auto acting as a click-shield.

5. Hardest: Missing id="home", preventing anchor navigation
