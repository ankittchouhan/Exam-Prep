
### **1. Reverse a String**
```python
def reverse_string(s):
    return s[::-1]

# Example
print(reverse_string("hello"))  # Output: "olleh"
```

---

### **2. Find Factorial**
```python
def factorial(n):
    if n == 0 or n == 1:  # Base case
        return 1
    return n * factorial(n - 1)  # Recursive call

# Example
print(factorial(5))  # Output: 120
```

---

### **3. Count Unique Characters**
```python
def count_unique_characters(s):
    return len(set(s))

# Example
print(count_unique_characters("programming"))  # Output: 8
```

---

### **4. Merge Two Sorted Lists**
```python
def merge_sorted_lists(list1, list2):
    return sorted(list1 + list2)

# Example
print(merge_sorted_lists([1, 3, 5], [2, 4, 6]))  # Output: [1, 2, 3, 4, 5, 6]
```

---

### **5. Find the Missing Number**
```python
def find_missing_number(nums, n):
    expected_sum = n * (n + 1) // 2
    actual_sum = sum(nums)
    return expected_sum - actual_sum

# Example
print(find_missing_number([1, 2, 4, 5, 6], 6))  # Output: 3
```

---

### **6. Find Duplicates in a List**
```python
def find_duplicates(nums):
    seen = set()
    duplicates = set()
    for num in nums:
        if num in seen:
            duplicates.add(num)
        else:
            seen.add(num)
    return list(duplicates)

# Example
print(find_duplicates([4, 3, 2, 7, 8, 2, 3, 1]))  # Output: [2, 3]
```

---

### **7. Longest Palindromic Substring**
```python
def longest_palindromic_substring(s):
    def is_palindrome(sub):
        return sub == sub[::-1]

    longest = ""
    for i in range(len(s)):
        for j in range(i + 1, len(s) + 1):
            if is_palindrome(s[i:j]) and len(s[i:j]) > len(longest):
                longest = s[i:j]
    return longest

# Example
print(longest_palindromic_substring("babad"))  # Output: "bab" or "aba"
```

---

### **8. Check for Balanced Parentheses**
```python
def is_balanced(s):
    stack = []
    for char in s:
        if char in "({[":
            stack.append(char)
        elif char in ")}]":
            if not stack:
                return False
            top = stack.pop()
            if char == ")" and top != "(" or \
               char == "}" and top != "{" or \
               char == "]" and top != "[":
                return False
    return not stack

# Example
print(is_balanced("((a+b)*c)"))  # Output: True
print(is_balanced("((a+b)*c))"))  # Output: False
```

---

### **9. Word Frequency in a File**
```python
def word_frequency(file_path):
    with open(file_path, "r") as f:
        text = f.read()
    words = text.split()
    frequency = {}
    for word in words:
        frequency[word] = frequency.get(word, 0) + 1
    return frequency

# Save "hello world hello" in a file named "example.txt" and use:
print(word_frequency("example.txt"))  # Output: {'hello': 2, 'world': 1}
```

---

### **10. Matrix Multiplication**
```python
def multiply_matrices(A, B):
    result = [[0 for _ in range(len(B[0]))] for _ in range(len(A))]
    for i in range(len(A)):
        for j in range(len(B[0])):
            for k in range(len(B)):
                result[i][j] += A[i][k] * B[k][j]
    return result

# Example
A = [[1, 2], [3, 4]]
B = [[5, 6], [7, 8]]
print(multiply_matrices(A, B))  # Output: [[19, 22], [43, 50]]
```

---
