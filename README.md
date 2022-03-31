
<!-- README.md is generated from README.Rmd. Please edit that file -->

# ggArtsyR

<!-- badges: start -->
<!-- badges: end -->

List of things to include in README from R Packages book, for our
reference:

1.  A paragraph that describes the high-level purpose of the package.

2.  An example that shows how to use the package to solve a simple
    problem.

3.  Installation instructions, giving code that can be copied and pasted
    into R.

4.  An overview that describes the main components of the package. For
    more complex packages, this will point to vignettes for more
    details.

At this point in its development, the ggArtsyR package works with
`ggplot2()` to add an additional color palette to the user’s repertoire.
This is the goghColors dataset, which contains the RGB codes of colors
picked from Van Gogh paintings. It also has a function that work
alongside `ggplot2()` to create more interesting data visualizations and
add contextual information to the user’s plots. This main function is
`RectangleFiller()`, which divides data visualizations into colored
quadrants, improving the readability of graphs.

### Example of `RectangleFiller()` using colors from goghColors dataset

``` r
# someone write code here if we can figure out how to do rectanglefiller with goghColors thatd be cool
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date. `devtools::build_readme()` is handy for this. You could also
use GitHub Actions to re-render `README.Rmd` every time you push. An
example workflow can be found here:
<https://github.com/r-lib/actions/tree/v1/examples>.

You can also embed plots, for example:

![](README_files/figure-gfm/pressure-1.png)<!-- -->

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub.
