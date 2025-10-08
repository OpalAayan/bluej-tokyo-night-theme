# 🎨 BlueJ Tokyo Night Theme

A complete, modern dark theme for the BlueJ Java IDE.

Tired of BlueJ’s outdated default look? This theme gives BlueJ a fresh, professional dark style inspired by popular palettes like **Tokyo Night** , **Catppuccin** and **Ocean Space**. It’s designed for readability, usability, and aesthetics — making coding more enjoyable and less straining on your eyes.

---

## ✨ Gallery

Here’s the theme in action:

> All img are In 720p (1366*768) as that what my Old laptop has 

### Editor Window
<img width="1366" height="768" alt="Screenshot From 2025-08-30 16-49-02" src="https://github.com/user-attachments/assets/f95cb037-677a-4858-be12-d9fbfcca0e3a" />

In this screenshot, I’ve changed the Codepad background from `#140e1a` to `#24152d` to improve cursor visibility.  
An extension is planned to properly handle this across setups.  
~I’ll also upload the `java-colors.css` file soon—let me know if you’d like a copy~ Maybe I did.

### Project View
<img width="1366" height="768" src="https://github.com/user-attachments/assets/9e37045a-47bb-42d4-8f5e-dc0ade1a54a6" alt="Project Screenshot" />

### Preferences
<img width="262" height="416" alt="Screenshot From 2025-08-26 17-47-26" src="https://github.com/user-attachments/assets/0a8e647f-774f-402d-8595-675702ffc5cd" />
<img width="259" height="370" alt="Screenshot From 2025-08-26 17-47-10" src="https://github.com/user-attachments/assets/5fae203e-07e3-42b6-ae42-52e550080e5d" />
<img width="245" height="164" src="https://github.com/user-attachments/assets/55cce761-476e-4cb3-8004-6391a44d3cb5" alt="Preferences Screenshot" />

### Terminal
<img width="1366" height="768" alt="Screenshot From 2025-10-08 10-33-58" src="https://github.com/user-attachments/assets/335459db-9b15-420c-9d11-3ff494632751" />
<img width="1366" height="768" alt="Screenshot From 2025-10-08 10-40-57" src="https://github.com/user-attachments/assets/4f8b0242-cc4d-40e6-8ae0-051a7e3cd387" />




> I'm still figuring out how to customize the #fffffff part of  terminal colors exactly how I want — help would be appreciated!
> Maybe I can't 

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
   >NEWstylesheet.zip for latest 
   >Old one for default OG 

3. **Locate BlueJ’s stylesheet folder**
   - **Windows:** `C:\Program Files\BlueJ\lib\stylesheets`
   - **macOS:** Right-click BlueJ → **Show Package Contents** → `Contents/Resources/Java/stylesheets`
   - **Linux:** Usually `/usr/share/bluej/lib/stylesheets`

4. **Replace the files**
   - Extract the ZIP.  
   - Copy all `.css` files into the `stylesheets` folder.  
   - *(Optional but recommended: back up the originals first!)*

5. **Restart BlueJ**  
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

> Some UI elements may be hardcoded in BlueJ and not fully themeable via CSS alone. The planned extension aims to cover these gaps and deliver a 99% complete theme.
> Next I will update those mathod calling windows 

---

## 🤝 Contributing

Contributions and tips are welcome!  
- Open an **Issue** for bugs or ideas.  
- Submit a **Pull Request** for improvements (CSS tweaks, terminal colors, docs, etc.).

If you know good hooks for terminal colors or How may I change that Cursor Color inside the editor in BlueJ, I’d love your help!

---

## ❤️ Acknowledgements

- Thanks to Vickwes as His configs helped me when needed do check his repo out - https://github.com/Vickwes/BlueJ-Dark-Mode
- Thanks to this Ninja 🥷 https://github.com/WickedKakashi 
was a silent helper but also the core reason for this matching palettes.. 

- Inspired by the **Tokyo Night** , **Catppuccin** and **Ocean Space** palettes.

---

## 📜 License

This project is open source under the **MIT License**.
