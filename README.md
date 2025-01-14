# Responsive_webpage

This project demonstrates a responsive webpage with a fixed navbar and footer, along with dynamic layout adjustments based on screen size. The page adapts seamlessly to both large and small devices using CSS and JavaScript.

## Features

1. **Fixed Navbar and Footer**:
   - The navbar stays at the top, and the footer remains at the bottom, regardless of scrolling.

2. **Responsive Layout**:
   - **Screen Width > 700px**: Sections (left menu, main content, and right panel) are aligned horizontally with a height of 90vh.
   - **Screen Width <= 700px**: Sections are stacked vertically to fit smaller screens.

3. **Collapsible Left Menu**:
   - A toggle button allows collapsing or expanding the left menu.

4. **Dynamic Scaling**:
   - The page dynamically scales based on screen width for optimal viewing:
     - **992px - 1600px**: Scales to 90%.
     - **700px - 767px**: Scales to 80%.
     - **600px - 700px**: Scales to 75%.
     - **<= 600px**: Scales to 50%.

5. **Visual Enhancements**:
   - Each section has distinct colors and borders for clarity and aesthetics.

## How to Run

1. **Prerequisites**:
   - A modern web browser (e.g., Chrome, Firefox, Edge).

2. **Steps**:
   - Download the HTML file.
   - Open the file in any web browser.
   - Resize the browser window to observe layout and scaling changes.

3. **Test the Features**:
   - Click the "☰ Toggle Menu" button to collapse/expand the left menu.
   - Observe how sections realign and scale dynamically when resizing the browser window.

## Code Overview

### HTML
- **Structure**:
  - `navbar`, `container`, and `footer` define the layout.
  - Left menu, main content, and right panel are organized inside the `container`.

### CSS
- **Styling**:
  - Media queries adjust layouts for different screen widths.
  - Flexbox ensures proper alignment and spacing.

### JavaScript
- **Interactive Elements**:
  - `toggleMenu()`: Toggles the width of the left menu.
  - `adjustPageWidth()`: Dynamically scales the page based on screen width.

## Customization
- Modify colors, fonts, or dimensions in the `<style>` section of the HTML file to suit your design needs.

## License
This project is open-source and free to use.

