# JS30-5-FlexPanelGallery

# Flex Panels 💪

This project is part of Wes Bos's "30 Days of JavaScript" challenge, specifically Day 5: **Flex Panels Image Gallery**. It demonstrates the use of CSS Flexbox combined with JavaScript for creating interactive, animated panels.

## Project Overview

The Flex Panels project showcases a simple and responsive image gallery using flexbox. The panels expand and shrink when clicked, creating a dynamic and engaging user experience. Each panel contains text that slides into view when the panel is expanded.

### Features

- **CSS Flexbox**: Used to create a flexible and responsive layout for the panels.
- **Smooth Transitions**: CSS transitions provide a smooth animation when the panels are clicked.
- **JavaScript Interaction**: Panels are clickable and expand or collapse with JavaScript event listeners.
- **Responsive Design**: The layout adapts to various screen sizes using the flex properties.

## Demo

Click on a panel to expand it. The text inside the panel will slide into view, and the panel will grow in size. Clicking on the panel again will collapse it.

## Technologies Used

- **HTML**: For structuring the page.
- **CSS (Flexbox)**: For creating a responsive and flexible layout.
- **JavaScript**: For handling user interaction and toggling panel states.

## How It Works

1. **HTML**: The page contains five panels, each with background images and text content.
2. **CSS**: Flexbox is used to align and size the panels. Transitions are applied to handle animations for expanding the panels and sliding the text in.
3. **JavaScript**:
   - Panels are selected using `document.querySelectorAll()`.
   - An event listener is added to each panel to toggle the `open` class when clicked, which triggers the flex-grow CSS transition.
   - Another event listener checks when the transition ends (triggered by `flex-grow`) and toggles the `open-active` class to control the text sliding animation.

## How to Run the Project

1. Download or clone the repository.
2. Open the `index.html` file in your browser.
3. Click on any panel to see the animation in action.

## Credits

This project is part of Wes Bos's [JavaScript 30](https://javascript30.com/) course, an excellent free resource to improve your JavaScript skills.
