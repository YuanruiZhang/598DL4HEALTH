# 598DLH final

Author's Repo: https://github.com/jasminezhuoy/Clinical-Named-Entity-Recognition-From-Chinese-Electronic-Health-Records <p>
Paper: https://medinform.jmir.org/2018/4/e50/

Note:
1. We commented out the install package line and in order to run this code you will have to install those R-packages first
2. We attempted to fix the evaluation matrix but the result is still a bit off. However, running CRF and dictionary file directly will give you the score.

  
  Files
  - /Code/
  1. Dictionary.R train and evaluate the traditionary method
  2. CRF.R train and evaluate the CRF model.
  
  - /Data/
  1. Train and Test datasets

  

 ## results
  
|Window|Ngram|Precision|Recall|   F1   |  runtime |
|------|-----|---------|------|--------|----------|
| 2    | 3   | 0.9211  |0.8506| 0.8844 |  27min   |
| 3    | 3   | 0.9211  |0.8506| 0.8844 |  29min   |
| 2    | 2   | 0.9173  |0.744 | 0.8216 |  34min   |
