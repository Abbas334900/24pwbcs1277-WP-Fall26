# CS 224L Lab 03 & 04: CSS Fundamentals - Styling and Visual Design

**Course:** CS 224L Web Technologies
**Instructor:** Mr. Mohammad
**Department:** Computer Science
**University:** University of Engineering & Technology, Peshawar

## Overview

This comprehensive lab covers CSS fundamentals, selectors, styling techniques, visual effects, and modern CSS features. Students will learn to create responsive, visually appealing web pages using CSS.

## Learning Outcomes

By the end of this lab, students will be able to:

- ✓ Understand CSS syntax, rules, and selectors
- ✓ Apply various CSS selectors and combinators
- ✓ Style text content with fonts, colors, and spacing
- ✓ Work with background properties and images
- ✓ Style images and create visual effects
- ✓ Implement CSS box model properties
- ✓ Create gradients and shadow effects
- ✓ Apply CSS transformations and transitions

## Project Structure

```
Lab03-css/
├── index.html                 # Main dashboard with all tasks
├── README.md                  # This file
├── styles/
│   ├── main.css              # Global styles and utilities
│   ├── typography.css        # Font and text styling
│   ├── components.css        # Buttons, forms, cards, navigation
│   └── effects.css           # Gradients, shadows, animations
├── images/
│   ├── backgrounds/          # Background images
│   ├── gallery/              # Gallery images
│   └── icons/                # Icon images
├── exercises/                # PRACTICE EXERCISES
│   ├── selectors.html        # Exercise 1-3: Selectors & Combinators
│   ├── typography.html       # Exercise 7-9: Typography
│   ├── backgrounds.html      # Exercise 10-11: Backgrounds
│   └── images.html           # Exercise 12-13: Images
└── tasks/                    # MAIN LAB TASKS
    ├── task5-buttons.html    # Task 5: Button Styling
    ├── task6-forms.html      # Task 6: Form Styling
    ├── task7-cards.html      # Task 7: Card Components
    ├── task8-navigation.html # Task 8: Navigation Menus
    ├── task9-transforms.html # Task 9: CSS Transforms
    └── task10-effects.html   # Task 10: Advanced Effects
```

## Exercises (Part A): Practice Fundamentals

### Exercise 1-3: CSS Selectors & Combinators
**File:** `exercises/selectors.html`

Demonstrates:
- Element, class, ID, universal selectors
- Attribute selectors
- Descendant, child, adjacent sibling, general sibling combinators
- Pseudo-classes and pseudo-elements

### Exercise 7-9: Typography & Text Styling
**File:** `exercises/typography.html`

Demonstrates:
- Google Fonts implementation
- Font sizes (px, em, rem, %)
- Text alignment and decoration
- Text transformation and shadows
- Line height and letter spacing

### Exercise 10-11: Background Properties
**File:** `exercises/backgrounds.html`

Demonstrates:
- Solid colors and image backgrounds
- Linear, radial, and conic gradients
- Background repeat patterns
- Multiple background layers
- Blend modes and attachment

### Exercise 12-13: Image Styling
**File:** `exercises/images.html`

Demonstrates:
- Rounded corners and circular images
- Borders and shadows
- Hover effects and transitions
- CSS filters (blur, brightness, contrast, saturate)
- Object-fit and overlays

## Main Tasks (Part B): Apply Your Knowledge

### Task 5: Button Styling Collection
**File:** `tasks/task5-buttons.html`

Create a comprehensive button showcase featuring:
- **Sizes:** Small, normal, large, block
- **Colors:** Primary, secondary, success, danger, warning
- **Shapes:** Sharp, rounded, pill-shaped
- **States:** Hover, focus, active, disabled
- **Effects:** Shadows, gradients, transitions
- **Special:** Icon buttons, button groups, loading states

### Task 6: Form Styling
**File:** `tasks/task6-forms.html`

Design styled registration forms with:
- **Input Fields:** Text, email, password, tel, number
- **Focus States:** Visual feedback with colors and shadows
- **Error/Success States:** Red/green borders with messages
- **Form Elements:** Select dropdowns, checkboxes, radio buttons
- **Textarea:** Multi-line input with custom styling
- **Labels & Help Text:** Proper form organization
- **Buttons:** Submit, reset, and styled buttons

### Task 7: Card Component Design
**File:** `tasks/task7-cards.html`

Create professional cards including:
- **Product Cards:** With prices, ratings, badges, CTAs
- **Service Cards:** With icons, descriptions, feature lists
- **Team Member Cards:** Profile information and social links
- **Blog Cards:** Article previews with metadata
- **Styling:** Borders, shadows, rounded corners
- **Interactions:** Hover effects, transformations, image zoom
- **Responsive:** Grid layouts that adapt to screen size

