# 🧮 Phase 3A: Binary Operators (The Conversion Tools)

This section covers the fundamental actions that require **two** input numbers (A and B). These operators are the core mechanics that convert your input energy into a new, transformed energy state (the output).

| Symbol | Name | Description | Example (Input 5, 3) |
| :---: | :--- | :--- | :---: |
| $+$ | **Addition** | The operation of finding the sum of two values. | $5 + 3 = 8$ |
| $-$ | **Subtraction** | The operation of finding the difference between two values. | $5 - 3 = 2$ |
| $\times$ or $\cdot$ | **Multiplication** | The operation of finding the product of two values. | $5 \cdot 3 = 15$ |
| $\div$ or $/$ | **Division** | The operation of finding the quotient of two values. | $5 / 3 \approx 1.66...$ |
| $\wedge$ or $x^y$ | **Exponentiation** | Raising a base ($x$) to a power ($y$). | $5^3 = 125$ |
| $\sum$ | **Summation** | Adds up a sequence of numbers, defined by limits. | $\sum_{i=1}^{3} i = 1+2+3 = 6$ |
| $\int$ | **Integral** | Calculates the cumulative area under a function's curve (Antiderivative). | $\int_{0}^{1} x \, dx = 0.5$ |

# 🧮 Phase 3B: Unary Operators (The Conversion Tools)

This section covers operators that require only **one** input number ($x$). These operators transform the input state directly, changing its magnitude, sign, or logarithmic/root value. They are the specialized internal processors of the mathematical machine.

| Symbol | Name | Description | Example (Input -7) |
| :---: | :--- | :--- | :---: |
| $|x|$ | **Absolute Value** | Measures the distance of a number from zero (always non-negative). | $|-7| = 7$ |
| $-x$ | **Negation** | Reverses the sign of a number. | $-(7) = -7$ |
| $\ln(x)$ | **Natural Logarithm** | The exponent to which the mathematical constant $e$ must be raised to equal $x$. | $\ln(e^2) = 2$ |
| $\log_b(x)$ | **Logarithm (Base $b$)** | The exponent to which a specific base ($b$) must be raised to equal $x$. | $\log_{10}(100) = 2$ |
| $\sqrt[n]{x}$ | **Nth Root** | The number that, when raised to the power $n$, equals $x$. (If $n=2$, it is the square root). | $\sqrt[3]{8} = 2$ |
| $\frac{d}{dx}$ | **Derivative** | Measures the instantaneous rate of change of a function $f(x)$ with respect to $x$. | $\frac{d}{dx}(x^2) = 2x$ |

# ✅ Unary Operators Check: The Internal Processors

**Goal:** To ensure you understand not just *what* the operator does, but *how* it affects the number and *why* it works. We are testing your ability to perform the "internal processing" of the mathematical machine.

---

## ⚛️ 1. Absolute Value: $|x|$
*(The operator that measures the raw magnitude or distance from zero.)*

| Concept | Description | Key Property | Pitfall to Avoid |
| :---: | :--- | :--- | :---: |
| **Action** | Returns the non-negative distance of $x$ from the origin. | $|-x| = |x|$ | **Mistake:** Assuming $|x| = x^2$. (e.g., $|-2| = 2$, not 4). |
| **Domain** | All Real Numbers ($\mathbb{R}$). | $|x| \ge 0$ (The output is always zero or positive). | **Mistake:** Forgetting that $|-5|$ is **not** $-5$. |
| **Advanced Link** | **Inequalities:** Defines intervals. $|x| < a$ means $-a < x < a$. | $|x| \ge a$ means $x \le -a$ **OR** $x \ge a$. |

---

## ⚡ 2. Negation: $-x$
*(The operator that reverses the state or sign of the number.)*

| Concept | Description | Key Property | Pitfall to Avoid |
| :---: | :--- | :--- | :---: |
| **Action** | Multiplies $x$ by $-1$. Flips the number across the $x$-axis. | $-(-x) = x$ | **Mistake:** Confusing negation with subtraction. ($5 - (-3)$ is **$+8$**, not $-2$). |
| **Domain** | All Real Numbers ($\mathbb{R}$). | $-(-x) = x$ | **Mistake:** Incorrectly applying it to fractions (e.g., $-1/3$ is $\frac{-1}{3}$). |
| **Advanced Link** | **Function:** This is the simplest linear function: $f(x) = -x$. | $-x = -1 \cdot x$ |

