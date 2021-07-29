# liver-disease-classification

## Methodology

The dataset comprised of 10 attributes, 1 class label and 583 patient records. There were only 4 missing values for A/G ratio across the entire dataset. Since the sample size was small, removal of the instances with missing values was not considered and instead the missing values were imputed with the mean A/G ratio. The nominal gender variable was mapped to numerical values (Female = 1 and Male = 2). The class label was renamed as ‘disease’ and changed to a boolean variable where the disease group remained as 1 and those without liver disease were recoded to 0.