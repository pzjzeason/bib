# 科技文献可视化结课作业

### Files
1. `07-16.bib`: 2007～2016 May，566 papers
2. `95-16.bib`: 1995-2016, 1141 papers
3. `bib.Rproj`: Rstudio start file
4. `burst-result.csv`: keywords burst result
5. `citation-report.xls`: download from WOS citation report to get citation forward every year, 673papers(whole 2016)
6. `cited-forward.csv`: citation forward every year and total(GCS)
7. `index.Rmd`: R code and result analysis
8. `index.html`: html generated from R markdown. **Recommend to read this**
9. `keywords-freq-top20.csv`: top20 keywords(after stem) every year
10. `py.ipynb`: python code of (1) process citation-report.xls to get cited-forward.csv, (2) keywords related andburst detection
11. `selected-keywords-freq.csv`: the frequency every year of 21 author selected keywords(after stem)
12. `stem-keywords-by-year`: whole result of keywords(after stem) frequency every year
13. `zero2one.bib`: we manually change those 0-cited papers to 1 cited, but haven't used yet. see doubts at first part in `index.Rmd`.