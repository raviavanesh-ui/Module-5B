# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program

Add code here
```
import numpy as np

x = np.array([10, 20, 30, 40, 50])
y = np.array([15, 20, 25, 45, 10])

indices = np.where(x >= y)

print(f"Array x: {x}")
print(f"Array y: {y}")
print("-" * 20)
print(f"Indices where x >= y: {indices[0]}")

```
## Output
<img width="511" height="132" alt="569199562-807c1e47-02e7-4d51-a48d-22e784208528" src="https://github.com/user-attachments/assets/13bd47a6-e455-4f66-a9bc-69551c863e6f" />

## Result
Thus,the program has been executed successfully.