---

## 📈 3. Natural Logarithm: $\ln(x)$
*(The operator that asks: "To what power must $e$ be raised to get $x$?")*

| Concept | Description | Key Property | Pitfall to Avoid |
| :---: | :--- | :--- | :---: |
| **Action** | Converts a multiplicative growth rate into an additive measure. | $\ln(e) = 1$ (Since $e^1 = e$) | **Mistake:** Assuming $\ln(x)$ is always smaller than $x$. (e.g., $\ln(0.5) \approx -0.69$, which is smaller than $0.5$). |
| **Domain** | $x > 0$ (The input must be a positive number). | $\ln(1) = 0$ (Since $e^0 = 1$) | **Mistake:** Taking $\ln(0)$ (approaches $-\infty$) or $\ln(\text{negative})$. |
| **Advanced Link** | **Decay/Growth:** Governs continuous compounding: $A = P e^{rt}$. | $\ln(A/P) = rt$ |

---

## 📊 4. Logarithm: $\log_b(x)$
*(The operator that asks: "To what power must $b$ be raised to get $x$?")*

| Concept | Description | Key Property | Pitfall to Avoid |
| :---: | :--- | :--- | :---: |
| **Action** | Measures the exponent required relative to a specified base ($b$). | $\log_b(b) = 1$ (Since $b^1 = b$) | **Mistake:** Confusing the roles of $b$ (Base) and $x$ (Argument). |
| **Domain** | $x > 0$ (The input must be positive). | $\log_b(1) = 0$ | **Mistake:** Assuming $\log_b(b^2) = 2b$ (it is simply **2**). |
| **Advanced Link** | **Scale Measurement:** Used to compress huge ranges. (Richter Scale $\log_{10}$, pH Scale $\log_{0.1}$). | $\log_b(x^n) = n \cdot \log_b(x)$ |

---

## 📏 5. Nth Root: $\sqrt[n]{x}$
*(The operator that asks: "What number, multiplied by itself $n$ times, equals $x$?")*

| Concept | Description | Key Property | Pitfall to Avoid |
| :---: | :--- | :--- | :---: |
| **Action** | Finds the number $y$ such that $y^n = x$. | $\sqrt[n]{x} = x^{1/n}$ | **Mistake:** Forgetting that the $n$-th root can be negative (e.g., $\sqrt[3]{-8} = -2$). |
| **Domain** | **Even $n$**: $x \ge 0$. **Odd $n$**: $x$ can be any Real Number. | $\sqrt{x} = x^{1/2}$ | **Mistake:** When $n=2$, don't automatically assume $x$ must be positive. |
| **Advanced Link** | **Generalization:** Allows powers to be expressed as roots. | $\sqrt[n]{x^m} = x^{m/n}$ |

---

## ⚙️ 6. Derivative: $\frac{d}{dx}$
*(The operator that measures the instantaneous slope or rate of change.)*

| Concept | Description | Key Property | Pitfall to Avoid |
| :---: | :--- | :--- | :---: |
| **Action** | Determines the slope of the tangent line to the curve at any point $x$. | $\frac{d}{dx}(c) = 0$ (The slope of a flat line is zero). | **Mistake:** Confusing the Derivative with the function's value. ($f(5)=25$, but $f'(5)=10$). |
| **Domain** | Usually all Real Numbers ($\mathbb{R}$), provided the function is smooth. | $\frac{d}{dx}(x^n) = nx^{n-1}$ | **Mistake:** Forgetting the Chain Rule when differentiating composite functions, like $f(x^2) = (x^2)^2$. |
| **Advanced Link** | **Optimization:** Used to find maxima and minima (the highest and lowest points of a function). | Set $\frac{d}{dx} f(x) = 0$ to find critical points. |

***
*(You are now fully checked on the core mechanisms of the math machine! Ready for Phase 3C: Relational Symbols!)*


