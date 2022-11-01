# Position

- **static**
    - By default
    - Not affected by top, bottom, left, right
- **relative**
    - Relative to element's normal position
- **fixed**
    - Relative to the viewport
    - Stays in the same place even if the page is scrolled
- **absolute**
    - Relative to its nearest positioned ancestor
    - If no positioned ancestors are found, document body will be used
    - Takes the element out of the normal flow and can overlap other elements
    - moves along with page scrolling
- **sticky**
    - Positioned based on user's scroll position
    - Hybrid between relative and fixed
    - It's positioned relative until a given offset position in the viewport and then it stays fixed

Position must be set first before we can use top, bottom, left, right properties.

References: [W3Schools](https://www.w3schools.com/css/css_positioning.asp), 
[Mozillla](https://developer.mozilla.org/en-US/docs/Web/CSS/position),
[:arrow_forward:](https://www.youtube.com/watch?v=jx5jmI0UlXU&ab_channel=WebDevSimplified)

### Float property

- It specifies if an element should float on the left or right
- Elements that are positioned absolute will ignore this property
- Elements close to a floating element will flow around it. To avoid this the clear property can be used

References: [Mozilla](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Floats), 
[:arrow_forward:](https://www.youtube.com/watch?v=LrdkRMZhgZg)

Hands on: [Example 1](https://stackblitz.com/edit/web-platform-d28us6?file=styles.css), [Example 2](https://stackblitz.com/edit/web-platform-ftogmz?file=styles.css), [Float clearfix](https://stackblitz.com/edit/web-platform-zfmawu?file=styles.css)
