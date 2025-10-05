# Interactive Drawing Canvas using Python & OpenCV

An **interactive drawing application** built with Python and OpenCV that allows users to draw shapes, use an eraser, customize colors and brush thickness, and save their creations.

## Features

* **Draw shapes**: Pen, Line, Rectangle, Circle
* **Eraser**: Toggle to remove parts of your drawing
* **Customizable colors**: Use trackbars to adjust RGB values
* **Adjust brush thickness**: Change line thickness dynamically
* **Save sketches**: Automatically save drawings to a folder
* **Clear canvas**: Reset the canvas with a single key
* **Keyboard shortcuts**:

  * `p` : Pen mode
  * `e` : Eraser mode
  * `s` : Save current canvas
  * `d` : Delete/clear canvas
  * `q` : Quit application

## Screenshots

*(Add screenshots of your canvas in action here to make it visually appealing)*

## Installation

1. Clone the repository:

   ```bash
   git clone <your-repo-link>
   ```
2. Install dependencies:

   ```bash
   pip install opencv-python numpy
   ```

## Usage

1. Run the Python script:

   ```bash
   python canvas.py
   ```
2. Use the **toolbar** on the right to select shapes.
3. Use **trackbars** to change color and brush thickness.
4. Use **keyboard shortcuts** for quick actions.

## Folder Structure

* `canvas.py` : Main application script
* `D:\paint_sc\` : Folder where images are saved

## Future Improvements

* Add more shapes and brush styles
* Implement undo/redo functionality
* Add color picker instead of trackbars
* Cross-platform save directory

