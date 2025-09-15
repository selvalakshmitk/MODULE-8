# 🔄 Hackerrank : # 📦 count the number of vowels and consonants

---

## 🎯 Aim

To Develop a python program to count the number of vowels and consonants from the given string

---

## 🧠 Algorithm

1. Start
2. Input a string s.
3. Convert the string to lowercase (to handle both uppercase and lowercase letters).
4. Initialize two counters: vowel_count = 0, consonant_count = 0.
5. Define the set of vowels → {A, E, I, O, U, a, e, i, o, u}.
6. For each character ch in the string:
   If ch is an alphabet:
      If ch is in vowels, increment vowel_count.
      Else, increment consonant_count.
7. Display vowel_count and consonant_count.
8. Stop
---


## 🧪 Program
def fun(s):
    
    v,c=0,0
    
    for i in s:
     
        if i in ['A','E','I','O','U','a','e','i','o','u']:
        
            v+=1
        
        else:
        
            c+=1
    
    print("Number of Vowels:",v)
   
    print("Number of Consonants:",c)

s=input()
## Sample Output
<img width="844" height="226" alt="image" src="https://github.com/user-attachments/assets/4f98cb20-99af-4e05-827b-9b50c384e8c8" />


## Result
Thus, the program is excuted and verified.

