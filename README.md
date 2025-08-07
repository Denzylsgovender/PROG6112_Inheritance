# 💻 Activity: Safe Withdrawals – A Banking Scenario with Inheritance

Welcome to your hands-on Java coding challenge! In this activity, you’ll simulate a **basic Online Banking System** using **inheritance** and **method overriding**.

---

## 🧠 Learning Objectives

- Override superclass methods.
- Call constructors during inheritance.
- Access superclass methods using `super`.
- Use conditional logic to enforce rules in subclasses.

---

## 🏗️ Classes You'll Create

1. **`BankAccount`** (Superclass)
2. **`SavingsAccount`** (Subclass – inherits from `BankAccount`)

---

## 🎯 Your Task

### 🔹 Step 1: Create the Superclass `BankAccount`

- Create a class called `BankAccount`.
- Add a constructor to initialize the account balance.
- Add a method called `withdraw(double amount)` that simply prints:



---

### 🔹 Step 2: Create the Subclass `SavingsAccount`

- Create a subclass `SavingsAccount` that extends `BankAccount`.
- Add a constructor that uses `super(...)` to call the superclass constructor.
- Override the `withdraw` method to add a **minimum balance rule**.

In this method:
- Prompt the user for:
- Amount they wish to withdraw.
- Minimum balance that must remain (e.g., R8500.00).

---

### 🔹 Step 3: Enforce the Rule

- Inside the overridden `withdraw` method:
- Check if `(current balance - withdrawal amount)` is **less than** the minimum balance.
- If **yes**, display:
  ```
  Transaction declined: Minimum balance requirement not met.
  ```
- If **no**, proceed and deduct the amount. Show:
  ```
  Transaction successful. Remaining balance: Rxxxx.xx
  ```

---

## ✅ What You’re Practicing

- Inheritance and class hierarchy
- Method overriding
- Using constructors and `super(...)`
- Conditional logic and user input

---

## 📦 Bonus Tips

- Use `Scanner` for user input.
- Make sure to track the current balance inside the class using a variable.
- Use proper formatting like `System.out.printf()` for currency.

---

## 📘 Example Output

