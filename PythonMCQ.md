
---

### **Object-Oriented Programming (15 Questions)**  
1. Which method in Python is used to initialize a class?  
   - a) `__init__`  
   - b) `__start__`  
   - c) `__create__`  
   - d) `__setup__`  

2. What will be the output of the following code?
   ```python
   class A:
       def __init__(self):
           print("A initialized")
   class B(A):
       def __init__(self):
           super().__init__()
           print("B initialized")
   obj = B()
   ```
   - a) A initialized  
   - b) B initialized  
   - c) A initialized  
       B initialized  
   - d) None  

3. What is method overloading in Python?  
   - a) Using the same method name with different return types  
   - b) Using the same method name with different arguments  
   - c) Both a and b  
   - d) Not supported in Python  

4. What does the `@staticmethod` decorator do?  
   - a) Declares a method as static within the class  
   - b) Binds the method to the class instance  
   - c) Makes the method callable without an instance  
   - d) None of the above  

5. Which of the following is used to prevent inheritance in Python?  
   - a) `@final` decorator  
   - b) Using private variables  
   - c) Making the class final  
   - d) Python doesn't provide any direct way  

---

### **Data Structures in Python (20 Questions)**  

6. What is the time complexity of searching for an element in a dictionary?  
   - a) O(1)  
   - b) O(n)  
   - c) O(log n)  
   - d) O(n log n)  

7. Which of the following methods is used to add an element to a set?  
   - a) `append()`  
   - b) `insert()`  
   - c) `add()`  
   - d) `push()`  

8. What is the difference between `list.sort()` and `sorted(list)`?  
   - a) `list.sort()` returns a new list, `sorted(list)` modifies in-place  
   - b) `list.sort()` modifies in-place, `sorted(list)` returns a new list  
   - c) Both perform in-place sorting  
   - d) Both return a new sorted list  

9. How do you reverse a list in Python?  
   - a) `list.reverse()`  
   - b) `list[::-1]`  
   - c) `reversed(list)`  
   - d) All of the above  

10. What is the output of the following code?
    ```python
    a = (1, 2, 3)
    b = a + (4, 5)
    print(b)
    ```
    - a) `(1, 2, 3)`  
    - b) `(1, 2, 3, 4, 5)`  
    - c) `(4, 5)`  
    - d) Error  

---

### **File Handling (10 Questions)**  

11. What is the correct way to open a file for reading in binary mode?  
    - a) `open("file.txt", "rb")`  
    - b) `open("file.txt", "wb")`  
    - c) `open("file.txt", "r")`  
    - d) `open("file.txt", "readb")`  

12. What does the `seek()` method do?  
    - a) Moves the file pointer to a specified position  
    - b) Closes the file  
    - c) Deletes the file  
    - d) None of the above  

13. Which of the following is not a valid mode for opening a file?  
    - a) `r+`  
    - b) `rw`  
    - c) `a`  
    - d) `wb+`  

14. What is the output of the following code?
    ```python
    f = open("file.txt", "w")
    f.write("Hello")
    f.close()
    f = open("file.txt", "r")
    print(f.read())
    ```
    - a) `Hello`  
    - b) `None`  
    - c) `Error`  
    - d) None of the above  

---

### **Error Handling (10 Questions)**  

15. Which block is used to handle exceptions in Python?  
    - a) `try`  
    - b) `except`  
    - c) `finally`  
    - d) All of the above  

16. What will be the output of the following code?
    ```python
    try:
        print(10 / 0)
    except ZeroDivisionError as e:
        print("Error:", e)
    ```
    - a) `Error: ZeroDivisionError`  
    - b) `Error: division by zero`  
    - c) `Error`  
    - d) None  

---

### **Libraries and Frameworks (15 Questions)**  

17. Which of the following is used for data manipulation in Python?  
    - a) `numpy`  
    - b) `pandas`  
    - c) `matplotlib`  
    - d) `scipy`  

18. How do you create a DataFrame in pandas?  
    - a) `pd.DataFrame()`  
    - b) `pandas.createDataFrame()`  
    - c) `pd.createDF()`  
    - d) None of the above  

19. What does the `head()` function in pandas do?  
    - a) Returns the first 5 rows of a DataFrame  
    - b) Returns the last 5 rows of a DataFrame  
    - c) Displays the column headers  
    - d) None of the above  

20. What is the primary purpose of the `numpy` library?  
    - a) Machine Learning  
    - b) Web development  
    - c) Numerical computing  
    - d) Database management  

---

### **Advanced Python Topics (30 Questions)**  

21. What is a Python generator?  
    - a) A function that returns multiple values at once  
    - b) A function that returns an iterator  
    - c) A class that generates objects  
    - d) None of the above  

22. What does the `yield` keyword do in Python?  
    - a) Terminates a function  
    - b) Pauses a function and returns a value  
    - c) Continues the execution of a function  
    - d) None  

23. What is the output of this code?
    ```python
    def func():
        for i in range(3):
            yield i
    print(list(func()))
    ```
    - a) `[0, 1, 2]`  
    - b) `0, 1, 2`  
    - c) `[1, 2, 3]`  
    - d) Error  

24. What is the purpose of the `with` statement in Python?  
    - a) To declare global variables  
    - b) To automatically manage resources like files  
    - c) To define decorators  
    - d) None  

---
