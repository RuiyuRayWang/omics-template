# Omics Template

Template for omics data analysis.

Featuring:

- Compatibility for multi-modal datasets
- Compatibility for Python and R - used most frequently in omics data science
- Host your analyses documents with [Github Pages](https://pages.github.com/)

## Repository Structure

```
.
├── LICENSE
├── README.md
├── data
|   ├-- some_data
|   ├-- symlink_to_some_data
├── docs                # Rendered .html files
|   ├-- index.html
├── figures             # Generated figures
│   └── fig.png
├── miscs               # Miscellaneous
│   └── metadata.csv
├── outs                # output results
│   └── results.csv
├── pyscripts           # Python scripts
│   └── some_script.py
├── notebooks           # iPython notebooks
│   └── book.ipynb
├── rscripts            # R scripts
│   └── some_script.R
└── vignettes           # vignettes (Rmarkdown)
    └── vignette.Rmd
```

## Notes

* Avoid using special characters in directory or file names.  
  If you need a separator, use underscore `_`. DO NOT use space ` ` or dot `.`!
  Generally, the best practice is to stick with `A-Z`, `a-z`, `0-9`, `_`.
