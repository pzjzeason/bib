# 科技文献可视化结课作业

### Files
1. `07-16.bib`: 2007～2016 May，566 papers
2. `95-16.bib`: 1995-2016, 1141 papers
3. `bib.Rproj`: Rstudio start file
4. `citation-report.xls`: download from WOS citation report to get citation forward every year, 673papers(whole 2016)
5. `cited-forward.csv`: citation forward every year and total(GCS)
6. `index.Rmd`: main R code
7. `keywords-freq-top20.csv`: top20 keywords(after stem) every year
8. `py.ipynb`: python code of (1) process citation-report.xls to get cited-forward.csv, (2) keywords related andburst detection
9. `selected-keywords-freq.csv`: the frequency every year of 21 author selected keywords(after stem)
10. `stem-keywords-by-year`: whole result of keywords(after stem) frequency every year
11. `zero2one.bib`: manually change those 0-cited papers to 1 cited, haven't used yet. see doubts at first part in `index.Rmd`.