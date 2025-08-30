# 🎨 BlueJ Tokyo Night Theme

A complete, modern dark theme for the BlueJ Java IDE.

Tired of BlueJ’s outdated default look? This theme gives BlueJ a fresh, professional dark style inspired by popular palettes like **Tokyo Night** and **Catppuccin**. It’s designed for readability, usability, and aesthetics — making coding more enjoyable and less straining on your eyes.

---

## ✨ Gallery

Here’s the theme in action:

### Editor Window
<img width="1366" height="768" alt="Screenshot From 2025-08-30 16-49-02" src="https://github.com/user-attachments/assets/f95cb037-677a-4858-be12-d9fbfcca0e3a" />

In this screenshot, I’ve changed the Codepad background from `#140e1a` to `#24152d` to improve cursor visibility.  
An extension is planned to properly handle this across setups.  
I’ll also upload the `java-colors.css` file soon—let me know if you’d like a copy.

### Project View
<img width="1366" height="768" src="https://github.com/user-attachments/assets/9e37045a-47bb-42d4-8f5e-dc0ade1a54a6" alt="Project Screenshot" />

### Preferences
<img width="262" height="416" alt="Screenshot From 2025-08-26 17-47-26" src="https://github.com/user-attachments/assets/0a8e647f-774f-402d-8595-675702ffc5cd" />
<img width="259" height="370" alt="Screenshot From 2025-08-26 17-47-10" src="https://github.com/user-attachments/assets/5fae203e-07e3-42b6-ae42-52e550080e5d" />
<img width="245" height="164" src="https://github.com/user-attachments/assets/55cce761-476e-4cb3-8004-6391a44d3cb5" alt="Preferences Screenshot" />

### Terminal
<img width="1366" height="768" src="https://github.com/user-attachments/assets/4ba944c8-263c-4634-85a5-fff50c766118" alt="Terminal Screenshot" />

> I'm still figuring out how to customize the terminal colors exactly how I want — help would be appreciated!

---

## 🚀 Features

- 🎨 **Comprehensive theming** — Menus, dialogs, buttons, editor, and terminal.
- 🌙 **Modern dark aesthetics** — Smooth Tokyo Night–inspired palette.
- 🔍 **Enhanced readability** — Syntax highlighting tuned for clarity.
- ⚡ **Easy installation** — Just replace a few CSS files.

---

## 🛠️ Installation

1. **Download the theme**  
   Click the green **Code** button on this page → **Download ZIP**.

2. **Locate BlueJ’s stylesheet folder**
   - **Windows:** `C:\Program Files\BlueJ\lib\stylesheets`
   - **macOS:** Right-click BlueJ → **Show Package Contents** → `Contents/Resources/Java/stylesheets`
   - **Linux:** Usually `/usr/share/bluej/lib/stylesheets`

3. **Replace the files**
   - Extract the ZIP.  
   - Copy all `.css` files into the `stylesheets` folder.  
   - *(Optional but recommended: back up the originals first!)*

4. **Restart BlueJ**  
   The dark theme will now be applied.

---

## ♻️ Uninstall / Revert

- Replace the modified `.css` files with your backups, **or**
- Reinstall BlueJ to restore the default styles.

---

## 🎛️ Customization

- The file `java-colors.css` (to be uploaded) will expose editor/Codepad colors you can tweak (e.g., background and cursor visibility).
- If the cursor is hard to see, try a slightly lighter editor background (e.g., `#24152d`) or adjust the caret color (when available).

---

## 🔮 Roadmap

- BlueJ extension to override areas that CSS can’t reliably reach (e.g., some cursor and editor behaviors).
- Improved terminal theming.
- More palette variants (e.g., Storm, Night, Moon).

> Some UI elements may be hardcoded in BlueJ and not fully themeable via CSS alone. The planned extension aims to cover these gaps and deliver a 100% complete theme.

---

## 🤝 Contributing

Contributions and tips are welcome!  
- Open an **Issue** for bugs or ideas.  
- Submit a **Pull Request** for improvements (CSS tweaks, terminal colors, docs, etc.).

If you know good hooks for terminal colors or caret rendering in BlueJ, I’d love your help!

---

## ❤️ Acknowledgements

- Thanks to **Gemini** for help with CSS troubleshooting and development.  
- Inspired by the **Tokyo Night** and **Catppuccin** palettes.

---

## 📜 License

This project is open source under the **MIT License**.