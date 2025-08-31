# LaTeX in IDE

A minimal LaTeX project setup to compile documents using LuaLaTeX with FontAwesome icons. This repository demonstrates how to include FontAwesome icons in LaTeX resumes or documents without installing the full TeXLive font packages.

---

## Features

- Use **LuaLaTeX** for compilation.
- Include **FontAwesome icons** (LinkedIn, GitHub, Email, Phone, etc.).
- Minimal dependencies; works offline.
- Ready-to-run sample LaTeX files for testing icons.

---

## Usage

1. Clone the repository:

```bash
git clone git@github.com:shyamsingh19/latex-in-ide.git
cd latex-in-ide
````

2. Compile a sample file using LuaLaTeX:

```bash
lualatex sample-files/test.tex
```

This will generate a PDF (`test.pdf`) in the repository root.

---

## File Structure

```
.
├── FontAwesome.otf                  # Font file for FontAwesome icons
├── fontawesome.sty                  # FontAwesome LaTeX package
├── fontawesomesymbols-*.tex        # Supporting FontAwesome symbol definitions
├── ufontawesome*.fd                 # Font definition files
├── sample-files/                    # Sample LaTeX documents
│   ├── sample.tex
│   └── test.tex
├── test.tex                         # Example LaTeX document
├── README.md                        # This README
```

> **Note:** The `utils/` folder and compiled outputs (`.aux`, `.log`, `.out`, `.pdf`, `.dvi`) are not required for source control.

---

## Contributing

* Make changes to `.tex` files or add new samples in `sample-files/`.
* Do **not** commit compiled PDFs, logs, or auxiliary files.
* Add new icons via the included FontAwesome package as needed.

---
