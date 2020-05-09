# 2020_Duluth_Complex


### Conversion from .tex to .docx

Unfortunately, the Geological Society of America does not accept .tex files and require .docx. The manuscript can be converted using pandoc:

```
pandoc -s Duluth_Complex_manuscript.tex --bibliography=../../../0000_Github/references/allrefs.bib -o Duluth_Complex_manuscript.docx
```

Additional fixes need to be made. Replace the table references with the table names, fixing the n.d. in references and implementing \citealp where references have ((.
