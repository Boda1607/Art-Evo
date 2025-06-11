# Art Evo


A comprehensive and responsive web-based drawing application, built with HTML, CSS, and JavaScript. This app provides a wide array of drawing tools, shapes, and features, designed to work seamlessly across desktop and mobile devices.

## Features

🎨 **Diverse Drawing Tools:**

* **Pen:** Freehand drawing with adjustable size and color, creating smooth, continuous strokes.

* **Eraser:** Precisely remove parts of your drawing, with its size configurable just like the pen, effectively painting with the canvas's background color.

* **Shapes:** Draw various geometric and custom shapes with precision and control:
  * **Basic Geometries:** Line, Rectangle, Square, Circle, Ellipse, Triangle, Pentagon, Hexagon, Heptagon, Octagon, Nonagon, Decagon.
  * **Complex Forms:** Star, Heart, Arrow, Cloud, Lightning, Cross, Diamond, Speech Bubble, Trapezoid.

* **Fill Tool:** Apply a solid color flood fill to any enclosed area on the canvas with a single click, automatically detecting boundaries.

* **Text Tool:** Add custom text elements to your canvas, allowing you to position and size the text dynamically.

* **Image Insertion:** Seamlessly import and place external images directly onto your canvas as drawable objects, which can then be moved or resized.

🌈 **Customization & Effects:**

* **Color Picker:** Intuitive color selection for both strokes and fills, offering a full spectrum of choices.

* **Brush Size Slider:** Granular control over the thickness of your pen strokes and the area of your eraser, ranging from fine details to broad strokes.

* **Opacity Control:** Adjust the transparency level for all drawing actions, enabling layered effects and subtle blending.

* **Line Styles:** Choose from a variety of line styles including Solid, Dashed (for segmented lines), and Dotted (for discrete points).

* **Fill Types:** Enhance your shapes with different fill options: Solid Color for uniform fills, and Linear Gradient for smooth color transitions within shapes.

* **Symmetry Tools:** Unlock creative possibilities with real-time drawing mirroring:
  * **Horizontal Symmetry (H-Sym):** Draw simultaneously mirrored across the horizontal center of the canvas.
  * **Vertical Symmetry (V-Sym):** Draw simultaneously mirrored across the vertical center of the canvas.

* **Dynamic Backgrounds:** Personalize your canvas with a wide range of backgrounds:
  * **Solid Color:** A clean, single-color background that adapts to the chosen theme.
  * **Patterned:** Grid, Dots, Horizontal Stripes, Vertical Stripes, and Checkerboard for structured drawing.
  * **Custom Image Background:** Upload and display your own image as the canvas background, which scales automatically to fit.

🔄 **History & Persistence:**

* **Undo/Redo:** Comprehensive history management allows you to step backward and forward through your drawing actions with standard keyboard shortcuts (Ctrl+Z / Ctrl+Y).

* **Auto-Save to Local Storage:** Your work is automatically saved to your browser's local storage after every significant drawing action, ensuring your progress is never lost even if you close the tab or browser. The last saved canvas dimensions are also remembered.

* **Save Image:** Easily export your finished masterpiece as a high-quality PNG image file.

📱 **Mobile-First Responsive Design:**

* The entire user interface is built with a mobile-first approach, ensuring optimal usability and aesthetic appeal across all device sizes.

* The toolbar dynamically adjusts its layout, intelligently grouping and wrapping elements to fit screen real estate, providing a clean and efficient workspace on smartphones, tablets, and desktops alike, with approximately 3-4 items per line on smaller screens.

* All interactive elements (buttons, sliders, dropdowns) are carefully sized to be comfortable and accurate for touch input.

💡 **Creative Modes:**

* **Guided Drawing Mode:** Import an image as a translucent overlay on your canvas, allowing you to trace over it. The opacity of the guide image can be adjusted for optimal visibility.

* **Drawing Challenges:** Engage in fun, timed drawing exercises with random prompts to spark creativity and improve your sketching speed.

📏 **Custom Canvas Size:**

* Define and apply custom width and height dimensions for your canvas. Existing drawings are intelligently scaled to fit the new dimensions, preserving your work.

🌓 **Dark Mode Toggle:**

