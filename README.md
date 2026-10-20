# NumPy Student Marks Analysis

**Veda Technology | AI & ML Internship | Level 1, Task 11**

## Overview
This project uses NumPy to create an array of student marks and calculate key statistical values: mean, median, maximum, minimum, and standard deviation.

## Objective
Learn how NumPy can efficiently perform numerical analysis.

## Tools Used
- Python
- NumPy
- Jupyter Notebook / Google Colab

## Approach
1. Created a NumPy array with 10 manually created student marks.
2. Used built-in NumPy functions to compute the statistics:
   - `np.mean()` for the average
   - `np.median()` for the middle value
   - `np.max()` and `np.min()` for the highest and lowest marks
   - `np.std()` for the standard deviation
3. Displayed each result clearly.

## Code
```python
import numpy as np

# Student marks (manually created)
marks = np.array([78, 85, 92, 67, 74, 88, 95, 60, 81, 70])

print("Marks array :", marks)
print("Mean        :", np.mean(marks))
print("Median      :", np.median(marks))
print("Maximum     :", np.max(marks))
print("Minimum     :", np.min(marks))
print("Std Dev     :", round(np.std(marks), 2))
```

## Results
| Statistic | Value |
|-----------|-------|
| Mean | 79.0 |
| Median | 79.5 |
| Maximum | 95 |
| Minimum | 60 |
| Standard Deviation | 10.76 |

## Explanation of Results
The mean (79.0) is the class average. The median (79.5) is very close to the mean, which shows the marks are evenly distributed with no extreme outliers. The highest mark is 95 and the lowest is 60. A standard deviation of about 10.76 means the marks typically spread around 11 points from the average, which is a moderate variation.

## Files
- `student_marks.ipynb` : Notebook with code and output
- `README.md` : Project documentation

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/sanzayjanarthanan/<repo-name>.git
   ```
2. Install NumPy:
   ```bash
   pip install numpy
   ```
3. Open `student_marks.ipynb` in Jupyter Notebook or Google Colab and run all cells.

## Conclusion
NumPy's built-in functions compute these statistics in a single line each, without manual loops. This is why NumPy is the foundation for libraries like Pandas, scikit-learn and TensorFlow in machine learning workflows.

## Author
**J Sanjay**
AI & Data Science Student, Velammal Institute of Technology, Chennai
GitHub: [sanzayjanarthanan](https://github.com/sanzayjanarthanan)
