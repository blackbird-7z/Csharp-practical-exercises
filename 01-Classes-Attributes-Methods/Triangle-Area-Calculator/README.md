# Exercise 01: Triangle Area Calculation


## 📝 Problem Statement

Write a program to read the side measurements of two triangles, **X** and **Y** (assume valid measurements). Then, display the area of both triangles and identify which one has the larger area.

### 📐 Mathematical Foundation
The formula used to calculate the area based on the sides $a, b, c$ is **Heron's Formula**:

$$Area = \sqrt{s(s-a)(s-b)(s-c)}$$

Where the semi-perimeter $s$ is:

$$s = \frac{a+b+c}{2}$$

---

## 💻 Console Output Example

Below is a simulation of the execution. The values highlighted in <font color="red">**red**</font> indicate the inputs entered by the user in the console:

```diff
  Enter the measurements of triangle X:
- 3.00
- 4.00
- 5.00
  Enter the measurements of triangle Y:
- 7.50
- 4.50
- 4.02

  Triangle X area = 6.0000
  Triangle Y area = 7.5638
  Larger area: Y
  ```
  ```text
Enter the measurements of triangle X:
> 3.00
> 4.00
> 5.00
Enter the measurements of triangle Y:
> 7.50
> 4.50
> 4.02

Triangle X area = 6.0000
Triangle Y area = 7.5638
Larger area: Y
```
---



## 🛠️ Technologies and Concepts
* **Language:** C#
* **Encapsulation:** The calculation logic was delegated to an `Area()` method within the `Triangle` class.
* **IO:** Data input and output via Console.
* **Formatting:** Use of `CultureInfo.InvariantCulture` to handle decimal points (dot instead of comma).

---
[⬅ Back to Chapter 01](../README.md)