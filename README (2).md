# TechVerse – Web Store

A responsive, single-page tech store website built with **HTML, CSS and JavaScript**. It shows a product gallery, a pricing table, a pulsing animated title and a one-click **dark/light mode** switch.

## Preview

| Light mode | Dark mode |
|---|---|
| ![Light mode - top of the page](screenshotslight-top.png) | ![Dark mode - top of the page](screenshotsdark-top.png) |
| ![Light mode - products and pricing](screenshotslight-bottom.png) | ![Dark mode - products and pricing](screenshotsdark-bottom.png) |

## Features

- Animated hero title (CSS `@keyframes` fade and scale)
- Dark/Light mode toggle button (JavaScript)
- Navigation bar with smooth in-page links (About, Features, Gallery, Pricing) and an external link
- "Why Choose Us?" feature list
- Featured products gallery with 5 images
- Product catalog table with item, category, stock status and price
- Responsive layout: on screens under 600 px the menu stacks vertically and the images fill the full width

## Built with

- HTML5 (semantic sections, table, lists)
- CSS3 (Flexbox, animations, transitions, media queries)
- Vanilla JavaScript (no frameworks or libraries)

## Project structure

```
techverse-web-store/
├── index.html          # Page structure and content
├── styles.css          # Styling, animation, dark mode, responsive rules
├── script.js           # Dark/Light mode toggle function
├── img1.jfif           # Gallery image 1
├── img2.jfif           # Gallery image 2
├── img3.jfif           # Gallery image 3
├── img4.jfif           # Gallery image 4
├── img5.jfif           # Gallery image 5
├── screenshots/        # Preview images used in this README
│   ├── light-top.png
│   ├── light-bottom.png
│   ├── dark-top.png
│   └── dark-bottom.png
└── README.md
```

## How it works

Clicking the toggle button calls `toggleTheme()` in `script.js`, which adds or removes the `dark-mode` class on the `<body>`. The CSS then switches the colors, and the `transition` property makes the change smooth.

```js
function toggleTheme() {
  document.body.classList.toggle("dark-mode");
}
```

## How to run

1. Download or clone this repository:
   ```
   git clone https://github.com/YOUR-USERNAME/techverse-web-store.git
   ```
2. Open the folder.
3. Double-click `index.html` to open it in your browser. No installation or server is needed.

## Deploy for free with GitHub Pages

1. Push the project to a GitHub repository.
2. Go to **Settings > Pages**.
3. Under **Branch**, choose `main` and `/ (root)`, then click **Save**.
4. After a minute your site will be live at `https://YOUR-USERNAME.github.io/techverse-web-store/`.

## Ideas for improvement

- Remember the chosen theme with `localStorage`
- Add a shopping cart with JavaScript
- Add product names and prices under each gallery image
- Make the table match the gallery products
- Add a contact form and footer

## What I learned

- Building a page with semantic HTML sections, lists, images and tables
- Creating CSS animations and responsive layouts with media queries
- Using JavaScript to change the page by toggling a CSS class

## Disclaimer

This is an educational, non-commercial practice project. TechVerse is a fictional store. The product images show products owned by Apple Inc., whose names and logos are trademarks of Apple. This project is not affiliated with or endorsed by Apple. Replace the images with your own or free-to-use photos if you plan to publish it as a real site.

## Author

**W.M. Tharindu Nadeeshan Wijesekera**
Badulla, Sri Lanka
LinkedIn: [linkedin.com/in/tharindu-w-81156a334](https://linkedin.com/in/tharindu-w-81156a334)
