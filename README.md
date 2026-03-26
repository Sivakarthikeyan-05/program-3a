# 🧪 C Programming Lab
# program3 3a
## 📘 Experiment No: 3a
### 🔹
**Date:** 25/2/2026  
**Name:** Sivakarthikeyan.K 
**Register No:** 25017090

---

## 🎯 AIM
To write a C program to convert a decimal number to binary number.
---

## 🧠 ALGORITHM
1.Get a decimal number as input from the user.
2.Divide the number again and again by 2 and store the remainder in an array.
3.Print the elements of the array in reverse using for loop.
---

## 💻 PROGRAM

```
#include <stdio.h>
int tobinary(int );
int tobinary(int num)
{
    int bin[32],ind=0;
    while(num>0)
    {
        bin[ind]=num%2;
        num/=2;
        ind++;
    }
    for(int j=ind-1;j>=0;j--)
    {
        printf("%d",bin[j]);
    }
    return 0;
}

```

## 🖼️ OUTPUT SCREENSHOT


<img width="829" height="189" alt="image" src="https://github.com/user-attachments/assets/459f9074-57be-4536-a2b4-5d8a4a07d348" />

---

## ✅ RESULT
: Thus the C program to convert the given decimal number to binary number is executed successfully.