### Task 8: Navigation Menu Styling
**File:** `tasks/task8-navigation.html`

Style multiple navigation types:
- **Horizontal Navigation:** Top nav bars with hover effects
- **Vertical Navigation:** Sidebar menus with active states
- **Centered Navigation:** Elegant centered menus with underlines
- **Button-style Navigation:** Navigation as clickable buttons
- **Dropdown Menus:** Multi-level navigation with hovers
- **Breadcrumb Navigation:** Hierarchical path display
- **Pagination:** Page navigation for content lists
- **Tab Navigation:** Tabbed interface for content switching

### Task 9: CSS Transform Gallery
**File:** `tasks/task9-transforms.html`

Showcase all CSS transformations:
- **Translate:** Moving elements in X, Y, and diagonal directions
- **Rotate:** 2D and 3D rotation effects
- **Scale:** Uniform and asymmetric scaling
- **Skew:** Distortion along X and Y axes
- **3D Transforms:** rotateX, rotateY, rotateZ
- **Transform Origin:** Custom pivot points
- **Combined Transforms:** Multiple effects on single elements
- **Transitions:** Smooth animation between states

### Task 10: Advanced Effects Showcase
**File:** `tasks/task10-effects.html`

Implement cutting-edge CSS techniques:
- **Gradient Text:** Text clipping with background gradients
- **Custom Checkboxes:** Styled form elements
- **Loading Animations:** CSS-based spinners and loaders
- **Shadow Effects:** Multi-layer and neon glows
- **Animated Borders:** Dynamic border animations
- **Glassmorphism:** Frosted glass effect with blur
- **Particle Animation:** Floating background elements
- **Filter Combinations:** Multiple filter effects
- **Blend Modes:** Creative color mixing effects

### Tasks 11-13: Practical Implementation
Apply everything you learned to your own projects:

**Task 11: Personal Portfolio Styling**
- Apply CSS to your Lab 02 portfolio project
- Create a cohesive color scheme
- Style typography for readability
- Add visual depth with shadows and gradients
- Implement hover effects on interactive elements

**Task 12: Course Website Styling**
- Style the course schedule table from Lab 02
- Add zebra striping for readability
- Implement hover effects on table rows
- Use color coding for different course types
- Make the table responsive

**Task 13: GitHub Pages Enhancement**
- Update your GitHub Pages site with custom CSS
- Implement a consistent color scheme
- Improve typography and spacing
- Add visual effects to images
- Ensure responsive design across devices

## CSS Key Concepts

### 1. CSS Selectors
```css
/* Element */
p { color: blue; }

/* Class */
.highlight { background: yellow; }

/* ID */
#header { font-size: 2rem; }

/* Attribute */
input[type="text"] { border: 1px solid #ccc; }

/* Combinators */
div p { } /* Descendant */
div > p { } /* Child */
h2 + p { } /* Adjacent Sibling */
h2 ~ p { } /* General Sibling */
```

### 2. Box Model
```css
.box {
    margin: 20px;      /* Outside space */
    padding: 15px;     /* Inside space */
    border: 2px solid; /* Border */
    box-sizing: border-box; /* Include border in width/height */
}
```

### 3. Typography
```css
body {
    font-family: 'Segoe UI', Arial, sans-serif;
    font-size: 16px;
    line-height: 1.6;
    letter-spacing: 0.5px;
    text-alignment: left;
}
```

### 4. Colors & Gradients
```css
.background {
    background: linear-gradient(135deg, #3498db 0%, #e74c3c 100%);
    color: white;
}
```

### 5. Shadows & Effects
```css
.card {
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
    border-radius: 8px;
    transition: all 0.3s ease;
}

.card:hover {
    box-shadow: 0 12px 24px rgba(0, 0, 0, 0.2);
    transform: translateY(-4px);
}
```

### 6. Transforms
```css
.element {
    transform: translate(10px, 20px) rotate(45deg) scale(1.2);
    transition: transform 0.3s ease;
}
```

### 7. Animations
```css
@keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
}

.fade {
    animation: fadeIn 0.5s ease forwards;
}
```

## CSS Files Overview

### main.css
Global styles, variables, and utilities:
- CSS custom properties (variables)
- Reset styles
- Typography base styles
- Container and layout
- Button styles
- Utility classes

