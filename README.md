# Microsoft Clone

This project is a static clone of the Microsoft website, built with HTML, CSS, and JavaScript, with React integration.

## Files Description

### index.html
The main HTML file that structures the webpage. It includes:
- Navigation bar with Microsoft logo and menu items (Microsoft 365, Windows, Surface, Xbox, Copilot, Support).
- Search functionality and shopping cart links.
- Showcase section promoting Surface deals.
- Home cards sections displaying various Microsoft products and services (Surface Pro, Surface Laptop, Xbox, Microsoft Edge, Teams, Windows 10, etc.).
- Xbox Game Pass section.
- Carbon negative commitment section.
- Follow the section with social media links and a React root element.
- Footer with links and copyright information.

The HTML also includes Font Awesome icons and links to external stylesheets.

### style.css
The CSS file that provides styling for the entire webpage, including:
- Layout for the container, navigation, showcase, cards, sections, and footer.
- Responsive design elements.
- Dark theme for certain sections.
- Menu button animations and mobile menu toggle styles.

### work.js
The JavaScript file that handles interactive elements and React rendering:
- Menu button toggle functionality: Adds/removes 'show' class to the main menu and 'open' class to the menu button for animation.
- React component: Defines an `App` component that renders an `<h2>Welcome to Microsoft</h2>` heading.
- ReactDOM.render: Renders the App component into the element with id 'react-root' in the HTML.

React is used here to demonstrate component-based rendering for dynamic content. In this case, it renders a simple welcome message into a specific div, allowing for future expansion into more complex UI components while keeping the rest of the page as static HTML.

## How to Run
1. Ensure you have a modern web browser.
2. Open `index.html` in your browser.
3. Note: The React part requires Babel for JSX transformation. 

## Technologies Used
- HTML5
- CSS3
- JavaScript
- React (for component rendering)
- Font Awesome (for icons)

## Features
- Responsive navigation with mobile menu
- Product showcase and promotional sections
- Social media links
- Footer with comprehensive links
- Interactive menu button
- React-powered welcome message
