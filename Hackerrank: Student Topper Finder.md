# # 🔢 Hackerrank:# 🏆 Student Topper Finder

This Python program helps determine the **top-performing student** based on the total marks across five subjects. It uses a dictionary to store each student’s marks and identifies the topper using simple calculations and built-in functions.

---

## 🎯 Aim

To maintain a dictionary of students with their marks in five subjects, calculate their **total marks**, store them in a new dictionary, and identify the **student with the highest total (topper)**.

---

## 🧠 Algorithm

1. **Start** the program.
2. Create a dictionary `student_marks`:
   - Keys → Student names.
   - Values → List of marks in five subjects.
3. Initialize an empty dictionary `total_marks`.
4. Loop through `student_marks`:
   - Calculate the total marks using `sum()`.
   - Store the result in `total_marks`.
5. Use `max()` on `total_marks` to find the student with the highest total.
6. Print:
   - The `total_marks` dictionary.
   - The **topper's name and score**.

---

## 💻 PROGRAM:
m1,m2,m3=int(input()),int(input()),int(input()) total=m1+m2+m3; percentage=
(total/300)*100 print("Total marks obtained is {} and the percentage obtained is
{}".format(total,percentage))
## OUTPUT
<img width="771" height="112" alt="image" src="https://github.com/user-attachments/assets/b68551f0-1b9e-4098-8ff2-7716577ed629" />

## RESULT
Thus the program was executed successfully
