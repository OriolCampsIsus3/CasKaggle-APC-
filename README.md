# Pràctica Kaggle APC UAB 2022-23
### Nom: Oriol Camps ### DATASET: Should This Loan be Approved or Denied?
### URL: https://www.kaggle.com/datasets/mirbektoktogaraev/should-this-loan-be-approved-or-denied
## Resum
El dataset utilitza dades del SBA   
Tenim 899164 dades amb 27 atributs.
### Objectius del dataset
L'objectiu es decidir si aprovar o no un prestec a una empresa.
## Experiments
Durant aquesta pràctica hem realitzat diferents experiments.
### Preprocessat
He fet un processament de dades nan.
### Models
| Model | Hiperparametres | Accuracy |
| -- | -- | -- |
| Random Forest | criterion : gini| 92% |
| Linear SVC | penalty : l2, loss : squared_hinge | 75% |
| Decision Tree | criterion : gini| 89% |
| KNN | n_neighbors : 2| 86% |
| Logistic Regresion | penalty : l1, solver : liblinear | 86% |
| Red Neuronal | loss : binary_crossentropy, optimizer : adam| 81% |
## Conclusions
El millor model que s'ha aconseguit ha estat el RandomForest
## Idees per treballar en un futur
Crec que seria interesant indagar més en les xarxes neuronals i el deep learning ja que crec que pot ser un bon dataset per a experimentar
## Llicencia
El projecte s’ha desenvolupat sota llicència ZZZz.
