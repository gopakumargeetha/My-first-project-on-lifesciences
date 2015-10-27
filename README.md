# My-first-project-on-lifesciences

---
title: "LGG-gene-expression"
date: \`r format(Sys.Date(), "%B %d, %Y")`\'
output: html_document
---

This is an R Markdown document for the gene-expression analysis of low grade 
glioblastama (LGG) data. There are three possible goals in genomics which we can try using this data.

1. **Class prediction**: According to some labelling of samples (group 0 and group 1), can we predict the status of subjects/samples by exploiting the expression profiles?? This is a **supervised machine learning algorithm** where the desired output is known and it generates a function of inputs to desired outputs.

2. **Class comparison**: Are there any differences in the expression profiles between labelled groups of samples. This is also a **supervised machine learning algorithm**.

3. **Class discovery**: Are there any classses in the data groups of the samples characterised by the expression profiles. This is a **unsupervised machine learning algorithm**. Random Forest, Clustering algorithm etc.,


**Files provided:**  
1. expression_data_LGG  (Genes Vz. sample)
2. brain_LGG_subset    (patient id, group)
