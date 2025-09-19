## Hackerrank : # 📦 count the number of vowels and consonants
## 🎯 Aim
To Develop a python program to count the number of vowels and consonants from the given string

## 🧠 Algorithm
Start
Input a string s.
Convert the string to lowercase (to handle both uppercase and lowercase letters).
Initialize two counters: vowel_count = 0, consonant_count = 0.
Define the set of vowels → {A, E, I, O, U, a, e, i, o, u}.
For each character ch in the string: If ch is an alphabet: If ch is in vowels, increment vowel_count. Else, increment consonant_count.
Display vowel_count and consonant_count.
Stop

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
![WhatsApp Image 2025-09-15 at 14 41 03_e5b817bf](https://github.com/user-attachments/assets/1cf8ed22-3bed-410b-b6fa-ce3bcffe4b84)


## Result
Thus, the program is excuted and verified.

