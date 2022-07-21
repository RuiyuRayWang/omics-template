# data

Put (processed) experimental data here.

**Do NOT** push the data to git. This folder is specified to be ignored in the `.gitignore` file. Use other data repositories (i.e. Zenodo) to archive the data themselves.

If multiple modalities are involved (i.e. scRNA-seq, bulk RNA-seq, proteomics, spatial transcriptomics), create individual sub-directories to hold them.

Ideally, put the actual data somewhere in the storage system, and create symbolic links under this folder to point to the data. This is most efficient in regards to reading/writing data in an organized manner.

For example, in a linux system, data can be stored at `/mnt/disk/scRNAseq/processed_data/RuiyuRayWang/my_project/`:
```
$ ls /mnt/disk/processed_data/RuiyuRayWang/my_project/
sample1    sample2
```

Under this directory, create sym-link to the data:
```
$ ln -s /mnt/disk/processed_data/RuiyuRayWang/my_project/sample1 name_of_data1
```
