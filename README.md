# CS381 - Web Application Development

Interactive lecture slides for the **Web Application Development** course at Yanbu Industrial College, Computer Science and Engineering Department.

## Overview

This repository contains browser-based presentation slides built with [reveal.js](https://revealjs.com). The course covers full-stack web development from HTML/CSS fundamentals to PHP/MySQL backend development and web security.

## Course Modules

| Module | Topic | Status |
|--------|-------|--------|
| 01 | Foundations and Modern Web Development | Available |
| 02 | HTML5 | Available |
| 03 | CSS | Available |
| 04 | JavaScript Fundamentals | Available |
| 05 | PHP Fundamentals | Available |
| 06 | MySQL Database and PHP Integration | Available |
| 07 | Authentication, Authorization & Security | Available |

## Technologies Covered

- **Frontend:** HTML5, CSS3 (Flexbox, Grid, Responsive Design), JavaScript (ES6+)
- **Backend:** PHP 8.x
- **Database:** MySQL 8.x with PDO
- **Tools:** Git, GitHub, Browser DevTools, Laragon
- **Concepts:** Semantic HTML, Accessibility (ARIA), BEM, OWASP Security

## Getting Started

### Option 1: Local Web Server (Recommended)

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/cs381-slides.git
   ```

2. Place the folder in your web server's document root:
   - **Laragon:** `D:\laragon\www\cs381`
   - **XAMPP:** `C:\xampp\htdocs\cs381`
   - **MAMP:** `/Applications/MAMP/htdocs/cs381`

3. Start your local server and navigate to:
   ```
   http://localhost/cs381
   ```

### Option 2: Direct File Access

Simply open `index.html` in a modern web browser. Note: Some features may be limited without a web server.

## Slide Navigation

| Key | Action |
|-----|--------|
| `←` `→` | Navigate between slides |
| `↑` `↓` | Navigate vertical slides |
| `F` | Toggle fullscreen |
| `Esc` | Slide overview |
| `S` | Speaker notes |
| `?` | Keyboard shortcuts |

## Project Structure

```
cs381/
├── index.html          # Course landing page
├── module1.html        # Module 1 slides
├── module2.html        # Module 2 slides
├── module3.html        # Module 3 slides
├── css/
│   └── theme.css       # Custom theme overrides
├── images/
│   ├── module_1/       # Module 1 images
│   ├── module_2/       # Module 2 images
│   └── module_3/       # Module 3 images
└── README.md
```

## Customization

### Changing Colors

Edit `css/theme.css` to modify the color scheme:

```css
:root {
    --primary: #2563eb;        /* Main accent color */
    --primary-dark: #1d4ed8;
    --text: #1e293b;           /* Body text */
    --text-muted: #64748b;     /* Secondary text */
}
```

### Adding New Slides

Each module is a standalone HTML file using reveal.js. Copy an existing module and modify the content within `<div class="slides">`.

## Contributing

Feel free to:
- Fork this repository
- Submit pull requests with improvements
- Report issues or suggest enhancements
- Use these slides for your own teaching

## Acknowledgments

### References & Resources

A special thanks to the following resources that were invaluable in creating this course content:

- **[W3Schools](https://www.w3schools.com)** - Comprehensive tutorials and references for HTML, CSS, JavaScript, PHP, and MySQL. An excellent resource for both beginners and experienced developers.
  - [HTML Tutorial](https://www.w3schools.com/html/)
  - [CSS Tutorial](https://www.w3schools.com/css/)
  - [Sass Tutorial](https://www.w3schools.com/sass/)
  - [JavaScript Tutorial](https://www.w3schools.com/js/)
  - [PHP Tutorial](https://www.w3schools.com/php/)
  - [MySQL Tutorial](https://www.w3schools.com/mysql/)

- **[MDN Web Docs](https://developer.mozilla.org)** - In-depth documentation and guides for web technologies.

- **[reveal.js](https://revealjs.com)** - The HTML presentation framework powering these slides.

- **[Font Awesome](https://fontawesome.com)** - Icons used throughout the presentations.

### Tools Used

- [Laragon](https://laragon.org) - Local development environment
- [Visual Studio Code](https://code.visualstudio.com) - Code editor
- [Highlight.js](https://highlightjs.org) - Syntax highlighting

## License

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).

You are free to:
- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material for any purpose, even commercially

Under the following terms:
- **Attribution** — You must give appropriate credit
- **ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the same license

## Author

**Muhammad Rafiq**
Computer Science and Engineering Department
Yanbu Industrial College
Royal Commission Yanbu Colleges and Institutes

---

*If you find these slides helpful, please consider giving the repository a star!*
