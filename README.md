# Complex-Network-Theory

LaTeX sources for complex networks and graph theory coursework: problem sheets, exam-style questions, and worked solutions.

## Contents

| File | Description |
|------|-------------|
| `network_problem_G.tex` | Problem set on a 15-node tree network \(G\) (links, degrees, diameter, centralities, cycles). |
| `network_solutions_G.tex` | Solutions for the above. |
| `MTH6142_2024_Q1.tex` | MTH6142 (2024) Question 1 — directed network on 5 nodes, centralities, Katz, efficiency. |
| `MTH6142_2024_Q2.tex` | MTH6142 (2024) Question 2 — growing network with \(\Pi_i \propto k_i-1\). |
| `MTH6142_2024_Q2_solutions.tex` | Solutions for MTH6142 (2024) Q2. |
| `exam_directed_Q1_40marks.tex` | Directed 5-node exam question (40 marks) with diagram. |
| `exam_directed_Q1_40marks_solutions.tex` | Solutions. |
| `exam_growth_Q2_35marks.tex` | Growth model with \(n_0=10\), \(m=3\), initial attractiveness \(a\). |
| `exam_growth_Q2_35marks_solutions.tex` | Solutions. |

## Build

Requires a LaTeX distribution (e.g. [TeX Live](https://tug.org/texlive/)) with `amsmath`, `geometry`, `enumitem`, and **TikZ** (for files that include figures).

```bash
pdflatex network_problem_G.tex
pdflatex exam_directed_Q1_40marks.tex
# …repeat for other `.tex` files as needed
```

Run `pdflatex` twice if you add cross-references or a table of contents later.

## Repository

Course materials are provided as plain `.tex` so they are easy to edit, diff, and version control. PDFs and JPEGs are not stored in this repository.
