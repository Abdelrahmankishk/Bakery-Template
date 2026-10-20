# Bakery Website Template

A bakery website built using **HTML5 and CSS3**, recreating the design of the [Bakery Website](https://elnage.github.io/bakery/) as a front-end practice project.

## Live Demo

Explore the deployed website:

**[View Bakery Website](https://abdelrahmankishk.github.io/Bakery-Template/)**

## Features

- Full-screen hero section with a background image.
- Introduction section describing the bakery.
- Bakery location section.
- Baking products section featuring breads, bagels, and cookies.
- Contact information section with an embedded Google Map.
- Multi-column footer containing information about the bakery, opening hours, and contact details.

## Technologies Used

- **HTML5** — Website structure and content.
- **CSS3** — Styling, layouts, spacing, and visual presentation.
- **Google Fonts** — Typography using Alegreya Sans.
- **Google Maps Embed** — Displaying the bakery's location.

## Key Implementation Details

### 1. Float-Based Layout

The `float` property is used to position elements side by side, such as the two-column sections and the four-column footer.

```css
.left {
    float: left;
}

.right {
    float: right;
}
```

This technique was used to create multi-column layouts without relying entirely on modern layout systems.

### 2. Clearing Floats

A reusable `.clr` class clears floated elements, helping parent containers account for their floated children.

```css
.clr {
    clear: both;
}
```

### 3. Reusable Container

A shared `.container` class provides consistent width and horizontal alignment across website sections.

```css
.container {
    width: 90%;
    margin: auto;
}
```

### 4. Hero Section Background

The hero section uses CSS background properties to display a full-screen image while maintaining appropriate positioning and coverage.

```css
background-size: cover;
background-position: center;
```

### 5. Flexbox Alignment

Flexbox is used in selected components to align icons and text within list items.

## Project Structure

```text
Bakery-Template/
├── index.html
├── style.css
├── images/
└── Icons/
```

*The folders contain the website's images and icon assets.*

## Getting Started

To run the project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/Abdelrahmankishk/Bakery-Template.git
   ```

2. Open the project folder.
3. Open `index.html` in your browser.

You can also visit the [live demo](https://abdelrahmankishk.github.io/Bakery-Template/) to explore the deployed website without installing anything.

## Future Enhancements

- Add a responsive navigation bar with links to the website sections.
- Improve responsiveness for mobile phones, tablets, and different screen sizes.
- Refactor and organize CSS rules for better maintainability.
- Improve HTML semantics and accessibility.
- Enhance navigation and add interactive elements where appropriate.
- Optimize images and other assets to improve loading performance.
- Explore Flexbox and CSS Grid for alternative layout implementations.

## Credits

The project recreates the visual design of the [original Bakery Website](https://elnage.github.io/bakery/) using HTML and CSS.

This repository contains an independent implementation for front-end development practice.
