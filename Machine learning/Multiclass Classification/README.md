## Project overview
Implement One-versus-Rest (OvR) strategy transforming multiclass classification problems to multiple binary classification problems.
### One-versus-Rest
OvR involves training a binary class classifier for each class. During testing process, each classifier will predict the confidence of each class and OvR will select the one with highest confidence.

## Dataset 
**Iris** dataset

## Tasks 
**SVM**
- 1st will make 1st class label 1 and the rest classes' labels -1.
- 2nd one will make 2nd class label 1 and the rest classes' labels -1.
- 3rd one will make 3rd class label 1 and the rest classes' labels -1.

**Logistic Regression**
- 1st will make 1st class label 1 and the rest classes' labels -1.
- 2nd one will make 2nd class label 1 and the rest classes' labels -1.
- 3rd one will make 3rd class label 1 and the rest classes' labels -1.

**ArgMax**
- Using Argmax to aggregate confidence scores and obtain the final label and obtain the performance (i.e., confusion matrix, accuracy, plotting correct and wrong prediction points) of the 3 OvR-SVM models to get one OvR-SVM result.

**Visualize predictoions**
