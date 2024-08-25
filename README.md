# TidyVerseModelsOmics

Curated resources for learning [Tidyverse](https://www.tidyverse.org/), [Tidymodels](https://www.tidymodels.org/), [Tidyomics](https://github.com/tidyomics), and other packages built upon the [Tidy R paradigm](https://tidyr.tidyverse.org/articles/tidy-data.html).

`data/` directory: Data for coding exercises.

`reports/` directory: Contain Quarto-generated single-page HTML (`.html`) report for a corresponding `.qmd` file.

`.qmd` files: [Quarto](https://quarto.org/) files are used to document and reproduce data analyses. Quarto file (`.qmd`) is the next generation of [R Markdown](https://rmarkdown.rstudio.com/). In addition to R, Quarto also supports Python, Julia, and Observable. Quarto is an open-source scientific and technical publishing system that can do many [things](https://quarto.org/docs/guide/).

<br>

## Tidyverse

-   [Tidyverse](https://www.tidyverse.org/): The tidyverse is an opinionated [collection of R packages](https://www.tidyverse.org/packages) designed for data science. All packages share an underlying design philosophy, grammar, and data structures.
-   [R for Data Science (2e)](https://r4ds.hadley.nz/) by Hadley Wickham, Mine Cetinkaya-Rundel, and Garrett Grolemund
-   Posit Cheatsheets: [readr/readxl/googlesheets4](https://rstudio.github.io/cheatsheets/html/data-import.html), [dplyr](https://rstudio.github.io/cheatsheets/html/data-transformation.html), [tidyr](https://rstudio.github.io/cheatsheets/html/tidyr.html), [ggplot2](https://rstudio.github.io/cheatsheets/html/data-visualization.html), [stringr](https://rstudio.github.io/cheatsheets/html/strings.html), [purrr](https://rstudio.github.io/cheatsheets/html/purrr.html), [forcats](https://rstudio.github.io/cheatsheets/html/factors.html), [lubridate](https://rstudio.github.io/cheatsheets/html/lubridate.html)
-   [duckplyr](https://duckplyr.tidyverse.org/): A [DuckDB](https://duckdb.org/)-backed version of [dplyr](https://dplyr.tidyverse.org/) for ultra-fast data manipulation.
-   [tidypolars](https://github.com/etiennebacher/tidypolars): An ultra-fast library powered by Rust-based `polars` as the backend for fast data manipulation using `dplyr` API. Also, note that [Python's polars](https://pola.rs/) and [R's polars](https://pola-rs.github.io/r-polars/) share a very similar API (replace `pl.` with `pl$` in R in most cases), so it is super easy to translate polars codes from R to Python or vice versa.
-   [ggplot2: Elegant Graphics for Data Analysis (3e)](https://ggplot2-book.org/) by Hadley Wickham
-   [Data Wrangling and Visualization with R](https://rafalab.dfci.harvard.edu/dsbook-part-1/) by Rafael Irizarry
-   [Statistics and Prediction Algorithms Through Case Studies](https://rafalab.dfci.harvard.edu/dsbook-part-2/) by Rafael Irizarry
-   [Statistical Inference via Data Science–A ModernDive into R and the Tidyverse](https://moderndive.com/) by Chester Ismay and Albert Y. Kim
-   [Modern R with the tidyverse](https://modern-rstats.eu/) by Bruno Rodrigues
-   [DataCamp](https://www.datacamp.com/) skill tracks for tidyverse:
    -   [Data Manipulation with R](https://www.datacamp.com/tracks/data-manipulation-with-r)
    -   [Data Visualization with R](https://www.datacamp.com/tracks/data-visualization-with-r)
    -   [Tidyverse Fundamentals with R](https://www.datacamp.com/tracks/tidyverse-fundamentals)
    -   [Intermediate Tidyverse Toolbox](https://www.datacamp.com/tracks/intermediate-tidyverse-toolbox)

<br>

## Tidymodels

-   [Tidymodels Official Website](https://www.tidymodels.org/)
    -   [Explore tidymodels](https://www.tidymodels.org/find/): Search all packages and functions about tidymodels
    -   Use `parsnip::parsnip_addin()` to select and write out model specifications to R script
-   [Tidy Modeling with R](https://www.tmwr.org/) by Max Kuhn and Julia Silge (the textbook for tidymodels)
-   [ISLR tidymodels labs](https://emilhvitfeldt.github.io/ISLR-tidymodels-labs/) by Emil Hvitfeldt
-   [Machine learning with tidymodels](https://workshops.tidymodels.org/): posit::conf workshop materials ([github](https://github.com/tidymodels/workshops/tree/main))
-   [Feature Engineering and Selection: A Practical Approach for Predictive Models](http://www.feat.engineering/) by Max Kuhn and Kjell Johnson
-   [Three reasons to use Tidymodels — Julia Silge — R-Ladies East Lansing (English)](https://youtu.be/86KaMXHuzK4?si=Ep3xeAY3me_PVIdB). Julia Silge's [slides](https://juliasilge.github.io/r-ladies-east-lansing/#1).
-   [Supervised Machine Learning Case Studies in R](https://supervised-ml-course.netlify.app/) by Julia Silge
-   [Julia Sige's Blog](https://juliasilge.com/blog/): Contain a lot of tutorials on Tidymodels
-   [DataCamp](https://www.datacamp.com/) courses for tidymodels:
    -   [Modeling with tidymodels in R](https://www.datacamp.com/courses/modeling-with-tidymodels-in-r)
    -   [Machine Learning with Tree-Based Models in R](https://www.datacamp.com/courses/machine-learning-with-tree-based-models-in-r)
    -   [Feature Engineering in R](https://www.datacamp.com/courses/feature-engineering-in-r)

<br>

## Tidyomics

-   [Tidyomics](https://www.bioconductor.org/packages/release/bioc/html/tidyomics.html): Open project to create tidy analysis packages for omics data ([Hutchison et al., 2024](https://www.nature.com/articles/s41592-024-02299-2)).
-   [plyranges](https://www.bioconductor.org/packages/release/bioc/html/plyranges.html) ([Lee, et al., 2019](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-018-1597-8)): A Grammar of Genomic Data Transformation
    -   [Tidy Ranges Tutorial](https://tidyomics.github.io/tidy-ranges-tutorial/) by Michael Love
-   Tidy Transcriptomics:
    -   [tidybulk](https://bioconductor.org/packages/release/bioc/html/tidybulk.html) ([Mangiola, et al, 2021](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-020-02233-7)): An R tidy framework for modular bulk RNA-seq data analysis
    -   [tidyseurate](https://stemangiola.github.io/tidyseurat/) ([Mangiola, et al, 2021](https://academic.oup.com/bioinformatics/article/37/22/4100/6283576)): An R tidy framework for modular scRNA-seq data analysis
-   [tidyHeatmap](https://stemangiola.github.io/tidyHeatmap/) ([Mangiola and Papenfuss, 2020](https://joss.theoj.org/papers/10.21105/joss.02472)): An R package for modular heatmap production based on tidy principles
-   [tidyCoverage](https://bioconductor.org/packages/release/bioc/html/tidyCoverage.html) ([Serizay and Koszul, 2024](https://academic.oup.com/bioinformatics/article/40/8/btae487/7723482)): This framework enables tidy manipulation of collections of genomic tracks and features using \`tidySummarizedExperiment\` methods.
    -   [Applying tidy principles to investigating chromatin composition and architecture](https://jserizay.com/Bioc2024tidyworkshop/articles/workshop.html) by Jacques Serizay