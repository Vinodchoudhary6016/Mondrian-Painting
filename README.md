# Mondrian-Painting

This project is a simple web page inspired by the art style of Piet Mondrian. It utilizes CSS Grid to create a layout with various colored sections. The design is intended to mimic the geometric abstraction characteristic of Mondrian's work.

## Overview

The HTML file contains a single page with a grid layout composed of colored blocks. The layout uses CSS Grid to define the structure and placement of these blocks.

## Features

- Responsive design using CSS Grid
- Colorful sections representing Mondrian's style
- Customizable grid layout

## Installation

1. Clone the repository or download the HTML file.
2. Open the HTML file in a web browser to view the layout.

## Code Explanation

### HTML Structure

The main container is defined with the class `container`, which holds individual items represented by `div` elements. Each item can have different background colors and grid properties.

### CSS Styles

The following CSS styles are applied:

- **Body Style**: Centers the grid on the page.
- **Container**: Defines the grid layout with specific column and row sizes.
- **Items**: Each item can have different background colors and grid properties.

### Grid Layout

The grid layout is defined as follows:

```css
.container {
  height: 748px; /* Overall height of the grid */
  width: 748px; /* Overall width of the grid */
  display: grid;
  background-color: #000; /* Background color of the grid */
  grid-template-columns: 320px 198px 153px 50px; /* Column sizes */
  grid-template-rows: 414px 130px 155px 22px; /* Row sizes */
  gap: 9px; /* Gap between grid items */
}
