# Static Web Page Project

This repository contains a static web page project. A static web page is a website that displays the same content to every visitor, without requiring server-side processing or databases. It consists of HTML, CSS, and JavaScript files that are served directly to the browser.

## What is a Static Web Page?

A static web page is built using:
- **HTML** - Structure and content of the page
- **CSS** - Styling and visual design
- **JavaScript** - Interactive functionality and dynamic behavior

Static websites are:
- Fast to load
- Easy to host
- Secure (no server-side vulnerabilities)
- Cost-effective
- SEO-friendly

## Step-by-Step Guide to Create a Static Web Page

### Step 1: Project Setup
1. Clone this repository or create a new folder for your project
2. Create the basic file structure (see recommended structure below)

### Step 2: Create the HTML Structure
1. Create an `index.html` file as your main page
2. Add the basic HTML5 structure:
   ```html
   <!DOCTYPE html>
   <html lang="en">
   <head>
       <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>Your Page Title</title>
       <link rel="stylesheet" href="styles.css">
   </head>
   <body>
       <header>
           <!-- Navigation and header content -->
       </header>
       <main>
           <!-- Main page content -->
       </main>
       <footer>
           <!-- Footer content -->
       </footer>
       <script src="script.js"></script>
   </body>
   </html>
   ```

### Step 3: Add CSS Styling
1. Create a `styles.css` file
2. Add CSS rules to style your HTML elements:
   ```css
   /* Basic reset and styling */
   * {
       margin: 0;
       padding: 0;
       box-sizing: border-box;
   }
   
   body {
       font-family: Arial, sans-serif;
       line-height: 1.6;
       color: #333;
   }
   
   /* Add your custom styles here */
   ```

### Step 4: Add JavaScript Functionality
1. Create a `script.js` file
2. Add interactive features:
   ```javascript
   // DOM content loaded event
   document.addEventListener('DOMContentLoaded', function() {
       // Your JavaScript code here
       console.log('Page loaded successfully!');
   });
   ```

### Step 5: Enhance Your Content
1. Add semantic HTML elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`)
2. Include images in an `images/` or `assets/` folder
3. Optimize for mobile responsiveness using CSS media queries
4. Add meta tags for SEO

### Step 6: Testing
1. Open `index.html` in a web browser to test locally
2. Test on different devices and screen sizes
3. Validate HTML using [W3C Markup Validator](https://validator.w3.org/)
4. Check CSS with [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)

## Recommended File Structure

```
static_web/
├── index.html          # Main HTML file
├── styles.css          # Main CSS file
├── script.js           # Main JavaScript file
├── images/             # Image assets
│   ├── logo.png
│   └── background.jpg
├── assets/             # Other assets (fonts, icons, etc.)
│   ├── fonts/
│   └── icons/
├── pages/              # Additional HTML pages
│   ├── about.html
│   └── contact.html
└── README.md           # Project documentation
```

## Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Styling, layout, and responsive design
- **JavaScript** - Interactive functionality
- **Git** - Version control

## Development Workflow

1. **Plan**: Sketch your layout and plan the content structure
2. **HTML First**: Create the HTML structure with semantic elements
3. **Style with CSS**: Add styling progressively from mobile to desktop
4. **Add Interactivity**: Enhance with JavaScript features
5. **Test**: Test across different browsers and devices
6. **Optimize**: Optimize images, minify code, and improve performance
7. **Deploy**: Upload to a web hosting service

## Deployment Options

### Free Hosting Services
- **GitHub Pages** - Host directly from this repository
- **Netlify** - Drag and drop deployment
- **Vercel** - Git-based deployment
- **Surge.sh** - Simple command-line deployment

### GitHub Pages Deployment
1. Go to repository Settings
2. Scroll to Pages section
3. Select source: Deploy from a branch
4. Choose `main` branch and `/ (root)` folder
5. Your site will be available at `https://username.github.io/repository-name`

## Best Practices

- Use semantic HTML elements
- Write clean, readable code
- Optimize images for web (use WebP format when possible)
- Implement responsive design
- Add proper meta tags for SEO
- Test accessibility with screen readers
- Validate your HTML and CSS
- Use version control (Git) for tracking changes

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/nimeshayasith/static_web.git
   cd static_web
   ```

2. Start building your static web page by creating the files mentioned in the structure above

3. Open `index.html` in your browser to see your changes

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).

---

Happy coding! 🚀