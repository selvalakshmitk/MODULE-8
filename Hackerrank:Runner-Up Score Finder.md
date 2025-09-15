# 🏆 Hackerrank:Runner-Up Score Finder in Python

## 🎯 AIM:
To write a Python program that takes a list of scores from participants and finds the **runner-up score** (i.e., the second-highest score), eliminating any duplicates.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create a variable `n` and get its value from the user (number of participants)
3. Read the list of `n` scores from the user using `input().split()` and convert them to integers
4. Store the scores in a list
5. Use `set()` to remove any duplicate scores
6. Convert the set back to a list and sort it in ascending order
7. Print the second-last element of the sorted list (i.e., the runner-up score)
8. **Stop**

---

## 💻 PROGRAM:

n = int(input())

arr = list(map(int, input().split()))

arr.sort()

large=arr[-1]

arr.reverse()

for i in range(len(arr)-1):
  
    if arr[i+1]<arr[i]:
      
        print(arr[i+1])
    
        break

## OUTPUT
<img width="843" height="225" alt="image" src="https://github.com/user-attachments/assets/1fef4b79-fb1b-4b05-8041-6b5d0eb80fe5" />


## RESULT
Thus, the program is excuted and verified.
