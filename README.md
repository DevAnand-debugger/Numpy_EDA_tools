# Numpy_EDA_tools
Learning EDA NumPy library
# 1️⃣ AIM

To study the NumPy library and understand its importance in data analysis and mathematical computation, especially as a foundational tool for Exploratory Data Analysis (EDA).

---

# 2️⃣ OBJECTIVE

- To understand the importance of NumPy in Python.
- To learn how to create and manipulate arrays.
- To study array dimensions and shapes.
- To perform mathematical and statistical operations.
- To understand NumPy’s role as a base library for Pandas and other data science tools.

---

# 3️⃣ INTRODUCTION TO NUMPY

NumPy (Numerical Python) is a powerful Python library used for numerical and scientific computing.

It provides:

- High-performance multidimensional arrays
- Mathematical functions
- Statistical operations
- Linear algebra operations
- Random number generation

NumPy is faster than Python lists because:
- It uses contiguous memory allocation.
- It is implemented in C.
- It supports vectorized operations.

NumPy is the foundation of:
- Pandas
- SciPy
- Matplotlib
- Scikit-learn
- TensorFlow

---

# 4️⃣ WHY NUMPY?

NumPy is used because:

- It performs mathematical operations efficiently.
- It supports multi-dimensional arrays.
- It enables vectorized computation (no need for loops).
- It consumes less memory than Python lists.
- It is the backbone of data science and machine learning libraries.

In Exploratory Data Analysis (EDA), NumPy helps in:
- Data cleaning
- Statistical calculations
- Array manipulation
- Numerical transformations

---

# 5️⃣ NUMPY ARRAY

## Definition

A NumPy array is a grid of values, all of the same type, indexed by a tuple of non-negative integers.

### Example:

1D Array:
```python
a = np.array([10, 20, 30, 40])

2D Array:

b = np.array([[1,2,3],[4,5,6]])
#6️⃣ DIMENSIONS AND SHAPE
ndim

Used to determine the number of dimensions of an array.

1D array → ndim = 1

2D array → ndim = 2

3D array → ndim = 3

shape

Returns a tuple representing the dimensions of the array.

Example:

(4,) → 4 elements in 1D

(2,3) → 2 rows and 3 columns

Understanding shape is important in:

Matrix operations

Machine learning models

Data reshaping

7️⃣ DATA TYPES IN NUMPY

Each NumPy array has a fixed data type.

Use:

a.dtype

Common types:

int32

int64

float32

float64

NumPy arrays are homogeneous (all elements must be same type).

8️⃣ ARRAY CREATION FUNCTIONS
np.zeros()

Creates an array filled with zeros.

Example:

np.zeros((2,3))
np.ones()

Creates an array filled with ones.

Example:

np.ones((3,3))
np.eye()

Creates an identity matrix.

Identity matrix:

Diagonal elements = 1

Others = 0

Example:

np.eye(3)

Used in:

Linear algebra

Matrix multiplication

Machine learning

9️⃣ SEQUENCE GENERATION FUNCTIONS
np.arange()

Generates numbers within a range.

Syntax:

np.arange(start, stop, step)

Example:

np.arange(1,10,2)
np.linspace()

Generates evenly spaced numbers between two limits.

Syntax:

np.linspace(start, stop, number_of_values)

Example:

np.linspace(0,1,5)

Used in:

Graph plotting

Numerical simulations

Data sampling

🔟 VECTOR OPERATIONS

NumPy supports element-wise operations.

Example:

c = a * 2
d = a + 5

These operations are called vectorized operations.

Advantages:

Faster than loops

Cleaner syntax

Efficient computation

1️⃣1️⃣ STATISTICAL FUNCTIONS

NumPy provides built-in statistical functions:

np.mean()

Returns average value.

np.median()

Returns middle value.

np.max()

Returns maximum value.

np.min()

Returns minimum value.

np.sum()

Returns sum of elements.

These functions are widely used in:

Data analysis

Descriptive statistics

Data preprocessing

EDA reports

1️⃣2️⃣ NUMPY IN EDA

In Exploratory Data Analysis, NumPy helps in:

Calculating summary statistics

Handling numerical datasets

Performing transformations

Normalizing data

Feature scaling

Matrix operations for ML algorithms

NumPy works together with Pandas for structured data analysis.

1️⃣3️⃣ ADVANTAGES OF NUMPY

High performance

Memory efficient

Easy mathematical computation

Supports broadcasting

Integrates with other libraries

Foundation for machine learning

1️⃣4️⃣ LIMITATIONS OF NUMPY

Not ideal for labeled data (Pandas is better)

Arrays must be homogeneous

Less flexible than Python lists

1️⃣5️⃣ REAL-WORLD APPLICATIONS

Data Science

Machine Learning

Artificial Intelligence

Financial Analysis

Signal Processing

Engineering Simulations

Computer Graphics

1️⃣6️⃣ CONCLUSION

In this experiment, we studied:

NumPy arrays and their structure

Dimensions and shape of arrays

Array creation methods

Sequence generation functions

Vectorized operations

Statistical functions

NumPy serves as the backbone of data science and EDA processes.
Understanding NumPy is essential before moving to Pandas, Matplotlib, and Machine Learning.

This experiment builds the mathematical foundation required for advanced data analysis.
## 👤 Author

**Dev Anand**  
B.Tech – Electronics & Telecommunication Engineering  
Symbiosis Institute of Technology, Pune