### typography.css
Font and text styling:
- Google Fonts imports
- Font family demonstrations
- Font sizes (px, em, rem, %)
- Text alignment
- Text decoration and transformation
- Text shadows
- Line height and spacing

### components.css
Reusable components:
- Navigation menus
- Button variations
- Form elements
- Cards
- Badges and alerts
- Dropdown menus
- States and interactions

### effects.css
Visual effects and animations:
- Gradients (linear, radial, conic)
- Shadows (soft, dark, colored, glow)
- Transforms (2D and 3D)
- Transitions
- Animations (@keyframes)
- Filters
- Blend modes
- Clip paths

## Best Practices

1. **Use CSS Variables:** Define colors and sizes in `:root` for easy customization
   ```css
   :root {
       --primary-color: #3498db;
       --secondary-color: #e74c3c;
   }
   ```

2. **Mobile First:** Design for mobile screens first, enhance for larger screens
   ```css
   /* Mobile first */
   .card { width: 100%; }
   
   @media (min-width: 768px) {
       .card { width: 50%; }
   }
   ```

3. **Performance:** Use CSS transforms instead of JavaScript animations
   - `transform` and `opacity` are GPU-accelerated
   - Avoid animating width/height/left/top

4. **Accessibility:** Ensure sufficient color contrast and keyboard navigation
   - Minimum 4.5:1 contrast ratio for text
   - Always visible focus states
   - Keyboard navigation support

5. **Organization:** Separate styles into logical files
   - main.css: Global styles
   - typography.css: Font styles
   - components.css: Component styles
   - effects.css: Visual effects

6. **Specificity:** Keep specificity low for easier maintenance
   - Use classes instead of IDs
   - Avoid nested selectors
   - Use OOCSS (Object-Oriented CSS)

7. **Browser Testing:** Test in multiple browsers
   - Chrome, Firefox, Safari, Edge
   - Mobile browsers (iOS Safari, Chrome Mobile)
   - Older browsers if needed

## Using the Live Server

To view the project with live reload:

1. Open the project in VS Code
2. Install the Live Server extension
3. Right-click on `index.html`
4. Select "Open with Live Server"
5. The project will open in your default browser

## VS Code Extensions Recommended

- **Live Server:** Live reload for development
- **CSS Peek:** Quick CSS file navigation
- **Color Picker:** Color selection and conversion
- **Prettier:** Code formatting
- **Thunder Client:** API testing (for future labs)

## Submission Checklist

- [ ] All exercises completed (exercises/ folder)
- [ ] Tasks 5-10 completed (tasks/ folder)
- [ ] CSS files organized properly (styles/ folder)
- [ ] Responsive design tested on mobile
- [ ] All links working correctly
- [ ] No console errors
- [ ] Code properly formatted and commented
- [ ] README.md updated (this file)
- [ ] Project uploaded to GitHub

## Resources

### CSS References
- [MDN CSS Documentation](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [CSS Tricks](https://css-tricks.com/)
- [Can I Use](https://caniuse.com/) - Browser compatibility

### Fonts
- [Google Fonts](https://fonts.google.com/)
- [Font Awesome](https://fontawesome.com/) - Icons

### Tools
- [ColorHunt](https://colorhunt.co/) - Color palettes
- [Coolors](https://coolors.co/) - Color scheme generator
- [CSS Gradient](https://cssgradient.io/) - Gradient generator
- [Box Shadow](https://box-shadow.dev/) - Shadow generator

### Learning Resources
- [Codecademy CSS Course](https://www.codecademy.com/learn/learn-css)
- [freeCodeCamp CSS Tutorial](https://www.youtube.com/watch?v=OXGznpKZ_sA)
- [Web.dev CSS Learning Path](https://web.dev/learn/css/)

## Troubleshooting

### Styles not applying?
- Check if CSS file is linked correctly
- Use browser DevTools (F12) to inspect elements
- Check CSS specificity and cascade
- Use `!important` as a last resort (not recommended)

### Images not showing?
- Check image file paths
- Use relative paths: `../images/image.jpg`
- Ensure image dimensions are set
- Check browser console for 404 errors

### Responsive design issues?
- Check viewport meta tag in HTML
- Use CSS media queries for breakpoints
- Test with browser DevTools responsive mode
- Ensure images are responsive (max-width: 100%)

## Contact & Support

For questions or issues:
1. Review the MDN CSS documentation
2. Check CSS Tricks for solutions
3. Ask your instructor during lab hours
4. Post on the course forum if available

## License

© 2024 University of Engineering & Technology, Peshawar. All rights reserved.

---

**Last Updated:** March 2026
**Version:** 1.0
