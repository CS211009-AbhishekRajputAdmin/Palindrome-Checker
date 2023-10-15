## Description:
 Write a Python program to determine if a given number is an Armstrong number or not.  An Armstrong number is a special kind of number where the sum of its individual digits, each raised to a certain power, is equal to the number itself. In simpler terms:

Take a number (for example, 153).
Break it down into its individual digits (1, 5, and 3).
Raise each digit to a certain power (usually to the power of the number of digits, which is 3 in this case).
Add up these results.
If the sum is the same as the original number (153), it's an Armstrong number.
So, in the case of 153, you would calculate: 1^3 + 5^3 + 3^3 = 1 + 125 + 27 = 153. Since the sum is equal to the original number, 153 is an Armstrong number.

### Input:
- An integer `num` (1 ≤ num ≤ 10^6) to be checked for being an Armstrong number.

### Constraints:
- The input integer `num` will have at most 6 digits.

### Output:
- Print "Yes" if the number is an Armstrong number; otherwise, print "No."

**Examples:**
```
Input:
153

Output:
Yes

Explanation:
153 is an Armstrong number because 1^3 + 5^3 + 3^3 = 153.

---

Input:
370

Output:
Yes

Explanation:
370 is an Armstrong number because 3^3 + 7^3 + 0^3 = 370.

---

Input:
123

Output:
No

Explanation:
123 is not an Armstrong number because 1^3 + 2^3 + 3^3 ≠ 123.
```
