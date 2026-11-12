# Finite Automata for Real-Time Validation

## 📌 Project Overview

This project demonstrates the practical application of **Deterministic Finite Automata (DFA)** for real-time input validation using Python.

Finite Automata are used to check whether user inputs follow predefined rules. This project implements three real-world validation systems: password verification, email format validation, and ATM PIN verification.

## 🎯 Objectives

- Understand the working principles of Deterministic Finite Automata.
- Implement DFA-based input validation using Python.
- Apply automata concepts to real-world applications.
- Test valid and invalid input strings.
- Analyze accepted and rejected inputs.

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- Matplotlib

## 🔍 Applications Implemented

### 1. Password Verification System

Validates passwords based on the following conditions:

- Minimum length of 8 characters.
- At least one uppercase letter (A–Z).
- At least one lowercase letter (a–z).
- At least one digit (0–9).
- Whitespace characters are not allowed.

The DFA tracks password length and the presence of required character categories.

### 2. Email Format Validator

Validates email addresses using a simplified email format.

Rules:
- Must contain a local part.
- Must contain exactly one `@` symbol.
- Must contain a valid domain name.
- Must contain a dot (`.`) before the top-level domain.
- The top-level domain must contain at least two alphabetic characters.

### 3. ATM PIN Verification

Validates ATM PIN inputs using a DFA.

Rules:
- PIN must contain exactly four digits.
- Only numeric characters (0–9) are accepted.
- Non-numeric characters are rejected.
- Additional characters are not allowed.

## ⚙️ DFA Implementation

Each application uses states and transitions to process input strings character by character.

| Application | Validation Method |
|---|---|
| Password | Length and character tracking |
| Email | Character and separator validation |
| ATM PIN | Four-state digit counting |

Invalid inputs transition to a rejecting state.

## 🧪 Testing and Results

The project includes a combined test runner that evaluates valid and invalid inputs.

| Application | Test Cases |
|---|---:|
| Password Verification | 11 |
| Email Validation | 11 |
| ATM PIN Verification | 10 |
| **Total** | **32** |

**Expected Verification Result:**
- Total Tests: 32
- Passed: 32
- Failed: 0
- Status: ALL TESTS PASSED

## 🚀 How to Run the Project

1. Download or clone this repository.
2. Open the `.ipynb` notebook in Google Colab.
3. Select **Runtime → Run all**.
4. Observe the validation results and test summary.

No external dataset is required.

## 📂 Project Structure

```text
Finite-Automata-Real-Time-Validation/
│
├── Task_2_Finite_Automata.ipynb
└── README.md
```

## 📚 Learning Outcomes

- Understanding Deterministic Finite Automata.
- Designing DFA-based validation systems.
- Implementing state transitions using Python.
- Understanding accepting and rejecting states.
- Applying Formal Language and Automata concepts to practical applications.

## ⚠️ Limitations

This project performs syntax validation only.

- Password verification does not check password strength or breached-password databases.
- Email validation does not verify whether a mailbox actually exists.
- ATM PIN validation does not authenticate against an actual bank account.

Additional application logic is required for these operations.

## 👨‍💻 Academic Information

**Course:** 21CSC301T – Formal Language and Automata

**Assessment:** CLA-2 – Task 2

**Institution:** SRM Institute of Science and Technology, Tiruchirappalli

---

*Developed as part of the Formal Language and Automata coursework.*
