# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). 


### Screenshot

![recipe-page](./design/desktop-design.jpg)


### Links

- Solution URL: [GitHub](https://github.com/JuliAlchemDev/FM-Recipe-page)
- Live Site URL: [Netlify](https://fm-recipe-page-julialchem.netlify.app)

## My process

1. **Implementing Semantic HTML and BEM Naming** 

While building the HTML structure, I focused on keeping it semantic and accessible.  
At first, I used `<th>` for both the nutrition names and values to emphasize the numbers, but later realized it wasn’t correct — only the row headers should use `<th>`.  
I also learned the importance of adding `scope="row"` for accessibility.  

For BEM naming, I initially used section-specific classes like `recipe-card__nutrition-title` or `recipe-card__instructions-title`, but that limited reusability.  
I refactored them into a shared class, `recipe-card__sub-title`, which keeps the code cleaner and easier to scale.

2. **Responsive Images (Mobile-First Approach)** 

While adding images, I created multiple files for **mobile, tablet, desktop, and high-resolution** screens.  
I implemented `srcset` and `sizes` attributes to ensure responsive image loading and added `width` and `height` attributes to prevent layout shifts (CLS).  
I’ll finalize responsive behavior later when all styles are in place to ensure images fit their containers perfectly.



### Problems & To-Dos

1. Got stuck styling the table’s `tr` border — couldn’t quite match the spacing between text and line, so it goes to the **to-do list**.  
2. Had trouble customizing list markers, so I used a `<p>` wrapper and styled bullets and numbers using `::before` and `counter(step)` — my first time using CSS counters!  
3. Will need to polish small details later (like cleaning unused CSS and fine-tuning spacing).


### What I learned

- The importance of correct use of `<th>` and `scope` for accessibility.  
- How to handle **responsive images** with `srcset` and `sizes`.  
- How to simulate custom list markers with pseudo-elements and counters.  
- The value of keeping all design tokens (colors, fonts, spacing) as **CSS variables** for scalability.  
- Practiced a **mobile-first** workflow and layout building using Grid and relative units.  


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow
- BEM methodology
- Grid and relative units
- Figma design as reference

## Author

- Linkedin - [Julia Alkhimova](https://www.linkedin.com/in/julialkhimova/)
- Frontend Mentor - [@JuliAlchemDev](https://www.frontendmentor.io/profile/JuliAlchemDev)