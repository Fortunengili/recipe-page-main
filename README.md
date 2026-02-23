# Recipe page

# Overview

This project involved recreating a responsive recipe layout based on provided design files. The primary goal was to translate a static visual design into a clean, structured HTML and CSS implementation while maintaining layout accuracy, spacing consistency, and responsive behavior.

![Recipe Page Screenshot](./screenshot.jpg)

🔗 Links

Solution URL: https://www.frontendmentor.io/solutions/your-solution-link

Live Site URL: https://your-live-site-link.com

(Replace with your actual links)

# My process
🛠 Built with

Semantic HTML5 markup

CSS custom styling

Flexbox layout


# What I learned

This challenge reinforced several foundational frontend concepts:

✔ Proper content structuring using semantic HTML
✔ The importance of container-based layouts
✔ Centering strategies using Flexbox
✔ Correct table markup and alignment techniques
✔ Spacing consistency and visual hierarchy

One key correction involved fixing improper table structure. Initially, rows were incorrectly defined without table data cells. The proper implementation:

<table>
  <tr>
    <td>Calories</td>
    <td>277kcal</td>
  </tr>
</table>

This highlighted how browsers interpret table layouts strictly based on valid HTML hierarchy.

Another important improvement involved centering the card layout using Flexbox:

body{
  display: flex;
  justify-content: center;
}

This created predictable layout behavior across screen sizes.

# Continued development

Going forward, I plan to focus on:

✔ Improving responsive layout precision
✔ Refining spacing systems and typography scales
✔ Building reusable UI components
✔ Strengthening CSS architecture practices
✔ Expanding into component-driven frameworks

# Useful resources

Frontend Mentor community solutions


# Author

Frontend Mentor – https://www.frontendmentor.io/profile/Fortunengili
GitHub – https://github.com/Fortunengili/recipe-page-main

# Acknowledgments

Frontend Mentor for providing structured, design-driven challenges that simulate practical frontend development scenarios.
