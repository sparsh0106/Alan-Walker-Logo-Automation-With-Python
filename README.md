# 🎨 Alan Walker Logo Drawing Automation (`PyAutoGUI`)

A Python desktop automation script (`Alan_Walker_Logo_Automation.py`) powered by **PyAutoGUI** that automatically opens **Microsoft Paint** via the Windows Start menu and sketches the geometric **Alan Walker ("AW")** logo using programmed cursor drag trajectories.

---

## 📂 Repository Structure

- `Alan_Walker_Logo_Automation.py`: Automated mouse/keyboard control script using `pyautogui`.
- `README.md`: Project documentation.

---

## ⚙️ How It Works

1. Triggers the Windows Start menu (`Ctrl + Esc`), types `paint`, and presses `Enter`.
2. Waits 5 seconds for the MS Paint canvas to initialize and focus.
3. Executes a sequence of relative cursor movements (`pyautogui.moveRel`) and brush strokes (`pyautogui.dragRel`) to draw the interlocked **A** and **W** emblem.

---

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/sparsh0106/Alan-Walker-Logo-Automation-With-Python.git
   cd Alan-Walker-Logo-Automation-With-Python
   ```

2. **Install PyAutoGUI**:
   ```bash
   pip install pyautogui
   ```

3. **Run the automation** *(on Windows with MS Paint installed)*:
   ```bash
   python Alan_Walker_Logo_Automation.py
   ```
   *(Tip: Move your mouse cursor to any corner of the screen to trigger PyAutoGUI's fail-safe abort if needed.)*

---

## 👤 Author

**Sparsh Agarwal** — [GitHub](https://github.com/sparsh0106)
