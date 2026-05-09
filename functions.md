# 📐 Function Notations and Symbols Cheat Sheet

The concept of a "function" is foundational to mathematics. The symbols and notations used define the rules, inputs, outputs, and relationships between mathematical objects. This guide provides a comprehensive reference for all essential function notations.

***

## I. Notation for Function Application (How to write $f(x)$)

These notations indicate that a specific rule (the function) is being applied to an input variable.

| Notation | Name | Meaning / Usage | Example |
| :---: | :--- | :--- | :---: |
| $\mathbf{f(x)}$ | Function $f$ of $x$ | The most common form. Represents the output when the input is $x$. | If $f(x) = 2x + 1$, then $f(3) = 7$. |
| $\mathbf{g(t)}$ | Function $g$ of $t$ | Using a different function name ($g$) and input variable ($t$). | $g(\text{time}) = \text{distance}$ |
| $\mathbf{h(y)}$ | Function $h$ of $y$ | Common when the independent variable is $y$. | |
| $\mathbf{y = f(x)}$ | Equation Form | Explicitly defines the relationship: $y$ is a function of $x$. | $y = \cos(x)$ |
| $\mathbf{x = f(y)}$ | Inverse/Dependent Form | Defines the relationship where $x$ is dependent on $y$ (used when $y$ is the primary independent variable). | $x = 3y - 5$ (meaning $x$ is a function of $y$) |

## II. Notation for Domain and Range (The Inputs and Outputs)

This section defines the scope of the function—what inputs are allowed (Domain) and what outputs are produced (Range).

### A. Set Notation (The Formal Definition)

Set-builder notation defines the function's overall mapping.

*   **$f: A \to B$**
    *   **Meaning:** "Function $f$ maps from set $A$ to set $B$."
    *   **$A$ (The Domain):** The set of all possible input values.
    *   **$B$ (The Codomain):** The set where all the output values *must* belong.
    *   **Example:** $f: \mathbb{R} \to \mathbb{R}$ (Function $f$ maps from Real Numbers to Real Numbers).
*   **$f: A \to B$** where $\text{Range}(f) \subseteq B$
    *   This explicitly states that the **Range** is a subset of the **Codomain**.

### B. Listing Specific Sets (Function Properties)

| Symbol | Name | Description | Example |
| :---: | :--- | :--- | :---: |
| $\mathbf{\text{Dom}(f)}$ | Domain of $f$ | The set of all valid inputs for $f$. | $\text{Dom}(f) = \{x | x \neq 0\}$ |
| $\mathbf{\text{Ran}(f)}$ | Range of $f$ | The set of all actual outputs produced by $f$. | $\text{Ran}(f) = [5, \infty)$ |
| $\mathbf{D_f}$ | Domain of $f$ (Alt.) | An alternative, compact symbol for Domain. | |

### C. Standard Set Symbols (The elements of the Domain/Codomain)

These symbols represent the specific types of numbers allowed in the Domain or Codomain.

| Symbol | Name | Meaning | Example |
| :---: | :--- | :--- | :---: |
| $\mathbf{\mathbb{N}}$ | Natural Numbers | Counting numbers: $\{1, 2, 3, \dots\}$ | $7 \in \mathbb{N}$ |
| $\mathbf{\mathbb{Z}}$ | Integers | All whole numbers (positive, negative, zero). | $-5 \in \mathbb{Z}$ |
| $\mathbf{\mathbb{Q}}$ | Rational Numbers | Numbers expressible as $\frac{p}{q}$. | $0.75 = \frac{3}{4} \in \mathbb{Q}$ |
| $\mathbf{\mathbb{R}}$ | Real Numbers | All rational and irrational numbers. | $\pi \in \mathbb{R}$ |
| $\mathbf{\mathbb{C}}$ | Complex Numbers | Numbers of the form $a + bi$. | $2 + 3i \in \mathbb{C}$ |

***

## III. Notation for Specific Function Types

These notations describe special mathematical relationships, behaviors, or structures within the function.

### 1. Inverse Function (Reversing the mapping)

| Notation | Name | Meaning / Usage | Example |
| :---: | :--- | :--- | :---: |
| $\mathbf{f^{-1}(x)}$ | Inverse of $f$ | The function that "undoes" $f$. If $f(a) = b$, then $f^{-1}(b) = a$. | If $f(x) = 2x + 1$, then $f^{-1}(x) = \frac{x-1}{2}$. |

### 2. Composite Function (Function within a Function)

| Notation | Name | Meaning / Usage | Example |
| :---: | :--- | :--- | :---: |
| $\mathbf{(f \circ g)(x)}$ | $f$ composed with $g$ of $x$ | Means applying $g$ first, then $f$: $\mathbf{f(g(x))}$. | $(f \circ g)(x) = (x+1)^2$ |
| $\mathbf{g \circ f}$ | $g$ composed with $f$ | Means applying $f$ first, then $g$: $\mathbf{g(f(x))}$. | $(g \circ f)(x) = x^2 + 1$ |

### 3. Other Special Types

| Notation | Meaning | Context / Usage | Example |
| :---: | :--- | :--- | :---: |
| $\mathbf{f(x) \to y}$ | Mapping arrow | Shows a specific input $x$ maps to output $y$. | $f(4) \to 10$ |
| $\mathbf{f(x) = x}$ | Identity Function | A function that maps every input to itself. | $f(x) = x$ |
| $\mathbf{f(x) = c}$ | Constant Function | Output is always a fixed value $c$, regardless of the input. | $f(x) = 5$ |
| $\mathbf{f(x) = mx + b}$ | Linear Function | Represents a straight line relationship. | $f(x) = 2x - 3$ |

***

## 📝 Summary Table Cheat Sheet

| Concept | Notation | How it is Read | Primary Purpose |
| :---: | :---: | :---: | :--- |
| **Application** | $f(x)$ | "f of x" | The value of the function for a given input $x$. |
| **Definition** | $f: A \to B$ | "$f$ maps from $A$ to $B$" | Defines the overall scope (Domain $A$, Codomain $B$). |
| **Domain** | $\text{Dom}(f)$ | "Domain of $f$" | Set of all allowed inputs. |
| **Range** | $\text{Ran}(f)$ | "Range of $f$" | Set of all actual outputs. |
| **Inverse** | $f^{-1}(x)$ | "Inverse of $f$ of $x$" | Undoes the function $f$. |
| **Composition** | $(f \circ g)(x)$ | "$f$ composed with $g$ of $x$" | Applies $g$, then applies $f$. |
| **Identity** | $f(x) = x$ | $f$ equals $x$ | Output always equals input. |
