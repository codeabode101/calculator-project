# 🧮 **7-Day Calculator Quest**  

## Before You Start
Write down whatever you mess up on in a notebook and write down the solution that worked. If you weren't able to finish, write down a guess.

## **🌱 Day 1: Basic Setup**  
**Goal:** Ask for two numbers and an operator (`+`, `-`, `*`, `/`).  

1. Use `input()` three times to collect:  
   - First number  
   - Operator  
   - Second number  
2. Convert the numbers from strings to a number. 
3. Print all three inputs (e.g., `5 + 3.0`). **Don't** solve yet, just print it.

Extension:
What if you want to write `0.5 + 0.5`? Which type is right to cast to?

---

## **🔥 Day 1.5: Operation Logic**  
**Goal:** Perform calculations based on the operator.  

1. Check the operator and do the operation. **Hint:** use multiple ifs.
2. **You can't divide by 0, ask google why if you don't understand it.** Handle division by zero (print "Error: Can't divide by 0!").  


**Hint:**  
- Add `**` (exponent) and `%` (modulo) as new operators.  
- Don't understand what they mean? **Before Googling**, just add the if statements for these operations and try plugging in random numbers.

---

## **🛡️ Day 2: Input Validation**  
**Goal:** Ensure inputs are valid.  

1. Check if the numbers are *actually numbers* (**Hint:** Google how)
2. Print an error if the operator isn't valid.
3. If invalid, print "Invalid input!" and stop.  
4. Test `operator=4` and other weird code. What does it do?

---

## **♾️ Day 3: Looping & Exiting**  
**Goal:** Let the user keep calculating until they say "quit".  

1. Wrap the calculator in a `while True:` loop. Find out what this does.
2. Ask after each calculation: "Continue? (yes/no)".  
3. Exit the loop if they type "no".  

**Hint:**  
- Google `break` statement.

---


## **🔥 Extra Challenge: Day 4: History Tracking**  
**Goal:** Save the last 5 calculations using variables.  

This problem is challenging! Highly suggest you draw the flow of the code on paper first. 

1. Create 5 variables:  
   ```python  
   hist1 = ""  
   hist2 = ""  
   hist3 = ""  
   hist4 = ""  
   hist5 = ""  
   ```  
2. After each calculation, update the history:  
   - Shift old entries (e.g., `hist5 = hist4`, `hist4 = hist3`, ...)  
   - Save the newest to `hist1`: `"5.0 + 3.0 = 8.0"`  
3. Print all 5 entries after each calculation.  

**Debug Challenge:**  
- What happens if you do `hist5 = hist4` *after* updating `hist1`?  
