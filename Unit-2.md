# UNIT–II: Introduction to Programming Tools for Data Science

### 11. What is the role of Python in data science? Why is it preferred over other programming languages?
- **Role of Python**:
  - Python is widely used in data science for tasks like data cleaning, analysis, visualization, and machine learning.
  - It has numerous libraries such as Pandas, NumPy, Matplotlib, and Scikit-learn, which make data manipulation and modeling easier.
- **Why Preferred**:
  - Easy to learn and use due to its simple syntax.
  - Extensive community support and numerous libraries.
  - Cross-platform compatibility.
  - Integration with other tools and languages.

### 12. Describe the main features of the Matplotlib library and provide an example use case.
- **Main Features**:
  - Creates static, interactive, and animated visualizations.
  - Supports various plots such as line, bar, scatter, and histogram.
  - Customizable for advanced styling and formatting.
- **Example Use Case**:
  - Plotting a line graph to visualize sales trends over time.

### 13. How do you work with external data in Python, and what are some examples of tasks that can be performed?
- **Working with External Data**:
  - Use libraries like Pandas to load data from CSV, Excel, databases, or APIs.
  - Example:
    ```python
    import pandas as pd
    data = pd.read_csv('data.csv')
    ```
- **Tasks**:
  - Data cleaning (e.g., handling missing values).
  - Data transformation (e.g., feature engineering).
  - Analysis and visualization.

### 14. Explain the use of the Scikit-learn library in data science.
- **Use of Scikit-learn**:
  - A library for machine learning in Python.
  - Provides tools for classification, regression, clustering, and dimensionality reduction.
  - Example: Building a predictive model for housing prices using linear regression.

### 15. What is the NLTK library used for, and how does it facilitate text analysis?
- **NLTK (Natural Language Toolkit)**:
  - Used for natural language processing tasks.
  - Provides tools for text tokenization, stemming, lemmatization, and sentiment analysis.
  - Example: Analyzing customer reviews to determine sentiment.

### 16. How do you create a bar chart using Matplotlib? Provide a sample code.
- **Creating a Bar Chart**:
  ```python
  import matplotlib.pyplot as plt

  categories = ['A', 'B', 'C']
  values = [10, 20, 15]

  plt.bar(categories, values)
  plt.title('Bar Chart Example')
  plt.xlabel('Categories')
  plt.ylabel('Values')
  plt.show()
  ```

### 17. What are the key differences between line charts and scatterplots in data visualization?
- **Line Charts**:
  - Show trends over a continuous interval.
  - Useful for time-series data.
- **Scatterplots**:
  - Show relationships between two variables.
  - Useful for identifying correlations and outliers.

### 18. How do you read a CSV file into a Pandas DataFrame and display the first 5 rows?
- **Code Example**:
  ```python
  import pandas as pd

  df = pd.read_csv('data.csv')
  print(df.head())
  ```

### 19. What is the purpose of using `plt.subplot()` in Matplotlib, and how do you create multiple plots in one figure?
- **Purpose**:
  - To create multiple subplots in a single figure for better comparison of visualizations.
- **Example**:
  ```python
  import matplotlib.pyplot as plt

  plt.subplot(1, 2, 1)  # 1 row, 2 columns, 1st plot
  plt.plot([1, 2, 3], [4, 5, 6])
  plt.title('Line Plot')

  plt.subplot(1, 2, 2)  # 1 row, 2 columns, 2nd plot
  plt.bar([1, 2, 3], [4, 5, 6])
  plt.title('Bar Chart')

  plt.show()
  ```

### 20. How can you create a line plot using Matplotlib in Python?
- **Code Example**:
  ```python
  import matplotlib.pyplot as plt

  x = [1, 2, 3, 4]
  y = [10, 20, 15, 25]

  plt.plot(x, y)
  plt.title('Line Plot Example')
  plt.xlabel('X-axis')
  plt.ylabel('Y-axis')
  plt.show()
  ```

### 21. How do you create a 2D NumPy array and perform element-wise addition?
- **Code Example**:
  ```python
  import numpy as np

  array1 = np.array([[1, 2], [3, 4]])
  array2 = np.array([[5, 6], [7, 8]])

  result = array1 + array2
  print(result)
  ```

