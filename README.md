# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). 


### Screenshot

![recipe-page](./design/destkop-design.jpg)


### Links

- Solution URL: [GitHub](https://github.com/JuliAlchemDev/FM-Recipe-page)
- Live Site URL: [Netlify](https://fm-social-recipe-page-julialchem.netlify.app)

## My process

1. **Implementing Semantic HTML and BEM Naming**

While building the HTML structure, I focused on keeping it semantic and accessible.  
At first, I used `<th>` for both the nutrition names and values to emphasize the numbers, but later realized it wasn’t correct — only the row headers should use `<th>`. I also learned the importance of adding `scope="row"` for accessibility.  

For BEM naming, I initially used section-specific classes like `recipe-card__nutrition-title` or `recipe-card__instructions-title`, but that limited reusability. I refactored them into a shared class, `recipe-card__sub-title`, which keeps the code cleaner and easier to scale.

2. **Responsive images (mobile-first approach)**
While adding images, I created multiple files for mobile, tablet, desktop, and high-resolution screens. I implemented `srcset` and `sizes` attributes to ensure responsive loading, and added `width` and `height` attributes to preserve layout and prevent content shifts. I’ll finalize the responsive behavior once the styles are applied so the images match their container widths accurately.

Problems:

1. Stuck with table's tr border-bottom 


...


### What I learned

...


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow
- BEM methodology
- Grid and relative units
- Figma design as reference

...

## Author

- Linkedin - [Julia Alkhimova](https://www.linkedin.com/in/julialkhimova/)
- Frontend Mentor - [@JuliAlchemDev](https://www.frontendmentor.io/profile/JuliAlchemDev)