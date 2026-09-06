# Kenta Utsunomiya - Resume (LaTeX)

This repository contains the LaTeX source code for Kenta Utsunomiya's English CV / Resume, based on the clean, professional, and ATS-friendly format adapted from [Overleaf](https://www.overleaf.com/articles/vidushi-wahals-cv/wpcddrydqwsj).

---

## 📁 File Structure

- [`resume.tex`](resume.tex): Main LaTeX document containing the CV content and styling.

---

## 🚀 How to Compile to PDF

### Method 1: Overleaf (Recommended & Easiest)
1. Go to [Overleaf](https://www.overleaf.com/).
2. Click **New Project** -> **Upload Project** (or **Blank Project** and paste the content of `resume.tex`).
3. Press **Recompile** to generate and download the PDF.

### Method 2: Local Compilation (Linux / macOS)

If you have TeX Live or MacTeX installed:

```bash
pdflatex resume.tex
```

To install TeX Live on Fedora Linux:
```bash
sudo dnf install texlive-scheme-basic texlive-collection-latexextra texlive-titlesec texlive-enumitem
```

On Ubuntu / Debian:
```bash
sudo apt-get install texlive-latex-base texlive-latex-extra
```

---

## ✏️ Customization Tips

- **Bullet Points**: Tailor the bullet points in the `Experience` section using the **Google XYZ formula**:
  > *"Accomplished [X] as measured by [Y], by doing [Z]"*
- **Skills**: Update the `Skills & Technologies` section based on the specific job application requirements.
- **Links**: URLs are configured with clickable hyperlinks via the `hyperref` package without ugly colored boxes.

