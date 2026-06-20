# lifesimulatoR-book

**lifesimulatoR-book** is a companion book to the `lifesimulatoR` R package. 

It provides the theoretical and scientific context behind the package's simulations, covering major origin-of-life theories including molecular evolution, RNA World hypotheses, protocell models, autocatalytic networks, diversity and complexity metrics, and competing frameworks for abiogenesis.

Each chapter follows a consistent structure:

1. Scientific theory and background
2. Conceptual models and simplifying assumptions
3. Computational examples using `lifesimulatoR`
4. Interpretation of simulation results
5. Discussion questions and educational exercises

This book explains origin-of-life theories, introduces conceptual models, demonstrates how to explore those models using `lifesimulatoR`, and provides interpretation guidance for students, instructors, and science communicators.
It is designed for teaching, self-study, workshops, science communication, and exploratory research into the origins of life and the emergence of biological complexity.

## Suggested workflow

```r
install.packages(c("bookdown", "rmarkdown", "knitr", "ggplot2", "remotes"))

remotes::install_github("NoushinN/lifesimulatoR")

bookdown::render_book("index.Rmd")
```

## Book structure

- Origin of Life: Big Questions
- Prebiotic Chemistry and Molecular Pools
- Molecular Evolution
- Mutation and Selection
- Diversity, Entropy, and Complexity
- Protocells and Compartmentalization
- Autocatalytic Networks
- Comparing Origin-of-Life Hypotheses
- Classroom Labs and Activities
- Package Function Reference

## License

MIT License.

Copyright (c) 2026 Noushin Nabavi

## Citation

If you use this book, please cite:

Nabavi, N. (2026). *lifesimulatoR-book: A Companion Book for Teaching Origin-of-Life Concepts with Computational Simulations*. 

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20767188.svg)](https://doi.org/10.5281/zenodo.20767188)
