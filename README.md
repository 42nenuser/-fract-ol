# Fractol - Computer Graphics Fractals

## 📌 Project Overview
Fractol is a fractal visualization program written in C using the **MiniLibX** graphical library. This project allows users to generate and interact with different fractals, primarily the **Mandelbrot** and **Julia** sets. The program provides zooming capabilities, customizable fractal parameters, and smooth rendering using color gradients.

## 🎯 Features
- ✅ **Mandelbrot and Julia set visualization**
- ✅ **Interactive zooming and panning**
- ✅ **Dynamic fractal parameter adjustments**
- ✅ **Color depth effects for better visualization**
- ✅ **Clean event handling (ESC to quit, smooth window management)**
- ✅ **Bonus: Additional fractal types, mouse-based zooming, keyboard navigation, and color shifts**

## 🖥️ Installation & Usage

### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/yourusername/fractol.git
cd fractol
2️⃣ Compile the Program

Make sure you have MiniLibX installed before compiling. Then, run:

make

3️⃣ Run the Program

./fractol [fractal_type]

Available fractal types:

    mandelbrot
    julia
    other_fractal (if implemented as a bonus)

Example:

./fractol mandelbrot

🎮 Controls
Key/Mouse Action	Function
Scroll Up / Scroll Down	Zoom In / Zoom Out
Arrow Keys	Move the view
ESC	Exit the program
📚 Dependencies

    C programming language
    MiniLibX (mlx library)
    Math library (-lm)
    Libft (if used)

🛠️ Development Notes

    The project follows strict memory management rules to prevent leaks.
    Compiled with flags: -Wall -Wextra -Werror
    No global variables are used, and all functions comply with coding standards.

📜 License

This project is developed as part of 42 School's curriculum.
