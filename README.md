# Omics Template

Template for omics data analysis.

Featuring:

    - Multi-modal datasets
    - Multi-language

## Repository Structure

```
.
├── LICENSE
├── README.md
├── data
|   ├-- some_data
|   ├-- symlink_to_data_dir
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

* Avoid using special characters `/\?'"()[]{}|~,.;:` in directory or file names.  
  If you need a separator, use underscore `_` or hyphen `-`. DO NOT use space ` ` or dot `.`!