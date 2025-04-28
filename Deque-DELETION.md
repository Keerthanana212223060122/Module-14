# Exp.No:38  
## Deque - DELETION

---

### AIM  
To write a Python program to delete elements at FRONT END of deque using a collection built-in function.

---

### ALGORITHM  

1. Import the `deque` class from the `collections` module.  
2. Create an empty deque.  
3. Define how many elements to input (e.g., 3 inputs as in the example).  
4. Loop through the range of input size:  
   - Read an integer from the user.  
   - Append the integer to the deque.  
5. Remove the front element of the deque using `popleft()`.  
6. Print the final deque after deletion.  

---

### PROGRAM  

```python
import collections
a=int(input())
b=int(input())
c=int(input())
de=collections.deque([a,b,c])
de.popleft()
print("The deque after deleting is : ")
print(de)
```

### OUTPUT

![Screenshot 2025-04-28 211430](https://github.com/user-attachments/assets/479462ff-2f91-47cc-aba0-411a5b4248d0)

### RESULT
Thus Python program to delete elements at FRONT END of deque using a collection built-in function is implemented and executed successfully
