# UiPath Control Flow – Break and Continue Example

## 📌 Project Overview
This project demonstrates how to use **Break** and **Continue** activities inside a loop in UiPath.
It helps beginners understand how to control loop execution flow effectively.

---

## 🎯 Objective
- Learn how **Break** stops a loop completely
- Learn how **Continue** skips the current iteration
- Understand real-world use cases of loop control

---

## 🧩 Workflow Description
1. An integer array `numbers` is created with values:
2. A **For Each** loop iterates through the array.
3. Inside the loop:
- If the current number equals `30`, the **Break** activity is executed.
- Otherwise, a message box displays the current number.
4. Once Break is executed, the loop stops immediately.

(Alternate scenario can be created using **Continue** to skip a value.)

---

## 🛠️ Tools & Technologies
- UiPath Studio
- For Each Loop
- If Condition
- Break Activity
- Continue Activity
- Message Box

---

## 📂 Variables Used
| Variable Name | Type     | Description                     |
|--------------|----------|---------------------------------|
| numbers      | Int32[]  | Collection for loop iteration   |
| currentNumber | Int32   | Current loop item               |

---

## ▶️ Expected Output (Break Example)
