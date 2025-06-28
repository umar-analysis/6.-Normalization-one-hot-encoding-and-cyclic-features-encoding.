## 🔄 Data Transformation Techniques

This part of the repository covers essential data transformation techniques that prepare features for machine learning models:

1. **📏 Normalization**  
   - Scales numerical features to a standard range (e.g., 0 to 1 or -1 to 1).  
   - Helps gradient-based models converge faster and prevents bias due to scale differences.

2. **🏷️ One-Hot Encoding**  
   - Converts categorical variables into binary columns for each category.  
   - Prevents models from assuming any ordinal relationship between categories.

3. **🔁 Cyclic Feature Encoding**  
   - Encodes cyclical features like hours of the day, days of the week, or months using sine and cosine transformations.  
   - Retains the cyclical nature of such features (e.g., 23:00 and 01:00 are close in time).

These preprocessing steps ensure that features are in a format suitable for training accurate and reliable machine learning models.
