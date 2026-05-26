# IA-Template-Report

# 📄 IAGI LaTeX Report Template
### Computer Science & Artificial Intelligence — Hassan II University


---

A free, fully structured LaTeX report template for undergraduate final year project students in **Artificial Intelligence and Computer Science (IAGI)**. Designed to guide students through every chapter of their report with embedded writing guidance, structured skeletons, and practical LaTeX examples.

> 🟡 **Overleaf Gallery submission is pending approval.** Once confirmed, the template will be available as a one-click Overleaf template. In the meantime, use it directly from this repository.

---

---

## 📁 Repository Structure

```
IAGI-LaTeX-Report-Template/
│
├── main.tex                    # Main entry point — compile this file
├── CS_report.sty               # Style file — DO NOT modify unless needed
├── references.bib              # BibTeX reference file
│
├── chapters/
│   ├── 00_general_intro.tex    # General Introduction (unnumbered)
│   ├── 01_introduction.tex     # Chapter 1: Introduction
│   ├── 02_literature.tex       # Chapter 2: Literature Review
│   ├── 03_methodology.tex      # Chapter 3: Methodology
│   ├── 04_results.tex          # Chapter 4: Results
│   ├── 05_discussion.tex       # Chapter 5: Discussion and Analysis
│   ├── 06_conclusions.tex      # Chapter 6: Conclusions and Future Work
│   └── 07_reflection.tex       # Chapter 7: Reflection
│
├── figures/
│   └── chart.pdf               # Example figure used in Chapter 3
│
├── frontmatter/
│   ├── declaration.tex         # Declaration page
│   ├── abstract.tex            # Abstract page
│   └── acknowledgements.tex    # Acknowledgements page
│
└── README.md                   # This file
```

---

## 🚀 Getting Started

### Option 1 — Overleaf (Recommended)
> ⏳ Pending approval in the Overleaf Gallery. Once live, click **"Open in Overleaf"** and start writing immediately — no setup required.

### Option 2 — Use from GitHub

