## 🧠 Assignment Result

Final Equation:
\[
\left(t*\cos(0.50905)-e^{0.0214|t|}\cdot\sin(0.3t)\sin(0.50905)+57.1429,\ t*\sin(0.50905)+e^{0.0214|t|}\cdot\sin(0.3t)\cos(0.50905)\right)
\]

Where:
- θ (Theta) = 0.50905 radians  
- M = 0.0214  
- X = 57.1429  
- Minimum Error = 38006.91  

---

### 🔍 Explanation of Process
1. Loaded the dataset containing x and y columns using `pandas`.
2. Generated a parameter array `t` using `numpy.linspace`.
3. Defined an error function that computes the total squared difference between the actual data and predicted curve points.
4. Performed a grid search across a range of θ, M, and X values to find the combination with the minimum error.
5. Printed the best parameters and their corresponding minimum error.
6. Verified that the predicted curve visually matches the dataset.

---

### 💻 GitHub Repo
All code (Google Colab notebook) is included in this repository under:
