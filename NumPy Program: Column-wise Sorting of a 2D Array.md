# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```
import numpy as np
a=eval(input())
array = np.array(a)
print('Given array','\n',array)
print()
print(np.sort(array,axis=0))
```

## Output
<img width="816" height="619" alt="528598972-31d4be29-4e89-4674-8138-7802ac60af53" src="https://github.com/user-attachments/assets/f0749739-5442-4fab-a1f8-e3d70c05e199" />

## Result
Thus a NumPy program that sorts the elements in each column of a given 2D array in ascending order is executed successfully.
