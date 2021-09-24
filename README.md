# Solar System App- React.js

### See The Live Site [Solar System App](https://aldothedev.github.io/SolarSystem-React/)

### Built with

- Semantic HTML5 markup
- sass custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [parceljs](https://parceljs.org/) - sass compiler and bundler
- [gsap](https://greensock.com/get-started/) - animation library

### What I learned

- themes , applying different colours to the separate pages using sass.
[themes](https://www.sitepoint.com/dealing-color-schemes-sass/)

- animation, using the gsap library.
  - First , i tried using the import statement in the js file but did not work as that needs a compiler to use the es6 features in the browser.
  - i then used the cdn link by placing it in the body of the html file, just above the closing body tag. It is also important to place the cdn link above the js file to avoid `gsap undefined errors`
  - [Tabbed intefaces](https://inclusive-components.design/tabbed-interfaces/) . This was a major topic that i picked up in this challenge. The challenge includes 3 buttons like such that when clicked - they give related information in a separate panel. My first option was to use radio buttons but the above article gave a new dimension on how to handle the challenge.

### Continued development

- improving the accessibility of the site.
- improving tab control.

### Useful resources

- [Tabbed intefaces](https://inclusive-components.design/tabbed-interfaces/)
- [themes](https://www.sitepoint.com/dealing-color-schemes-sass/)
- [gsap](https://greensock.com/get-started/)
- [navigation menu button example](https://www.w3.org/TR/wai-aria-practices/examples/menu-button/menu-button-links.html)
