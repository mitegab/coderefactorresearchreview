# Code Refactoring Research Review

## Project Overview
This repository contains a systematic literature review of code refactoring practices, focusing on the reasons and motivations behind refactoring activities in modern software development (2022-2025).

## Abstract
Code refactoring is a critical practice in software engineering that involves restructuring existing code without changing its external behavior. This systematic review examines recent research (2022-2025) on code refactoring, focusing exclusively on the primary reasons that drive refactoring activities in modern software development. Through a comprehensive analysis of recent literature, we identify and categorize the key motivations behind refactoring decisions.

Our findings reveal that technical debt management, maintainability enhancement, preparation for feature extension, performance optimization, and code smell removal are the most prevalent reasons for refactoring. Additionally, we identify emerging drivers such as architectural alignment, security enhancement, and test improvement. This review provides valuable insights for researchers and practitioners seeking to understand why and when refactoring should be performed in contemporary software development projects.

## Repository Contents
- `text.tex`: The main LaTeX document containing the full research paper
- `presentation.tex`: A Beamer presentation based on the research paper
- `coverpage.tex`: A standalone cover page for the document
- `aastu.png`: AASTU university logo for the cover page

## Key Findings
Our analysis revealed several key categories of reasons that drive code refactoring:

1. **Technical Debt Management (85%)**: Most frequently cited reason for refactoring
2. **Maintainability Enhancement (78%)**: Making code easier to understand, modify, and extend
3. **Preparation for Feature Extension (65%)**: Ensuring code can accommodate new functionality
4. **Performance Optimization (52%)**: Improving response time, resource utilization, scalability
5. **Code Smell Removal (48%)**: Addressing symptoms of deeper code problems

Emerging drivers include:
- Architectural Alignment (35%)
- Security Enhancement (28%)
- Test Improvement (25%)

## How to Compile the Documents
To compile the LaTeX documents, you'll need a LaTeX distribution installed (such as TeX Live on Linux/MacOS or MiKTeX on Windows).

### Compiling the main paper:
```bash
pdflatex text.tex
bibtex text
pdflatex text.tex
pdflatex text.tex
```

### Compiling the presentation:
```bash
pdflatex presentation.tex
```

### Compiling the cover page:
```bash
pdflatex coverpage.tex
```

## Authors
This research was conducted by students from Addis Ababa Science and Technology University:
- Kirubel Ateka (ETS0734/13)
- Kirubel Dagnchew (ETS0735/13)
- Laelay Temesgen (ETS0746/13)
- Natnael Endale (ETS1008/13)
- Dessalegn Sendek (ETS1553/13)
- Mitiku Abebe (ETS0904/13)
- Natnael Mulugeta (ETS1020/13)

## License
This project is licensed under the MIT License - see the LICENSE file for details.


 2025 AASTU Software Engineering
