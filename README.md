# Portfolio Website

A stunning, fully responsive single-page portfolio website built using HTML, CSS, and Vanilla JavaScript.

## Features
- **Classy, Elegant Design**: Features a refined dark color palette (deep navy / charcoal) and cream accents.
- **Premium Typography**: Uses Playfair Display for headings and Inter for body text.
- **Smooth Animations**: Includes scroll-triggered fade-in animations via IntersectionObserver, hover lifts on cards, and smooth scroll behaviors.
- **Responsive**: Mobile-first design that adapts beautifully to tablets and desktop screens.
- **Interactive Lightbox**: Vanilla JS lightbox for viewing certificate images in full-screen.
- **Dynamic Elements**: Sticky navbar with scroll-spy highlight, dynamic footer year, and a customized preloader.

## File Structure
- `index.html`: Main HTML document with all sections.
- `css/style.css`: Contains CSS variables, layout styling, and animations.
- `js/main.js`: Handles interactivity, intersection observer, lightbox, and navigation logic.
- `assets/`: Directory meant for images and your PDF resume.

## Setup and Usage
1. Open the project folder.
2. Open `index.html` in any modern web browser.
3. **Customization:**
   - **Colors & Fonts**: Edit the `:root` variables at the top of `css/style.css`.
   - **Images**: Replace the Unsplash placeholder image URLs in `index.html` with your actual image paths. Place your local images in `assets/images/`.
   - **Resume**: Save your actual generated PDF resume to the `assets` folder as `cv.pdf` to replace the iframe preview and download link.

## Technologies Used
- HTML5
- CSS3 (Variables, Flexbox, Grid, Animations)
- Vanilla JavaScript
- FontAwesome (Icons)
- DevIcons (Tech Stack Icons)
- Google Fonts
