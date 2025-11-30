# Calculator.py

A clean, intuitive calculator built with Python and Tkinter. It supports basic arithmetic and essential functions like square and square root — perfect for everyday use or as a lightweight replacement for your system's default calculator.

---

## Features

- ➕ Addition, ➖ Subtraction, ✖️ Multiplication, ➗ Division
- 🟰 Square and square root functions
- 🎨 Simple, user-friendly GUI
- ⌨️ Keyboard and mouse input support
- 🖼️ Customizable layout and styling

---

## 📦 Installation

### Requirements
- Python 3.7 or higher
- Tkinter (usually included with Python)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/Paddywelch117/-Calculator-App

2. Navigate to the project folder:
    ```bash
    cd Calculator.py

3. Run the calculator:
    ```bash
    python Calculator.py

---

## Preview
![Calculator Screenshot](Screenshot.png)

---

## 🖥️ Set as Default Calculator App

You can replace your system's default calculator with `Calculator.py` using the steps below.

### 🔹 Windows

1. **Create a shortcut**:
   - Right-click `Calculator.py` → Send to → Desktop (create shortcut)
   - Rename the shortcut to **Calculator**

2. **Change default app**:
   - Go to **Settings** → **Apps** → **Default apps**
   - Scroll to **Calculator** and click it
   - Choose **Look for an app on this PC**
   - Browse to your Python executable (e.g., `C:\Python39\python.exe`)
   - Select it and confirm

3. **Associate `.py` files with Python** (if needed):
   - Right-click any `.py` file → Open with → Choose another app → Select Python
   - Check **Always use this app**

---

### 🔹 macOS

1. **Create an Automator app**:
   - Open **Automator** → New Document → Choose **Application**
   - Add a **Run Shell Script** action with:
     ```bash
     python3 /path/to/Calculator.py
     ```
   - Save as **Calculator.app**

2. **Replace default shortcut**:
   - Rename the Automator app to **Calculator**
   - Move it to `/Applications`
   - Remove the default Calculator from the Dock and add your version

---

### 🔹 Linux (Ubuntu/Debian)

1. **Create a desktop entry**:
   - Create a file named `calculator.desktop` in `~/.local/share/applications/`:
     ```ini
     [Desktop Entry]
     Name=Calculator
     Exec=python3 /path/to/Calculator.py
     Icon=accessories-calculator
     Type=Application
     Categories=Utility;
     ```

2. **Set as default**:
   - Use `xdg-mime` to associate calculator MIME types:
     ```bash
     xdg-mime default calculator.desktop application/x-calculator
     ```
---

## 🧠 Author

Created by **Patrick Welch** — pragmatic, detail-oriented, and passionate about clarity, optimization, and sharing knowledge through clean technical design.

---

## 📬 Feedback & Contributions

Feel free to fork, improve, or suggest features via pull requests or issues. Let’s make this calculator even better together!

---

## 📈 Version

**Current Version:** 1.0.0  
**Status:** Stable release

---

## 💡 Future Enhancements

- Add calculation history
- Support scientific functions (trigonometry, logarithms)
- Theme customization
- Export results to text or CSV

---

