-------
# My Personal Learning Notes For Calculus With Analytic Geometry 2nd Edition

This repository contains the solutions to exercises from the second edition of `Calculus With Analytic Geometry` by George F. Simmons, along with my reflections and insights on the exercises. It serves as a personal record of my learning journey through this influential textbook.

## Project Organization Overview

This project is meticulously structured to ensure efficient navigation and simplified maintenance. Here's an overview of its organization:

1. Each section is written in its own `.tex` file labeled `sec_XX_YY.tex`.
1. Within each chapter, a dedicated folder labeled `ch_XX` contains all `.tex` files relevant to the XXth chapter. Including individual section files `sec_XX_YY.tex`, and a master file `ch_XX.tex` consolidates them.
1. At the project's root level, `main.tex` integrates all chapter files.
1. `elegantbook.cls` is a revised version of the [ElegantBook](https://github.com/ElegantLaTeX/ElegantBook) template originally crafted by [Ethan Deng](https://github.com/EthanDeng) and [Liam Huang](https://github.com/Liam0205), serving as the project's template.

## Building the Project

To build pdf file, following these steps: 
```console

# Clone the repository to your local machine
git clone https://github.com/wisherhxl/LearningNoteForCalculusWithAnalyticGeometry2nd.git

# Navigate to the project directory
cd /path/to/the/project/repository

# Compile using xelatex
xelatex main.tex

# Run biber to process the bibliography
biber main

# Compile twice with xelatex to incorporate the bibliography
xelatex main.tex
xelatex main.tex

```

## License

This project is licensed under the terms of the MIT license. See the [LICENSE](LICENSE) file for details.

This project includes the `elegantbook.cls` file originally provided by [ElegantLaTeX](https://github.com/ElegantLaTeX) under the LaTeX Project Public License, v1.3c or later. Please refer to [CTAN](https://ctan.org/license/lppl) for more information.

