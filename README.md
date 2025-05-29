📘 User Guide – _Quarto_ASlab-web
=================================

🧰 Requirements:
----------------
To run this website project, make sure you have:

- [R](https://cran.r-project.org/) installed (version 4.0 or later)
- [RStudio](https://posit.co/download/rstudio-desktop/) installed
- [Quarto CLI](https://quarto.org/docs/get-started/) installed  
  → You can verify it by running:
    ```
    quarto check
    ```
- The `quarto` R package installed:
    ```r
    install.packages("quarto")
    ```

🚀 How to render the website:
-----------------------------

✅ Easiest method – use RStudio:
1. Open `_Quarto_ASlab-web.Rproj` in RStudio.
2. In the **Files** tab, open the file `build.R`.
3. Click the **Source** button (top right corner of the editor).
4. The website will be rendered into the `_site/` directory.

✅ Alternatively, use R Console:
```r
source("build.R")
