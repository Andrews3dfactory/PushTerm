# PushTerm

PushTerm is a Python-based command-line tool designed to streamline your 3D printing experience using your terminal. It provides a clean, simple terminal interface and lets you launch customizable commands, scripts, or tools with ease. This command is a tool for auto print farms; most auto print farms take too long, and sometimes don't work. The PushTerm allows you to customize speed and is more efficient for producing quality prints.

⚠️ Legal Notice
PushTerm v1 (this version) is released free and open-source under the MIT License and is not covered by any patents. You are free to use, modify, and distribute this version.
Future versions of PushTerm may include proprietary logic and features that are patent-pending and protected. Only this original version (v1) is free for commercial and non-commercial use.

## 🚀 Features

- Lightweight and fast
- Customizable launcher interface
- Built with Python – easy to extend
- Perfect for personal or school projects

## 📦 Installation

PushTerm is available on PyPI. You can install it using pip:

```bash
pip install pushterm

## 🙌 Shoutout

Special thanks to **[Small Pot](https://makerworld.com/en/models/1021588-small-pot?from=search#profileId-1003062)** (user_1400159957) for the awesome print design used during testing! 🎉

---

## 📂 Folder Structure

```
PushTerm/
├── launcher.py          # Opens the terminal UI in a separate window
├── terminal_ui.py       # Main terminal interface logic
├── list_files.py        # This is a debug log  to see if it can find the files 
├── MyPrints/            # Where you put your original G-code files
│   └── Ploter.gcode     # (example file)
│   └── Ploter_Modify.gcode # (example file)
└── README.md            # This file
```

---

## 🧪 How to Use

1. **Download or clone** this project folder.
2. Put your G-code file (e.g., `Ploter.gcode`) inside the `MyPrints` folder.
3. Double-click or run this from the terminal:

   ```
   python launcher.py
   ```

4. When the terminal opens, follow the steps:
   - Type: `cd MyPrints`
   - Then: `begin`
   - Enter your file name: `Ploter.gcode`
   - Set the delay like `m5` for 5 minutes or `s30` for 30 seconds
   - Confirm how many copies to eject

5. The modified file will be saved in the same folder as:
      the orginal file 
      the name of fie: yourPrintFileName_modified.gcode

```

## ⚙️ What It Does

- Finds the end of your G-code file
- Adds a delay after the print finishes (based on your input)
- Inserts a G-code movement command to push the print off the bed using the toolhead
- Ensures safe travel height to avoid nozzle damage

---

## ✅ Requirements

- Python 3.x installed
- No extra dependencies — just basic Python and a terminal

---

## 🚨 Notes

- Always test modified G-code carefully.
- Use a safe push-off height to avoid nozzle damage.
- Works best on flat, hard-surface plates (like cool PEI or textured beds).
- Designed for Bambu Lab X1 Carbon but can be adapted.

---

## 🧠 Why This Exists

Because it’s fun to make your printer kick your prints off the bed like a boss.

---

## 📷 Screenshots or Demo

Link To Demo Video 
**[Demo Video link](https://www.youtube.com/watch?v=v64aOb2rB20&feature=youtu.be)** 

---

Created with 💚 by Andrew’s 3D Factory
📄 Licensed under the MIT License – see the LICENSE.md file for details.
