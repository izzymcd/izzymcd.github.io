---
name: create-page
description: "Use when: creating a new HTML page for the Nails by Izzy website. Creates a well-structured, responsive HTML page following project conventions with proper semantic HTML, accessibility, and mobile-first design."
---

# Create Page Skill

Creates a new HTML page for the Nails by Izzy static website with proper structure and conventions.

## Input

- `pageName`: Name of the page (e.g., "services", "gallery", "contact")
- `pageTitle`: Display title for the page
- `navItems`: Array of navigation items to include

## Output

Creates:
1. `{pageName}.html` - The HTML page file
2. Updates `style.css` with page-specific styles if needed

## Conventions

### HTML Structure
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Page Title | Nails by Izzy</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header>
    <nav>...</nav>
  </header>
  <main>...</main>
  <footer>...</footer>
</body>
</html>
```

### CSS Conventions
- Use CSS custom properties for colors
- Follow BEM naming: `.block__element--modifier`
- Mobile-first responsive with `@media (min-width: 768px)`
- Max content width: 1200px

### Color Palette
- Primary: #E8B4B8 (dusty rose)
- Background: #FFFEF9 (warm white)
- Text: #4A4A4A (dark gray)
- Accent: #D4A5A5 (muted rose)