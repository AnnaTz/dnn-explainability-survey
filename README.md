
This repository hosts a comprehensive survey on Deep Neural Network (DNN) explainability methods. The purpose of this survey is to provide an in-depth exploration of the methodologies developed to interpret the inner workings of DNNs and understand their decisions.

## Highlights

The survey paper covers:

- A detailed review of the current state-of-the-art in DNN explainability methods.
- A taxonomy of explainability approaches, categorizing them based on their underlying principles and methodologies.
- Insights into future research directions and the evolving landscape of explainable artificial intelligence (AI).

## Why This Matters

Explainability in AI is crucial for ethical, legal, and practical reasons. As DNNs become more integrated into daily life and critical decision-making processes, understanding their decision pathways becomes essential. The survey aims to provide a comprehensive overview that aids the understanding of this newly emerging field.

## Repository Structure

- **`/source/main.tex`**: The LaTeX source file that compiles into the survey paper.
- **`/source/images`**: This directory contains all the images and figures referenced in the LaTeX document.
- **`/source/IEEEtran.cls`**: The LaTeX class file used to adhere to the IEEE transaction document style. 
- **`/source/library.bib`**: The BibTeX file containing all the bibliographic references cited in the survey.
- **`An Overview of Deep Neural Network Explainability.pdf`**: The pre-compiled PDF of the survey for quick access and reading, generated from the above resources.

## Building the Document

To compile the LaTeX document into a PDF, follow these steps:

1. Ensure a LaTeX distribution (e.g., TeX Live, MiKTeX) is installed on your system.
2. Clone this repository to your local machine.
3. Navigate to the repository's `/source` directory in your terminal.
4. Run `pdflatex main.tex` to compile the LaTeX file. If `IEEEtran.cls` is not installed in your LaTeX distribution, the included class file will be used automatically.
5. Run `bibtex main` to process the bibliography.
6. Run `pdflatex main.tex` twice more to resolve cross-references and finalize the document compilation.
7. The survey's PDF file should now be generated under `/source/main.pdf`.

## License

This work is shared under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You are free to share, copy, distribute, and transmit the work, as long as you provide appropriate credit.
