# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program

Add code here
```
import pandas as pd

student_data1 = pd.DataFrame({
    'student_id': ['S1', 'S2', 'S3'],
    'name': ['Alice', 'Bob', 'Charlie'],
    'marks': [85, 92, 78]
})

student_data2 = pd.DataFrame({
    'student_id': ['S4', 'S5', 'S6'],
    'name': ['David', 'Eve', 'Frank'],
    'marks': [88, 76, 95]
})

combined_data = pd.concat([student_data1, student_data2], axis=0)

print("Combined DataFrame:")
print(combined_data)

```
## Output
<img width="442" height="213" alt="569200945-0cbff817-5ddd-4c1e-adf7-fef257854174" src="https://github.com/user-attachments/assets/555f787b-faa2-40c4-96ef-f6c30d4b4a82" />

## Result
Thus,the program has been executed successfully.
