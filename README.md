# levdopa_synthesis
Genome-scale FBA, thermodynamic, and stoichiometric analysis of engineered levdopa synthesis in E. coli.

Final project for Thayer School of Engineering at Dartmouth College ENGS 161, metabolic engineering.

## Analysis Notebooks

The following Jupyter notebooks contain the analysis done for the project:

* `FBA analysis.ipynb`: Flux balance analysis
* `thermodynamics.ipynb`: Black box and open box thermodynamic analyses
* `black box stoichiometry.ipynb`: Black box stoichiometric analyses

## Required Dependencies

* Jupyter Lab
* Equilibrator
* Equilibrator-Pathway
* Cobra
* Pandas
* Numpy
* Matplotlib
* Escher
* SBtab

## External data

The following external metabolomics datasets are used in this project

* BiGG Models _E. coli_ core [http://bigg.ucsd.edu/models/e_coli_core](http://bigg.ucsd.edu/models/e_coli_core)
* Relevant KEGG Pathways
  - (https://www.kegg.jp/kegg-bin/show_pathway?map01063)[https://www.kegg.jp/kegg-bin/show_pathway?map01063]
  - (https://www.kegg.jp/kegg-bin/show_pathway?org_name=eco&mapno=00400&mapscale=&show_description=hide)[https://www.kegg.jp/kegg-bin/show_pathway?org_name=eco&mapno=00400&mapscale=&show_description=hide]
  - (https://www.kegg.jp/kegg-bin/show_pathway?map00030)[https://www.kegg.jp/kegg-bin/show_pathway?map00030]

## References

* (http://jpet.aspetjournals.org/content/jpet/195/3/453.full.pdf)[http://jpet.aspetjournals.org/content/jpet/195/3/453.full.pdf]
* (https://apps.who.int/iris/bitstream/handle/10665/93142/EML_18_eng.pdf;jsessionid=BCB6FBC3AFB8913EB126C251473F6D05?sequence=1)[https://apps.who.int/iris/bitstream/handle/10665/93142/EML_18_eng.pdf;jsessionid=BCB6FBC3AFB8913EB126C251473F6D05?sequence=1]
* (https://www.nature.com/articles/srep30080)[https://www.nature.com/articles/srep30080]
* (https://link.springer.com/article/10.1007/s10295-011-0973-0)[https://link.springer.com/article/10.1007/s10295-011-0973-0]
