# ploidyverse.github.io

This repository contains the code for the Ploidyverse website. The website
is made using the `rmarkdown` package to convert `.Rmd` and `.md` files to
html. It automatically includes Bootstrap themes, and we use the `cosmo` theme
for our site. The file `_site.yml` controls the layout of the site and how it
is built. The code below will clone this repo, build the site using `rmarkdown`
and then open the home page in a browser.

```bash
git clone https://github.com/ploidyverse/ploidyverse.github.io.git
cd ploidyverse.github.io
Rscript -e 'rmarkdown::render_site()'
open index.html
```