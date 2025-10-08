# PCA Concept Quiz (without solutions)

## **Why do we standardize the data before applying PCA?**
- [ ] A) To reduce the effect of outliers  
- [ ] B) To ensure all features have the same scale  
- [ ] C) To increase the number of principal components  
- [ ] D) Both A and B  

---

## **What does the correlation circle tell us about the relationship between the original features?**
- [ ] A) How original features relate to the principal components  
- [ ] B) How features cluster in lower dimensions  
- [ ] C) The distribution of categorical variables in PCA space  
- [ ] D) The impact of outliers on PCA results  

---

## **What are the advantages of reducing dimensionality using PCA?**
- [ ] A) Reduces noise and redundancy in the dataset  
- [ ] B) Improves model efficiency and visualization  
- [ ] C) Ensures better feature selection for machine learning  
- [ ] D) Both A and B  

---

## **Singular Values (`pca.singular_values_`): What does it mean if a singular value is much larger than the others?**
- [ ] A) The corresponding principal component explains significantly more variance  
- [ ] B) The dataset is highly correlated in that direction  
- [ ] C) Some features may be redundant  
- [ ] D) All of the above  

---

## **Covariance Matrix (`pca.get_covariance()`): How does the covariance matrix change after PCA compared to the original dataset?**
- [ ] A) The covariance values become zero because PCA removes correlations  
- [ ] B) The covariance matrix becomes diagonal, meaning features are now uncorrelated  
- [ ] C) The covariance values increase because PCA introduces more relationships  
- [ ] D) The covariance matrix remains unchanged after PCA   

---

## **Feature Names in PCA Space (`pca.get_feature_names_out()`): Why do we have fewer features after PCA?**
- [ ] A) PCA removes features that are less important  
- [ ] B) PCA creates new transformed features (principal components), replacing the original ones  
- [ ] C) The original feature names are lost in the transformation  
- [ ] D) PCA only selects a subset of the original features  
