
**Cartesian Product:**
$$A \times B = \{(a,b) \mid a \in A \text{ and } b \in B\}$$

**Cartesian Product example:**
$$A = \{a,b\},\; B = \{1,2,3\}$$
$$A \times B = \{(a,1),(a,2),(a,3),(b,1),(b,2),(b,3)\}$$

**Principle of Inclusion & Exclusion (two sets):**
$$|A \cup B| = |A| + |B| - |A \cap B|$$

**Principle of Inclusion & Exclusion (three sets):**
$$|A \cup B \cup C| = |A|+|B|+|C| - (|A \cap B|+|A \cap C|+|B \cap C|) + |A \cap B \cap C|$$

**Worked example:**
$$|A \cup B| = 3 + 4 - 1 = 6 \qquad B - A = \{3\} \qquad \bar{B} = \{1,2\}$$

**Equal set exercise expressions:**
$$A \cup \emptyset \qquad A \cup \bar{A} \qquad A \cap \emptyset \qquad A - \bar{A} \qquad A \cap \bar{A} \qquad A \cup \Omega \qquad A \cap \Omega$$

**Set Identities:**

1. Commutative:
$$A \cap B = B \cap A \qquad A \cup B = B \cup A$$

2. Associative:
$$(A \cap B) \cap C = A \cap (B \cap C) \qquad (A \cup B) \cup C = A \cup (B \cup C)$$

3. Distributive:
$$A \cup (B \cap C) = (A \cup B) \cap (A \cup C) \qquad A \cap (B \cup C) = (A \cap B) \cup (A \cap C)$$

4. Identity with Ω:
$$A \cap \Omega = A \qquad A \cup \Omega = \Omega$$

5. Double Complement:
$$(A^c)^c = A$$

6. Idempotent:
$$A \cap A = A \qquad A \cup A = A$$

7. Set Difference (alternate):
$$A - B = A \cap B^c$$

8. De Morgan's Laws:
$$(A \cup B)^c = A^c \cap B^c \qquad (A \cap B)^c = A^c \cup B^c$$

9. Absorption:
$$A \cup (A \cap B) = A \qquad A \cap (A \cup B) = A$$

---

## L2 · Functions — All Equations

**Function notation:**
$$f : A \rightarrow B \qquad f(a) = b$$

**Range:**
$$\text{Range} = \{f(a) \mid a \in A\}$$

**Example — codomain:**
$$\text{Codomain} = \{x \in \mathbb{Z}^+ \mid x < 100\}$$

**Equality of functions:**
$$f = g \iff \forall x \in A,\; f(x) = g(x)$$

**Injective (one-to-one):**
$$f(a) = f(b) \implies a = b$$

**Surjective (onto):**
$$\forall b \in B,\; \exists a \in A : f(a) = b$$

**Many-to-one:**
$$a_1 \neq a_2 \text{ and } f(a_1) = f(a_2)$$

**Inverse function:**
$$f^{-1}(b) = a \quad \text{where } f(a) = b$$

**Finding inverse — example:** $f(x) = 2x + 3 : \mathbb{R} \rightarrow \mathbb{R}$
$$y = 2x + 3 \implies x = \frac{y-3}{2} \implies f^{-1}(x) = \frac{x-3}{2}$$

**Composition of functions:**
$$(f \circ g)(a) = f(g(a))$$

**Composition example:** $f(x) = 2x+3$, $g(x) = 3x+2$
$$(f \circ g)(x) = f(g(x)) = f(3x+2) = 2(3x+2)+3 = 6x+7$$
$$(g \circ f)(x) = g(f(x)) = g(2x+3) = 3(2x+3)+2 = 6x+11$$

---

## L3 · Sequences — All Equations

**Sequence examples:**
$$a_n = 3n \implies 3, 6, 9, 12, \ldots$$
$$b_n = 2^n \implies 2, 4, 8, 16, 32, \ldots$$

**Arithmetic sequence:**
$$a_n = 3n$$

**Geometric sequence:**
$$b_n = 2^n$$

