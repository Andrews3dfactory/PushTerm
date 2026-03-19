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

## 📢 Update (03/19/2026)

PushTerm is being **fully rebuilt from scratch**.

### ⚡ New Direction
- Web-connected printer control (no SD card)
- Cleaner, easier UI
- More reliable automation
- Fully rewritten backend

*(Yes… partly because my SD card slot is broken 😅)*

### 💸 Cost
**100% FREE — forever**
- No paid features
- No locked tools

### ⏳ Status
In development — updates coming soon.

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

PushTerm is available on PyPI. You can install it using pip:

```bash
pip install pushterm
```
Or just use the Zip File you can pick i prefer the zip file cause its up to date
---

## 🧪 How to Use 
   **1. Download or clone** this project folder.
   Put your G-code file (e.g., `Ploter.gcode`) inside the `MyPrints` folder.
   Double-click or run this from the terminal:

python launcher.py
4. When the terminal opens, follow the steps:
   - Type: `cd MyPrints`
   - Then: `begin`
   - Enter your file name: `Ploter.gcode`
   - Set the delay like `m5` for 5 minutes or `s30` for 30 seconds
   - Confirm how many copies to eject

5. The modified file will be saved in the same folder as:
      the orginal file 
      the name of fie: yourPrintFileName_modified.gcode
   
---

## ⚙️ What It Does

- Edits G-code automatically  
- Adds delay after prints  
- Pushes finished prints off the bed  
- Keeps safe nozzle height

## ✅ Requirements
   - Python 3.x installed
   - No extra dependencies
   - just basic Python and a terminal

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
