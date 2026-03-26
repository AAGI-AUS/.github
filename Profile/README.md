## Analytics for the Australian Grains Industry (AAGI) <img src="./AAGI_logo.svg" align="right"/>

Analytics for the Australian Grains Industry (AAGI) is a five-year strategic partnership aimed at harnessing analytics to drive the sector’s profitability and global competitiveness.

This GitHub organisation is the home for the AAGI project's publicly available outputs and other resources that can be shared.

AAGI is led by three strategic partners: [Curtin University](https://www.ccdm.com.au/research/aagi/), [University of Queensland](https://www.uq.edu.au/), and [University of Adelaide](https://www.adelaide.edu.au/) along with the Grains Research and Development Corporation.
The strategic partners work with project and associate partner organisations that include leading Australian and international universities, federal and state government research agencies, and commercial technology and analytics providers, to expand the sector’s analytics capability and tackle the Australian grains industry’s biggest challenges.

### AAGI-AUS R-Universe for R Users

AAGI maintains an R-Universe for easy installation of our R packages, <https://aagi-aus.r-universe.dev/packages>.
You can enable it like so:

```r
options(
  repos = c(
    aagi_aus = "https://aagi-aus.r-universe.dev",
    CRAN = "https://cloud.r-project.org"
  )
)
```

Once enabled, you can install any of our R packages by simply using `install.packages("package_name_here")`.
More detailed install instructions are provided in the packages' respective repositories.

![](./AAGI_SP_Logo_Block-Portrait.svg)
