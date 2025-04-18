

# 💰 EMI Calculator (Java)

This is a simple and practical **EMI (Equated Monthly Installment)** calculator built using Java. The application takes **loan amount**, **annual interest rate**, and **loan tenure** as input, then calculates the **monthly EMI**, **total payment**, and **total interest payable**.

---

## 🧮 Formula Used
The EMI is calculated using the standard formula:

```
EMI = [P x R x (1 + R)^N] / [(1 + R)^N - 1]
```
Where:
- **P** = Principal loan amount  
- **R** = Monthly interest rate = Annual interest rate / (12 × 100)  
- **N** = Loan tenure in months

---

## 🚀 Features
- Accepts dynamic input from the user
- Calculates monthly EMI
- Displays total payment (principal + interest)
- Displays total interest payable
- Clean and simple console output

---

## 📂 How to Run the Program
1. Copy the code from `EMICalculator.java`
2. Paste it into any Java IDE (like Eclipse, IntelliJ, or VS Code)
3. Compile and run the program
4. Enter:
   - Loan amount (in USD)
   - Annual interest rate (e.g., 8.5 for 8.5%)
   - Loan tenure in years
5. View the monthly EMI breakdown in the console

---

## 🛠️ Concepts Covered
- User input using `Scanner`
- Arithmetic operations with `double` and `int`
- Loan and finance-based real-world logic
- Power function with `Math.pow()`
- Clean formatted output

---

## 📸 Sample Output
```
Enter loan amount in USD:
10000
Enter annual interest rate (in %):
8
Enter loan tenure in years:
2

--- EMI Calculation Result ---
Monthly EMI: $452.45
Total Payment (Principal + Interest): $10858.83
Total Interest Payable: $858.83
```

---

## 📘 Author
Built by **Shadab Siddiqui** as part of the CloudBerry QA Automation Bootcamp (April 2025)

---

## ✅ Try It, Tweak It, Learn From It!
This program is perfect for beginner and intermediate learners who want to practice:
- Java fundamentals
- Financial logic
- Real-world problem-solving using code

---

