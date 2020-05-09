# Rapid emplacement of massive Duluth Complex intrusions within the Midcontinent Rift

This repository contains the manuscript, data, and code associated with a manuscript submitted to Geology on May 9, 2020 entitled: **Rapid emplacement of massive Duluth Complex intrusions within the Midcontinent Rift** by Swanson-Hysell, N.L., Hoaglund, S.A., Crowley, J.L., Schmitz, M.D., Zhang, Y., and Miller Jr., J.D.

## Code 

This folder contains a Jupyter notebook developed using a Python 3 kernel that generates the figures and conducts the data analysis associated with the study. This notebook can be viewed here: https://github.com/Swanson-Hysell-Group/2020_Duluth_Complex/blob/master/code/Duluth_Complex_notebook.ipynb

## Data

This folder contains new and compiled paleomagnetic, geochronologic and geologic data.

## Manuscript

This folder contains the .tex source file and the compiled PDF of the manuscript associated with the study. It also contains the version submitted to Geology as a .docx file.

### Conversion from .tex to .docx

Unfortunately, the Geological Society of America does not accept .tex files and require .docx. The manuscript can be converted using pandoc which was done for this manuscript:

```
pandoc -s Duluth_Complex_manuscript.tex --bibliography=../../../0000_Github/references/allrefs.bib -o Duluth_Complex_manuscript.docx
```

Additional fixes need to be made. Replace the table references with the table names, fixing the n.d. in references and implementing \citealp where references have ((.
