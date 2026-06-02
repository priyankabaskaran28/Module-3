## 🧹 Strings-Remove Nth Index Character from a String

🎯 Aim

To write a Python program that accepts a string and removes the character at a specified index.

🧠 Algorithm

Define a function named remove that takes the input string as an argument.
Read the index n from the user input.
Initialize an empty string a to store the new string.
Iterate over each index of the string using a for loop.
Check if the current index i is not equal to n.
If i != n, append the character at index i to string a.
After the loop, return the modified string a.
Print the final result.

💻 Program

```
def remove(s):
    n = int(input())
    c=s[:n] + s[n+1:] 
    print(c)
```

Output:

<img width="656" height="206" alt="WhatsApp Image 2026-06-01 at 9 34 54 AM" src="https://github.com/user-attachments/assets/98125369-db8a-4d1a-88fb-64a50ef88aaf" />

Result:

Thus to write a Python program that accepts a string and removes the character at a specified index is done successfully.