**Sigma (Summation) notation:**
$$\sum_{j=m}^{n} a_j = a_m + a_{m+1} + a_{m+2} + \cdots + a_n$$

**Practice expansions:**
$$\sum_{i=0}^{3} i \qquad \sum_{i=1}^{4}(i^2+3) \qquad \sum_{i=1}^{3} 4$$

**Product (Pi) notation:**
$$\prod_{i=m}^{n} a_i = a_m \cdot a_{m+1} \cdot a_{m+2} \cdots a_n$$

**Product examples:**
$$\prod_{i=1}^{4} i = 1 \cdot 2 \cdot 3 \cdot 4 = 24$$
$$\prod_{k=1}^{3}(k+1) = 2 \cdot 3 \cdot 4 = 24$$

**Empty product:**
$$\text{If } m > n, \text{ then } \prod_{i=m}^{n} a_i = 1$$

**Factorial:**
$$n! = n(n-1)(n-2)\cdots(2)(1)$$
$$0! = 1$$

**Factorial exercises:**
$$5! \qquad 7! \qquad \frac{n!}{(n-2)!}$$

---

That's every single equation from Lectures 1–3, including every image-embedded formula from the slides.
## L4 · Counting I

**Sum Rule**
$$n_1 + n_2 + n_3 + \cdots + n_k$$

**Product Rule**
$$n_1 \times n_2 \times n_3 \times \cdots \times n_k$$

**Subtraction Rule (Inclusion-Exclusion)**
$$|n_1 \cup n_2| = |n_1| + |n_2| - |n_1 \cap n_2|$$

**Division Rule**
$$\text{Distinct outcomes} = \frac{n}{d}$$

**Pigeonhole Principle (Generalized)**
$$\text{At least } \lceil n/k \rceil \text{ objects in one box, given } n \text{ objects into } k \text{ boxes}$$

**Permutation without Repetition (arrange all n):** 
 $$---P(n, r) = n \times (n-1) \times (n-2) \times \cdots \times 1 = n!$$

**Permutation without Repetition (choose r from n):**
$$---P(n, r) = \frac{n!}{(n-r)!}$$

**Permutation with Repetition:**
$$---P(n, r) = n^r$$

**Permutation with Indistinguishable Objects:**
$$---P = \frac{n!}{n_1! \times n_2! \times \cdots \times n_k!}$$
## L5 · Counting II

**Combination without Repetition:**
$$C(n, r) = \binom{n}{r} = \frac{n!}{r! \times (n-r)!}$$

**Combination with Repetition:**
$$\binom{n+r-1}{r} = \binom{n+r-1}{n-1} = \frac{(n+r-1)!}{r!\,(n-1)!}$$

**Binomial Theorem:**
$$(x + y)^n = \sum_{j=0}^{n} \binom{n}{j} x^{n-j} y^j$$

$$= \binom{n}{0}x^n y^0 + \binom{n}{1}x^{n-1}y^1 + \cdots + \binom{n}{n-1}x^1 y^{n-1} + \binom{n}{n}x^0 y^n$$

**Same example using Binomial Theorem:**
$$(x+y)^3 = \sum_{j=0}^{3}\binom{3}{j}x^{3-j}y^j = \binom{3}{0}x^3y^0 + \binom{3}{1}x^2y^1 + \binom{3}{2}x^1y^2 + \binom{3}{3}x^0y^3 = x^3+3x^2y+3xy^2+y^3$$

**Pascal's Identity** (let n and k be positive integers with n ≥ k):
$$\binom{n+1}{k} = \binom{n}{k-1} + \binom{n}{k}$$

**Pascal's Triangle Row 8:**
$$1 \quad 8 \quad 28 \quad 56 \quad 70 \quad 56 \quad 28 \quad 8 \quad 1$$

---

## L6 · Recursion

**Recursive function definition — Example 1:**
$$f(0) = 3, \quad f(n+1) = 2f(n) + 3$$
$$f(1) = 9, \quad f(2) = 21, \quad f(3) = 45, \quad f(4) = 93$$

