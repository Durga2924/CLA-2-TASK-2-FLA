 # Finite Automata for Real-Time Validation

## Student Details
- **Name:** Dande Durga Prasad
- **Register Number:** RA2411026050066
- **Course:** 21CSC301T – Formal Language and Automata
- **Institution:** SRM Institute of Science and Technology, Tiruchirappalli

## 1. Project Overview
This project demonstrates the use of Finite Automata in real-time validation systems using Python.

## 2. Applications Implemented

### 2.1 ATM PIN Validation
Validates whether an ATM PIN contains exactly four digits using a Deterministic Finite Automaton (DFA).

**Example:**
- 4821 – Accepted
- 123 – Rejected

### 2.2 ATM Card Lock System
The system locks the ATM card after three consecutive incorrect PIN attempts.

**Example:**
- WWW – Card Locked
- WWC – Card remains unlocked and the wrong-attempt count resets.

### 2.3 Password Validation
Checks the following password requirements:
- Minimum 8 and maximum 16 characters.
- At least one uppercase letter.
- At least one lowercase letter.
- At least one digit.
- At least one special character.

**Example:**
- Srm@2026 – Accepted
- srm@2026 – Rejected

### 2.4 Email Validation
Validates email formats using finite automata-based rules.

**Example:**
- student@gmail.com – Accepted
- student@@gmail.com – Rejected

## 3. Automata Diagrams

### ATM PIN Validation DFA
![ATM PIN DFA](images/atm_pin_dfa.png)

### ATM Card Lock DFA
![Card Lock DFA](images/card_lock_dfa.png)

### Password Validation
![Password DFA](images/password_dfa.png)

### Email Validation
![Email DFA](images/email_dfa.png)

## 4. Test Results

The following are example test cases. Final results should be updated using the actual Google Colab execution output.

| Application | Input | Expected Result |
|---|---|---|
| ATM PIN | 4821 | Accepted |
| ATM PIN | 123 | Rejected |
| Card Lock | WWW | Locked |
| Password | Srm@2026 | Accepted |
| Password | srm@2026 | Rejected |
| Email | student@gmail.com | Accepted |
| Email | student@@gmail.com | Rejected |

### Execution Screenshot
![Execution Results](images/test_results.png)

## 5. Technologies Used
- Python
- Google Colab
- Finite Automata
- DFA and State Transitions

## 6. Conclusion
This project demonstrates how finite automata can be applied to real-time validation problems such as ATM PIN checking, card locking, password validation and email format checking.

## 7. Project Notebook
The complete Python implementation is available in `Task2_Finite_Automata.ipynb`.
