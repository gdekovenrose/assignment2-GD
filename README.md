# assignment2-GD
for individual assignment 2 qac 380: Git/Github Exercise
# Assignment 2 – [Your Name]

## Dataset
This project uses `penguins.csv`, the Palmer Penguins dataset. It has measurements for 344 penguins from three species (Adelie, Chinstrap, Gentoo) on three islands in Antarctica, including bill length, bill depth, flipper length, body mass, and sex.

## Analysis script
`penguins_analysis.Rmd` is an R Markdown script that:
- Loads `penguins.csv`
- Calculates the mean bill length (ignoring missing values)
- [Your second analysis, e.g., a frequency table of species]

The knitted output is saved as `penguins_analysis.html`.

## How to reproduce
1. Clone or download this repository.
2. Open `penguins_analysis.Rmd` in RStudio.
3. Install the needed packages if you don't have them: `install.packages(c("descr", "ggplot2"))`
4. Click **Knit**. The data file is in the same folder, so no file paths need changing.