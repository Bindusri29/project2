# Pneumonia Detection using Optimization and Classification Algorithms

## 🧠 Feature Extraction
- **ResNet** (Residual Neural Network): Used to extract high-level features from chest X-ray images.

## 🔍 Feature Selection (Optimization Algorithms)
1. **AAPSO** - Adaptive Altruistic Particle Swarm Optimization  
2. **DPAMPSO** - Dual Population Adaptive Mutation PSO  
3. **GA** - Genetic Algorithm *(best performance observed)*

## 🎯 Classification Algorithms
1. **SVM** - Support Vector Machine (most commonly used)  
2. **SVM with Grid Search** - Optimized hyperparameter tuning  
3. **KNN** - K-Nearest Neighbors  
4. **XGBoost** - Extreme Gradient Boosting  
5. **AdaBoost** - Adaptive Boosting

## 🧪 Experimental Setups

### MINI 1  
- **Pipeline:** ResNet + AAPSO + SVM (with Grid Search)

### MINI 2  
- **Pipeline:** ResNet + DPAMPSO + SVM

### MAJOR  
- **Pipeline:** ResNet + GA + SVM  
- **Result:** Genetic Algorithm (GA) outperformed AAPSO and DPAMPSO in feature selection.

---

## ✅ Conclusion
Among all the optimization techniques evaluated, **Genetic Algorithm (GA)** yielded the highest classification accuracy when paired with **SVM**, making it the best-performing model in this study.
