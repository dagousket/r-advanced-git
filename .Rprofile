# use pak
options(renv.config.pak.enabled = TRUE)

source("renv/activate.R")

# ignore non-eval pkg
renv::settings$ignored.packages(
  c(
    "arrow",
    "data.table",
    "readr",
    "usethis",
    "vroom"
  ),
  persist = FALSE
)
