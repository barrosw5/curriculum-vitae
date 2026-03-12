# Curriculum Vitae - LaTeX Source

This repository contains the LaTeX source code for my professional Curriculum Vitae, maintained in both English and Portuguese.

## Description

By treating my professional resume as code, this project ensures high-quality typesetting, consistent formatting, and ease of maintenance. The use of LaTeX allows for a clean, minimalist design that prioritizes readability while maintaining a highly professional aesthetic. 

The primary technical objectives of this repository include:
- Document-as-Code: Leveraging version control for career history management.
- Multi-language Support: Maintaining synchronized versions of the CV in different languages (English and Portuguese).
- High-Fidelity Typesetting: Utilizing LaTeX's superior layout engine for precise alignment and typography.
- Modular Structure: Organizing professional sections (Experience, Education, Skills) for easy updates and scalability.

## Features

- Bilingual Documentation: Complete versions available in both English and Portuguese.
- Clean and Minimalist Design: Optimized for both automated Applicant Tracking Systems (ATS) and human reading.
- PDF Output: Source files are configured to compile into high-quality, searchable PDF documents.
- Logical Organization: Clear separation of concerns between content (LaTeX files) and presentation (classes and styles).

## Technologies Used

- LaTeX: A high-quality typesetting system used for the production of technical and scientific documentation.
- Overleaf: Recommended environments for compiling the source code into PDF format.

## How to Use

1. Clone the repository to your local machine or import it into a LaTeX editor like Overleaf.
2. Navigate to the language folder of your choice (`/en` for English or `/pt` for Portuguese).
3. Open the main `.tex` file (e.g., `resume.tex` or `curriculo.tex`).
4. Compile the document using a LaTeX compiler (such as `pdflatex` or `xelatex`).
5. The resulting PDF will be generated in the same directory.

## Project Structure

- `en/`: Contains the English version of the CV, including the `.tex` source and the compiled `.pdf`.
- `pt/`: Contains the Portuguese version of the CV, including the `.tex` source and the compiled `.pdf`.
- `.gitattributes`: Configuration for Git to handle line endings and binary files correctly.
