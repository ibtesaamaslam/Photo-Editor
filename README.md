
# 🖼️ Photo Editor with OpenCV | Python GUI App

A simple but powerful **photo editing app** built using **OpenCV** and **Tkinter**. This project allows users to apply common image transformations and filters through a user-friendly graphical interface.

> 🎨 Perfect for beginners exploring image processing and GUI development in Python!

---

## 🧰 Tech Stack

| Tool            | Purpose                         |
|-----------------|---------------------------------|
| Python          | Core programming language       |
| OpenCV          | Image processing functionality  |
| Tkinter         | GUI (Graphical User Interface)  |
| NumPy           | Numerical operations (used with OpenCV) |

---

## 🎯 Features

✅ Load and view images  
✅ Resize and rotate images  
✅ Convert to grayscale or apply blur  
✅ Save edited images  
✅ Easy-to-use GUI built with Tkinter

---

## 📸 Preview

> *(Insert screenshots or GIF of the app here if available)*

---

## 📂 Project Structure

```
.
├── photo_editor.py / .ipynb       # Main application (notebook or script)
├── README.md                      # Project documentation
└── sample_images/                 # Optional: folder with sample input/output
```

---

## 🧪 Supported Image Operations

| Feature        | Description                                  |
|----------------|----------------------------------------------|
| **Open Image** | Browse and open any `.jpg`, `.png`, etc.     |
| **Rotate**     | Rotate the image left or right               |
| **Resize**     | Adjust image dimensions                      |
| **Grayscale**  | Convert the image to black & white           |
| **Blur**       | Apply Gaussian blur to soften the image      |
| **Save Image** | Save the processed image to your device      |

---

## ⚙️ Installation

### 🐍 Requirements

Install the dependencies using pip:

```bash
pip install opencv-python tkinter numpy
```

> *Note: For some systems, Tkinter is built-in. If you get an error, try installing via your OS package manager.*

---

## 🚀 How to Run

### ▶️ Run via Python Script

```bash
python photo_editor.py
```

### ▶️ Run via Notebook

Open `Photo Editor.ipynb` in Jupyter or Google Colab and run all cells.

---

## 💡 How It Works

1. A Tkinter window opens and provides buttons for each function.
2. When you open an image, OpenCV reads and processes it.
3. Users apply filters via GUI controls.
4. The final image can be saved using `cv2.imwrite()`.

---

## 📌 Notes

- GUI windows **won’t work on Google Colab**, but the notebook version is still useful for testing image functions.
- Save paths are set locally — adjust them if using different platforms.
- This project is designed for **educational purposes** but can be extended to professional-grade tools.

---

## 🌟 Future Enhancements

- Add image filters: Sepia, Pencil Sketch, etc.
- Drag-and-drop image loading
- Dark/light mode UI toggle
- Batch processing for multiple images

---

## 🤝 Contributing

If you want to improve the app or add new filters, feel free to fork and open a pull request!
