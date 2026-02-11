# VS-Code-Interface-Replica

A pixel-perfect HTML/CSS replica of Microsoft Visual Studio Code's interface. This project recreates the iconic dark theme layout, complete with activity bar, sidebar explorer, tabbed editor with syntax highlighting, integrated terminal, and status bar.


<img width="1828" height="921" alt="image" src="https://github.com/user-attachments/assets/ac6b3376-d936-4230-ac8a-4b506a84c196" />

## 🚀 Features

- **Authentic Dark Theme** - True to VS Code's #1e1e1e background
- **Fully Responsive Grid Layout** - Activity bar, sidebar, editor, and terminal panel
- **Interactive Elements** - Hover states, active tabs, clickable icons
- **Syntax Highlighting** - JavaScript/HTML/CSS color tokens
- **File Explorer** - Collapsible tree view with folder/file icons
- **Tabbed Editor** - Multiple open files with active tab indicator
- **Integrated Terminal** - PowerShell-style command line
- **Status Bar** - Line/column position, language mode, git branch

## 🛠️ Built With

- HTML5
- CSS3 (Grid + Flexbox)
- Font Awesome 6 (free icons)
- System fonts (Segoe UI, Cascadia Code, Consolas)

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/vscode-interface-replica.git
```

2. Navigate to project directory:
```bash
cd vscode-interface-replica
```

3. Open `index.html` in your browser:
```bash
open index.html
# or double-click the file
```

No build process, no dependencies - just pure HTML/CSS.

## 🎨 Customization

### Colors
The entire theme uses VS Code's official color palette:

```css
--bg-primary: #1e1e1e;    /* main editor background */
--bg-sidebar: #252526;     /* explorer background */
--bg-activity: #333333;    /* activity bar */
--accent-blue: #0078d4;    /* selection border */
--fg-primary: #cccccc;     /* primary text */
```

### Icons
Font Awesome icons are used throughout. Change them by modifying the icon classes:

```html
<!-- Activity bar icons -->
<i class="fa-regular fa-files"></i>  <!-- explorer -->
<i class="fa-regular fa-magnifying-glass"></i>  <!-- search -->
<i class="fa-regular fa-source-control"></i>  <!-- source control -->
```

## 📁 Project Structure

```
vscode-interface-replica/
├── index.html          # Main interface
├── README.md          # Documentation
└── preview.png        # Screenshot (optional)
```

## 💡 Key Components

### Title Bar
- Windows-style window controls
- App title with workspace name
- Drag region simulation

### Activity Bar
- 5 main activity icons (explorer, search, source control, debug, extensions)
- Bottom icons (user, settings)
- Blue active indicator line

### Sidebar Explorer
- Folder tree structure
- File type-specific icons
- Header with ellipsis menu

### Editor Area
- Tab bar with multiple open files
- Active tab highlighting
- Line numbers (1-15)
- Syntax-colored code sample

### Integrated Terminal
- Panel tabs (Problems, Output, Debug Console, Terminal)
- PowerShell prompt
- Colored command output

### Status Bar
- Language mode (HTML)
- Prettier indicator
- Spaces: 4
- UTF-8 encoding
- Cursor position (Ln 10, Col 22)
- Git push indicator
- Error count

## 🎯 Use Cases

- **UI/UX Inspiration** - Reference for IDE-like interfaces
- **Frontend Practice** - Study CSS Grid and Flexbox layouts
- **Design System** - Base template for web-based code editors
- **Portfolio Piece** - Showcase attention to detail and visual fidelity

## 🔧 Browser Support

- Chrome/Edge (latest) ⭐
- Firefox (latest) ⭐
- Safari (latest) ⭐
- Opera (latest) ⭐

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**Note:** This is a visual replica for educational purposes. Not affiliated with or endorsed by Microsoft or Visual Studio Code.

## 🤝 Contributing

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📧 Contact

Om Gedam

GitHub: @itsomg134

Email: omgedam123098@gmail.com

Twitter (X): @omgedam

LinkedIn: Om Gedam

Portfolio: https://ogworks.lovable.app
