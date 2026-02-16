## Lab Experiment: Practical Study of While Loops in Python

**Author:** Vedant Trivedi

**PRN:** 25070123121

---

### **Aim**

To implement and analyze the `while` loop construct in Python for handling repetitive tasks, mathematical computations, and sequence generation.

---

### **Theory**

A **while loop** in Python repeatedly executes a target statement as long as a given condition is true. Unlike a `for` loop, which iterates over a predefined sequence, the `while` loop is generally used when the number of iterations is not known beforehand and depends on a dynamic condition.

* **Syntax:**
```python
while condition:
    # code block to be executed

```


* **Condition:** An expression evaluated before each loop iteration. If it evaluates to `True`, the loop body runs.
* **Update:** To avoid an **infinite loop**, the variables within the condition must be updated inside the loop body.
* **Control Statements:** * `break`: Terminates the loop entirely.
* `continue`: Skips the rest of the current iteration and jumps back to the condition check.



---

### **Program Algorithms**

#### **1. Basic Iteration (1 to )**

* **Algorithm:**
1. Initialize a counter variable .
2. While  is less than or equal to the target limit ( or ), print .
3. Increment  by 1 in each step to eventually break the condition.



#### **2. Factorial of a Number**

* **Algorithm:**
1. Input a number .
2. Check if  (undefined) or  (result is 1).
3. For , initialize `fact = 1` and `i = 1`.
4. While , multiply `fact` by  and increment .
5. Output the final value of `fact`.



#### **3. Fibonacci Series (Terms vs. Limit)**

* **Algorithm (Terms):**
1. Initialize  and `count=0`.
2. While `count < n`, print , calculate the next term (), update  to , and update  to the new term.


* **Algorithm (Limit):**
1. While the current value  is less than or equal to the user-defined `limit`, print  and update the values.



#### **4. Reversing a Number & Palindrome Check**

* **Algorithm:**
1. Input a number and store a copy as `original`.
2. Initialize `reversed = 0`.
3. While the number :
* Extract the last digit using modulo: `digit = num % 10`.
* Build the reversed number: `reversed = (reversed * 10) + digit`.
* Remove the last digit: `num //= 10`.


4. Compare `original` with `reversed` to determine if it is a palindrome.



#### **5. Counting Digits**

* **Algorithm:**
1. Input a number and initialize `count = 0`.
2. While the number , increment `count` and perform integer division by 10 (`num //= 10`).
3. Output the final `count`.



#### **6. Searching in a List**

* **Algorithm:**
1. Define a list and input a `search_element`.
2. Initialize `index = 0`.
3. While `index` is less than the length of the list, check if the element at that index matches the input.
4. If found, print the index and use `break` to stop.
5. If the loop finishes without a match, print "not found".



#### **7. Filtering Odd Numbers**

* **Algorithm:**
1. Initialize .
2. While :
* If  is divisible by 2, increment  and use `continue` to skip the print statement.
* Else, print  and increment .





---

### **Conclusion**

This experiment demonstrates the flexibility of the `while` loop in Python. It is effectively used for mathematical sequences like Fibonacci and factorials, as well as data manipulation tasks like reversing numbers and searching lists. The use of `break` and `continue` provided fine-grained control over the loop's execution flow.