* Instantly switch between a light and a dark theme for the entire application, providing a comfortable viewing experience in different lighting conditions and personal preferences.

## Demo

Experience the app live: <https://artevo.netlify.app/>

## How to Use

1. **Open `index.html`:** Simply download the project files and open the `index.html` file in any modern web browser. No server setup is required.

2. **Select a Tool:** Click on the desired tool button from the toolbar (e.g., "Pen", "Eraser", "Fill", "Text"). For shapes, use the "Shapes" dropdown to select your desired form.

3. **Adjust Properties:** Modify the drawing properties using the sliders and dropdowns:

   * Use the **Color Picker** to choose your drawing color.

   * Adjust **Size** for pen/eraser thickness.

   * Control **Opacity** for transparency.

   * Select **Line Style** (Solid, Dashed, Dotted) and **Fill Type** (Solid Color, Linear Gradient).

   * Enable **H-Sym** or **V-Sym** for symmetrical drawing.

4. **Draw on Canvas:**

   * **Pen/Eraser:** Click and drag your mouse (or finger on touch devices) across the canvas.

   * **Shapes:** Click and hold to define the starting point, drag to create the shape, and release to finalize.

   * **Fill Tool:** Click inside a closed shape or area to fill it with the selected color.

   * **Text Tool:** Click on the canvas where you want to add text. A text input overlay will appear; type your text and press `Enter` or click outside the input to place it.

   * **Insert Image:** Click the "Insert Image" button, select an image file from your computer, then click on the canvas to place it.

5. **Manage Your Work:**

   * Click **"Undo (Ctrl+Z)"** to revert the last action.

   * Click **"Redo (Ctrl+Y)"** to reapply a previously undone action.

   * Click **"Clear (Delete)"** to clear the entire canvas.

6. **Save Your Drawing:** Click **"Save Image"** to download your current canvas as a PNG file.

7. **Customize View:**

   * Use the **"Dark Mode"** toggle to switch the application's theme.

   * Select a **Background** type from the dropdown (Solid, Grid, Dots, Stripes, Checkerboard). You can also click "Set Image" to upload a custom background.

   * Adjust **Canvas Width** and **Canvas Height** using the number inputs and click "Apply Size" to resize your drawing area.

8. **Explore Creative Modes:**

   * **Guided Drawing:** Click "Guided Drawing", upload an image, and use the "Guide Opacity" slider to adjust its transparency for tracing. Click "Clear Guide" to remove it.

   * **Drawing Challenge:** Click "Drawing Challenge" to start a timed drawing session with a random prompt.

## Technical Stack

* **HTML5:** Provides the foundational structure and semantic markup for the web application.

* **CSS3:** Powers the styling, layout, animations, and ensures full responsiveness across various devices and screen sizes. Utilizes CSS variables for easy theme management (light/dark mode).

* **JavaScript (ES6+):** The core programming language implementing all interactive logic, including:
  * Canvas API manipulation for drawing, image processing, and pixel-level operations (e.g., flood fill algorithm).
  * Event handling for mouse and touch interactions.
  * State management for drawing history (undo/redo).
  * Local storage integration for data persistence.
  * Dynamic UI updates and element control.

* **Canvas API:** The fundamental technology enabling pixel-perfect drawing, shape rendering, image manipulation, and custom background patterns directly within the browser.

## Installation

This application is entirely client-side. No special installation or server is required.

1. **Clone the repository:**

   ```bash
   git clone [https://github.com/Boda1607/advanced-drawing-app.git](https://github.com/Boda1607/advanced-drawing-app.git)
   ```

2. **Navigate to the project directory:**

   ```bash
   cd advanced-drawing-app
   ```

3. **Open `index.html`:** Double-click `index.html` in your file explorer, or open it via your browser's file menu.

## Contributing

Contributions are welcome! If you have suggestions for improvements or find any issues, please feel free to:

1. Fork the repository.

2. Create a new branch (`git checkout -b feature/your-feature-name`).

3. Make your changes.

4. Commit your changes (`git commit -m 'Add new feature X'`).

5. Push to the branch (`git push origin feature/your-feature-name`).

6. Open a Pull Request.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Credits

Made with ❤️ by [AbdElRahman](https://abdelrahmanz.netlify.app/)