1. **Clone or download** this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/IAGI-LaTeX-Report-Template.git
   ```

2. **Open** `main.tex` in your LaTeX editor (Overleaf, TeXStudio, VS Code + LaTeX Workshop, etc.)

3. **Compile** using `pdfLaTeX` + `BibTeX` + `pdfLaTeX` × 2:
   ```
   pdflatex main.tex
   bibtex main
   pdflatex main.tex
   pdflatex main.tex
   ```

4. **Start writing** — replace all `[REPLACE THIS]` markers with your own content.

> ✅ The template compiles out of the box with no errors. All placeholder `\includegraphics` lines are commented out so no missing figure errors occur.

---

## 📖 Template Structure

The template follows the standard structure for undergraduate final year project reports:

| # | Chapter | What it covers |
|---|---------|----------------|
| — | General Introduction | Report framing, font and formatting rules |
| 1 | Introduction | Host organisation, problem statement, aims & objectives, solution approach, project management |
| 2 | Literature Review | Organising a review, synthesis vs. summarising, citation guide, plagiarism avoidance |
| 3 | Methodology | Report structure types, ethical considerations, LaTeX examples (equations, figures, algorithms, code) |
| 4 | Results | Algorithm performance, data-driven findings, ablation study, summary table |
| 5 | Discussion and Analysis | Interpretation frameworks, ablation analysis, significance, limitations |
| 6 | Conclusions and Future Work | Structured conclusion skeleton, short/long-term future work |
| 7 | Reflection | 5-paragraph reflection framework |

---

## ✨ Key Features

- **Three project type templates** — algorithm analysis, application development, and science lab experiment structures included in Chapter 3
- **Ablation study support** — correctly placed in both Results (what happened) and Discussion (why it matters)
- **Structured skeletons** — every chapter has `[REPLACE THIS]` markers so you always know what to write and where
- **Literature Review guidance** — explicit advice on thematic organisation and synthesis vs. summarising, the most commonly missing skill in student reviews
- **Harvard referencing** via BibTeX as default, with a built-in switch to IEEE numbered style
- **LaTeX examples included** — equations (`\eqref`), figures, algorithms (`algorithmicx`), and code listings in Python, Java, and C++
- **Compiles immediately** — no missing files, no broken references out of the box
- **Consistent cross-referencing** — every section and subsection has a `\label{}` for reliable `\ref{}` and `\Cref{}` usage throughout

---

## ✏️ How to Use This Template

### Step 1 — Fill in your details
Open `main.tex` and update:
```latex
\title{Your Project Title}
\author{FirstName(s) LastName}
\date{Month Year}
```

### Step 2 — Replace all placeholders
Search for `[REPLACE` across all chapter files and fill in your content. Every placeholder is clearly labelled, for example:
```latex
This project investigated \textit{[REPLACE: state the problem that was investigated]}.
```

### Step 3 — Add your references
Add your sources to `references.bib` in BibTeX format. Cite them using:
```latex
\cite{key}      % → Author et al. (2019)
\citep{key}     % → (Author et al., 2019)
```

### Step 4 — Add your figures
Place your figure files in the `/figures` folder and uncomment the `\includegraphics` lines:
```latex
% Before (placeholder):
% \includegraphics[width=0.75\textwidth]{figures/your_figure.png}

% After (your figure added):
\includegraphics[width=0.75\textwidth]{figures/your_figure.png}
```

### Step 5 — Switch referencing style (optional)
To switch from Harvard to IEEE, open `CS_report.sty` and follow the instructions in the `Bibliography/References settings` section.

---

## 📋 Requirements

| Tool | Version |
|------|---------|
| LaTeX distribution | TeX Live 2020+ or MiKTeX 2020+ |
| Compiler | pdfLaTeX or XeLaTeX |
| Bibliography | BibTeX |
| Key packages | `natbib`, `algorithmicx`, `listings`, `booktabs`, `hyperref`, `cleveref` |

> All required packages are included in standard TeX Live and MiKTeX distributions. No manual installation needed.

---

## 🗺️ Roadmap

- [x] Base report template (this repository)
- [x] Submitted to Overleaf Gallery — awaiting approval
- [ ] 🍳 **Dev & Test Template** *(in development)* — a dedicated template for software engineering and testing projects with adapted chapter structures for requirements, system design, implementation, and testing chapters
- [ ] French language version
- [ ] Master's level variant

---

## 🤝 Contributing

Contributions, suggestions, and bug reports are welcome!

1. Fork the repository
2. Create a new branch: `git checkout -b fix/your-fix-name`
3. Commit your changes: `git commit -m 'Fix: describe what you changed'`
4. Push to the branch: `git push origin fix/your-fix-name`
5. Open a Pull Request

For major changes, please open an issue first to discuss what you would like to change.

---

## 📬 Feedback and Issues

Found a bug? Have a suggestion? Open an [issue]([https://github.com/YOUR_USERNAME/IAGI-LaTeX-Report-Template](https://github.com/badrhr/IA-Template-Report/issues) on GitHub or reach out directly.

If you used this template for your report, a ⭐ on the repository is always appreciated — it helps other students find it!

---

## 📜 License

You are free to use, modify, and distribute it, including for academic submissions. Attribution is appreciated but not required.

---

## 👤 Author

**Badr HIRCHOUA**
Department of Computer Science
Hassan II University — IAGI (Intelligence Artificielle et Génie Informatique)

[![LinkedIn]([https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://linkedin.com/in/YOUR_PROFILE](https://www.linkedin.com/in/xproce/))
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?logo=github)]([https://github.com/YOUR_USERNAME](https://github.com/badrhr/))

---

> 💡 *"A well-structured report is not just a requirement — it is the first demonstration of your ability to communicate complex ideas clearly."*
