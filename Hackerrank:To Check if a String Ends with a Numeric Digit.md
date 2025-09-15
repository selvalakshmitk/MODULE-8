# 🔍 Hackerrank:Python Program to Check if a String Ends with a Numeric Digit

This Python program checks whether the last character of a given input string is a **numeric digit (0–9)**.

---

## 🎯 Aim

To write a Python program that checks if a given string ends with a number using Python's built-in string methods.

---

## 🧠 Algorithm

1. **Start the program.**
2. **Input** a string from the user.
3. **Access** the last character using indexing (`string[-1]`).
4. **Check** if the last character is a digit using the `.isdigit()` method.
5. **If true**, print that the string ends with a number.
6. **Else**, print that the string does not end with a number.
7. **End the program.**

---

## 💻  Program
s = input()

c,c1,c2,c3,c4=0,0,0,0,0

for i in range(len(s)):

    if s[i].isalnum():
    
        c+=1
    
    if s[i].isalpha():
    
        c1+=1
    
    if s[i].isdigit():
    
        c2+=1
    
    if s[i].islower():
      
        c3+=1
   
    if s[i].isupper():
     
        c4+=1

if c>=1:
    
    print('True')

else:
  
    print('False')

if c1>=1:
  
    print('True')

else:
   
    print('False')

if c2>=1:
   
    print('True')

else:
   
    print('False')

if c3>=1:
   
    print('True')

else:
  
    print('False')

if c4>=1:
  
    print('True')

else:
   
    print('False')


## Output
<img width="821" height="297" alt="image" src="https://github.com/user-attachments/assets/cfca6c8e-b912-46ff-accf-9b92de7f6bfa" />


## Result
Thus the program is excuted and verified.
