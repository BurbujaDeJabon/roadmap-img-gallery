# Image Grid - Roadmap.sh Project

Welcome to the **Image Grid** project! 
This project is part of the **Roadmap.sh** series and demonstrates an **implicit responsive grid** layout. 
The gallery dynamically arranges images into a responsive, multi-row grid that adapts to different screen sizes, providing a smooth, flexible design for displaying image galleries.

## Features
- **Implicit Grid Layout**: Uses CSS Grid to automatically create grid items without needing to manually define rows and columns.
- **Responsive Design**: The grid adjusts to different screen sizes, creating a fluid layout with images that scale dynamically.
- **Long Cards**: Some images are designed to span multiple rows for a varied layout using the `.long-card` class.
- **Grid Auto-rows**: Defines a flexible grid with automatic row height adjustment.

## How It Works

The gallery uses **CSS Grid** with an implicit grid layout, which allows content to flow naturally into available space.
The use of `grid-template-columns: repeat(auto-fit, minmax(300px, 1fr))` ensures that the grid adapts to the available screen size, while the `grid-auto-rows` rule helps maintain uniform row heights.




