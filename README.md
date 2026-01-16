# 🚀 Premium LaTeX Resume Template

<div align="center">

![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)
![TikZ](https://img.shields.io/badge/TikZ-Graphics-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Stars](https://img.shields.io/github/stars/i-am-paradox/resume?style=for-the-badge)

**A stunning, ultra-premium resume template that will make recruiters do a double-take! 🤯**

*Built with pure LaTeX & TikZ – No external icon fonts required!*

**Created by [@i-am-paradox](https://github.com/i-am-paradox)** 🔥

</div>

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🎨 **Premium Design** | Navy + Gold + Teal color scheme with gradient effects |
| ⬡ **Hexagonal Skill Meters** | Unique skill visualization that stands out |
| 🔵 **Circular Progress Rings** | Soft skills displayed as percentage circles |
| 📸 **Profile Photo Support** | Optional circular photo with gold border |
| 🏷️ **Colorful Competency Tags** | 3 variants with shadows and icons |
| 📱 **Single Page A4** | Perfect for ATS systems and printing |
| 🔧 **100% Customizable** | Easy color palette changes |
| 🚫 **No FontAwesome** | Pure TikZ icons - guaranteed compile |

---

## 📸 Preview

> **Note:** To add a preview image, compile the resume in Overleaf, download the PDF, take a screenshot, and add it as `preview.png` to your repository.

---

## 🚀 Quick Start

### Option 1: Overleaf (Recommended - No Installation!)

1. Go to [Overleaf.com](https://overleaf.com)
2. Create New Project → Upload Project
3. Upload `resume.tex`
4. Click **Recompile** → Done! 🎉

### Option 2: Local Compilation

```bash
# Clone the repository
git clone https://github.com/i-am-paradox/resume.git
cd resume

# Compile (requires TeX Live or MacTeX)
pdflatex resume.tex
pdflatex resume.tex  # Run twice for proper rendering
```

---

## 🎨 Customization

### Change Colors

Edit the color palette section in `resume.tex`:

```latex
% Primary Colors - Deep Navy Theme
\definecolor{navyDark}{RGB}{15,23,42}
\definecolor{navyMid}{RGB}{30,41,59}

% Accent Colors - Change these to match your style!
\definecolor{goldPrimary}{RGB}{245,158,11}    % Try: RGB{139,92,246} for purple
\definecolor{tealPrimary}{RGB}{20,184,166}    % Try: RGB{59,130,246} for blue
```

### Add Profile Photo

1. Add your photo as `photo.jpg` in the same folder
2. Uncomment the photo section in the header:

```latex
\begin{scope}
    \clip (1.8cm, 1.75cm) circle (1.1cm);
    \node at (1.8cm, 1.75cm) {\includegraphics[width=2.4cm]{photo.jpg}};
\end{scope}
\draw[goldPrimary, line width=2.5pt] (1.8cm, 1.75cm) circle (1.15cm);
```

### Modify Skill Levels

```latex
% Syntax: \SkillHexagon{Skill Name}{Level 1-5}
\SkillHexagon{Python}{5}      % 5 filled hexagons (Expert)
\SkillHexagon{Rust}{3}        % 3 filled hexagons (Intermediate)
```

---

## 📁 File Structure

```
premium-latex-resume/
├── resume.tex          # Main template file
├── README.md           # This file
├── LICENSE             # MIT License
├── preview.png         # Preview image for README
└── photo.jpg           # (Optional) Your profile photo
```

---

## 🔧 Requirements

- **TeX Distribution**: TeX Live, MacTeX, or MiKTeX
- **Packages Used** (all standard, auto-installed):
  - `tikz` - For all graphics
  - `tcolorbox` - For styled boxes
  - `geometry` - Page layout
  - `xcolor` - Colors
  - `enumitem` - List formatting
  - `hyperref` - Clickable links

---

## 💡 Pro Tips

1. **ATS Compatibility**: This template uses standard fonts and proper structure, making it ATS-friendly.

2. **PDF Export**: Always export as PDF for best results.

3. **One Page Rule**: Keep it to one page for most positions. The template is designed to fit perfectly.

4. **Consistent Colors**: Stick to the 3-color palette for a professional look.

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

- 🐛 Report bugs
- 💡 Suggest new features  
- 🎨 Submit design improvements
- 📝 Improve documentation

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## ⭐ Show Your Support

If this template helped you land your dream job, give it a ⭐!

---

<div align="center">

**Made with 💛 by [@i-am-paradox](https://github.com/i-am-paradox)**

*"Your resume is your first impression. Make it count!"*

[![GitHub](https://img.shields.io/badge/Follow-@i--am--paradox-181717?style=social&logo=github)](https://github.com/i-am-paradox)

</div>
