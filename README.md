# Latex Include

Some macros that help you include things in your document (sections and images).

## Table of Contents

- [Latex Include](#latex-include)
	- [Table of Contents](#table-of-contents)
	- [About](#about)
	- [Installation](#installation)
		- [Git submodule](#git-submodule)
		- [Manual](#manual)
	- [Usage](#usage)
	- [License](#license)

## About

This LaTeX package contains some helper-macros for including things such as chapters and images in your documents.
I initially wrote them for my seminar paper and extracted them to their own package during my Bachelor's thesis.
You may or may not find these useful.
Additional macros and configuration options may be added in the future.

## Installation

### Git submodule

Add this repository into a submodule of your repository: `git submodule add https://github.com/FloezeTv/latex-include`.
Then, add `ensure_path('TEXINPUTS', './latex-include/');` to your local `.latexmkrc` (modifying the path if needed).
You can then `\usepackage{include}` in your document.

### Manual

Copy [`include.sty`](include.sty) to the directory of your project.
You can then `\usepackage{include}` in your document.

## Usage

The commands have a short documentation in the comments above them.

## License

The project is licensed under the [LPPL-1.3c](https://www.latex-project.org/lppl/).