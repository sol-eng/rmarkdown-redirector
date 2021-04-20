# RMarkdown Redirector

"These are not the droids you're looking for"

Customizable, via a `REDIRECT_URL` environment variable for easy configuration
inside of RStudio Connect.

Further, there is a `manifest.json` so you can just point RStudio Connect at
this repository for easy deployment with [Git-backed
content](https://blog.rstudio.com/2019/06/24/rstudio-connect-1-7-6/)!

```
REDIRECT_URL=/other-droids/
```

## NEWS

- 2021-04-20 - BREAKING - switch "main" content to the `rmd/` subdirectory, as
we now have a `shiny/` variant as well