**Recursive factorial definition:**
$$f(0) = 1, \quad f(n+1) = (n+1) \cdot f(n)$$

**Recursive summation definition:**
$$\sum_{k=0}^{0} a_k = a_0$$
$$\sum_{k=0}^{n+1} a_k = \left(\sum_{k=0}^{n} a_k\right) + a_{n+1}$$

**Recursive product definition:**
$$\prod_{k=0}^{0} a_k = a_0$$
$$\prod_{k=0}^{n+1} a_k = \left(\prod_{k=0}^{n} a_k\right) \times a_{n+1}$$

**Fibonacci Numbers:**
$$f_0 = 0, \quad f_1 = 1, \quad f_n = f_{n-1} + f_{n-2}$$
$$f_2 = 1,\quad f_3 = 2,\quad f_4 = 3,\quad f_5 = 5$$

**Recursive Factorial Algorithm:**
$$\text{if } n=0: \text{return } 1 \qquad \text{else: return } n \cdot \text{factorial}(n-1)$$

**Recursive Power Algorithm (aⁿ):**
$$\text{if } n=0: \text{return } 1 \qquad \text{else: return } a \cdot \text{power}(a,\, n-1)$$

**GCD Recursive Reduction:**
$$\gcd(a, b) = \gcd(b \bmod a,\; a)$$
$$\gcd(0, b) = b \quad \text{(base case, } b > 0\text{)}$$

**Binary Search mid-index:**
$$m = \left\lfloor \frac{i+j}{2} \right\rfloor$$

---

## L7 · Mathematical Induction

**Inductive step statement:**
$$P(k) \rightarrow P(k+1)$$

**Claim — Sum of first n integers:**
$$\sum_{i=1}^{n} i = \frac{n(n+1)}{2}$$

**Basis step (P(1)):**
$$\frac{1(1+1)}{2} = 1$$

**Inductive hypothesis:**
$$\sum_{i=1}^{K} i = \frac{K(K+1)}{2}$$

**Inductive step proof chain:**
$$1 + 2 + \cdots + k + (k+1) = \frac{k(k+1)}{2} + (k+1) = \frac{k(k+1) + 2(k+1)}{2} = \frac{(k+1)(k+2)}{2}$$

**Claim — Sum of first n odd integers:**
$$1 + 3 + 5 + \cdots + (2n-1) = n^2$$

**Inductive hypothesis:**
$$1 + 3 + 5 + \cdots + (2k-1) = k^2$$

**Inductive step:**
$$1+3+5+\cdots+(2k-1)+(2k+1) = \bigl[1+3+\cdots+(2k-1)\bigr]+(2k+1) = k^2+(2k+1) = k^2+2k+1 = (k+1)^2$$

**Claim — Inequality 1:**
$$n < 2^n \quad \text{for all positive integers } n$$

**Basis step:** $1 < 2^1 = 2$

**Inductive step:**
$$k+1 < 2^k + 1 \leq 2^k + 2^k = 2 \cdot 2^k = 2^{k+1}$$

**Claim — Inequality 2:**
$$2^n < n! \quad \text{for every integer } n \geq 4$$

**Basis step:** $2^4 = 16 < 4! = 24$

**Inductive step:**
$$2^{k+1} = 2 \cdot 2^k < 2 \cdot k! < (k+1) \cdot k! = (k+1)!$$

**Claim — Divisibility:**
$$3 \mid (n^3 - n) \quad \text{for every positive integer } n$$

**Basis step:** $1^3 - 1 = 0$, and $3 \mid 0$

**Inductive step expansion:**
$$(k+1)^3 - (k+1) = k^3 + 3k^2 + 3k + 1 - k - 1 = (k^3 - k) + 3k^2 + 3k = (k^3-k) + 3(k^2+k)$$

**Tiling — Checkerboard sizes:**
$$2^k \times 2^k \quad \longrightarrow \quad 2^{k+1} \times 2^{k+1}$$

---

That's every single equation that appears in Lectures 4–7, including all the ones that were embedded as images in the slides.
