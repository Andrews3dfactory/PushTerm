<p align="center">
  <img src="https://raw.githubusercontent.com/Andrews3dfactory/PushTerm/main/assets/logo.png" width="300"/>
</p>

<h1 align="center">PushTerm</h1>

<p align="center">
  Terminal-powered 3D printing automation
</p>

<p align="center">
  <img src="https://img.shields.io/github/v/release/Andrews3dfactory/PushTerm?color=00ff99&label=Version&style=for-the-badge"/>
  <img src="https://img.shields.io/github/last-commit/Andrews3dfactory/PushTerm?color=00ff99&style=for-the-badge"/>
  <img src="https://img.shields.io/github/license/Andrews3dfactory/PushTerm?color=00ff99&style=for-the-badge"/>
</p>

---

## 📢 Update (04/06/2026)

PushTerm V2 is progressing—**the UI design is now complete**, and the **File Tab is functional**!

### ⚡ New Direction
- Web-connected printer control (no SD card)  
- Cleaner, easier-to-use UI  
- More reliable automation  
- Fully rewritten backend  
*(Yes… partly because my SD card slot is broken 😅)*

### ⚡ What’s New
- Full **UI design finalized**: dark, futuristic, space-style theme  
- **File Tab working**: generate and modify G-code directly in the app, like the terminal  
- Main layout finalized for terminal, queue, and placeholders for drag-and-drop and animations  
- **Note:** UI is functional for File Tab only; other interactive features still in development  
- Can do everything the Terminal Version can now  

### 💸 Cost
**100% FREE — forever**  
- No paid features  
- No locked tools  

### ⏳ Status
File Tab working — full printer integration coming next  

### ❤️ Support
Donations will be added soon if you want to support the project 🙌

---

## 🚀 Features

- ⚡ Fast & lightweight
- 🖥️ Terminal-based control
- 🧩 Custom workflows
- 🖨️ Built for print automation
- 🔧 Easy to modify (Python)

---

## 📦 Installation

PushTerm is available on PyPI:

```bash
pip install pushterm
```

Or download the **Zip file** (recommended for latest version).

---

## 🧪 How to Use

1. **Download or clone** this project folder.  
   Place your G-code file (e.g., `Ploter.gcode`) inside the `MyPrints` folder.

2. Run the launcher from the terminal:

```bash
python launcher.py
```

3. In the terminal:
   - Type: `cd MyPrints`
   - Then: `begin`
   - Enter your file name (e.g., `Ploter.gcode`)
   - Set the delay:
     - `m5` → 5 minutes
     - `s30` → 30 seconds
   - Confirm how many copies to eject

4. The modified file will be saved in the same folder as the original file with the name:

```
yourPrintFileName_modified.gcode
```

---

## ⚙️ What It Does

- Edits G-code automatically  
- Adds delay after prints  
- Pushes finished prints off the bed  
- Keeps safe nozzle height

---

## ✅ Requirements

- Python 3.x installed  
- No extra dependencies — just basic Python and a terminal

---

## 📂 Structure

```
PushTerm/
├── launcher.py
├── terminal_ui.py
├── MyPrints/
└── README.md
```

---

## 🚨 Notes

- Test G-code before real use  
- Works best on flat beds  
- Optimized for Bambu Lab (adaptable)

---

## 🎥 Demo

https://www.youtube.com/watch?v=v64aOb2rB20&feature=youtu.be

---

## 🧠 Why This Exists

Because your printer should finish a job and immediately start the next one like a machine 😤

---

## 📄 License

MIT License

---

## 💚 Created By

Andrew’s 3D Factory
