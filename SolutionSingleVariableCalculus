# Comprehensive Calculus of Functions of One Variable

## 1. Functions, Domain, and Range

### 1.1 What is a Function?

A function is a rule that assigns exactly one output value to each input value. Think of a function as a machine: you put in a value (the input), and the machine produces a specific result (the output).

More formally, a function f assigns to each element x in a set X (called the domain) exactly one element y in a set Y (called the range).

We write this as:
- f: X → Y
- y = f(x), where x ∈ X and y ∈ Y

### 1.2 Domain and Range

**Domain**: The set of all possible input values (x-values) for which the function is defined.

**Range**: The set of all possible output values (y-values) that the function can produce.

For many functions, we need to identify where the function is defined. A function might not be defined for all real numbers due to:
- Division by zero
- Square roots of negative numbers
- Logarithms of non-positive numbers
- And other mathematical restrictions

### 1.3 Examples of Functions with Their Domains and Ranges

**Example 1:** f(x) = x² for -1 < x ≤ 1

*Step 1:* Identify the domain from the given constraints
- Domain: -1 < x ≤ 1 (all x values between -1 and 1, including 1 but not -1)

*Step 2:* Determine the range by finding possible output values
- Since f(x) = x², and x² ≥ 0 for all real x
- When x = 0, f(0) = 0
- As x approaches -1 from the right, x² approaches 1
- At x = 1, f(1) = 1
- For all values in between, 0 ≤ x² ≤ 1
- Therefore, Range: 0 ≤ y ≤ 1

**Example 2:** f(x) = 1/(x-2)

*Step 1:* Find where the function is undefined (where the denominator equals zero)
- The function is undefined when x = 2
- Domain: {x | x ∈ ℝ, x ≠ 2} (all real numbers except 2)

*Step 2:* Analyze the range
- As x approaches 2 from the left, f(x) approaches negative infinity
- As x approaches 2 from the right, f(x) approaches positive infinity
- The function never equals 0 (since the numerator is never 0)
- Range: {y | y ∈ ℝ, y ≠ 0} (all real numbers except 0)

**Example 3:** f(x) = √(4-x²)

*Step 1:* Find where the function is defined (where the expression under the square root is non-negative)
- 4-x² ≥ 0
- Solving: x² ≤ 4, which gives -2 ≤ x ≤ 2
- Domain: [-2, 2]

*Step 2:* Determine the range by substituting values from the domain
- When x = 0, f(0) = √4 = 2 (maximum value)
- When x = ±2, f(±2) = √0 = 0 (minimum value)
- For all values in between, 0 ≤ f(x) ≤ 2
- Range: [0, 2]

## 2. Important Functions

### 2.1 Trigonometric Functions

Trigonometric functions relate angles to the ratios of sides in a right triangle, but they can be extended to all real numbers through the unit circle concept.

**Sine and Cosine Functions:**
- sin(x): The y-coordinate of a point on the unit circle at angle x
- cos(x): The x-coordinate of a point on the unit circle at angle x
- Domain: All real numbers (ℝ)
- Range: [-1, 1] (the coordinates can't exceed the radius of the unit circle)

**Tangent Function:**
- tan(x) = sin(x)/cos(x)
- Domain: All real numbers except x = π/2 + nπ where n is an integer (these are the values where cos(x) = 0)
- Range: All real numbers (ℝ)

**Important Properties:**
- sin(x+2π) = sin(x), cos(x+2π) = cos(x) (periodic with period 2π)
- sin(-x) = -sin(x) (odd function)
- cos(-x) = cos(x) (even function)
- sin²(x) + cos²(x) = 1 (Pythagorean identity)

**Example:** Find the domain and range of f(x) = tan(x)

*Solution:*
- Since tan(x) = sin(x)/cos(x), tan(x) is undefined when cos(x) = 0
- cos(x) = 0 when x = π/2 + nπ for any integer n
- Domain: {x | x ∈ ℝ, x ≠ π/2 + nπ, where n is an integer}
- Range: ℝ (all real numbers)

### 2.2 Polynomials

A polynomial is an expression consisting of variables and coefficients combined using only addition, subtraction, multiplication, and non-negative integer exponents.

General form: P(x) = anx^n + an-1x^(n-1) + ... + a1x + a0

Where:
- n is a non-negative integer called the degree of the polynomial
- an, an-1, ..., a1, a0 are constants, with an ≠ 0

**Properties of Polynomials:**
- Domain: All real numbers (ℝ)
- Continuous and smooth for all x
- Range depends on the specific polynomial

**Important Property:** If two polynomials P(x) and Q(x) are equal for all values of x, then:
1. They have the same degree
2. Their corresponding coefficients are equal

**Example:** Determine if the following polynomials are equal: P(x) = 3x³ + 2x² - 5x + 1 and Q(x) = 3x³ + 2x² - 5x + 2

*Solution:*
- Both polynomials have the same degree (n = 3)
- Comparing coefficients:
  - Coefficient of x³: 3 = 3 ✓
  - Coefficient of x²: 2 = 2 ✓
  - Coefficient of x: -5 = -5 ✓
  - Constant term: 1 ≠ 2 ✗
- Since the constant terms differ, the polynomials are not equal

### 2.3 Rational Functions

A rational function is a fraction where both the numerator and denominator are polynomials.

General form: R(x) = P(x)/Q(x), where P(x) and Q(x) are polynomials and Q(x) ≠ 0

**Domain:** All real numbers except where Q(x) = 0 (these values make the denominator zero, causing the function to be undefined)

**Range:** Depends on the specific rational function

**Example:** Find the domain of R(x) = (x² - 4)/(x² - x - 6)

*Solution:*
*Step 1:* Find where the denominator equals zero
- x² - x - 6 = 0
- (x - 3)(x + 2) = 0
- x = 3 or x = -2

*Step 2:* Express the domain
- Domain: {x | x ∈ ℝ, x ≠ 3, x ≠ -2}

### 2.4 Inverse Functions

If a function f maps x to y, then its inverse function f⁻¹ maps y back to x.

For a function to have an inverse:
- It must be one-to-one (injective): each output comes from exactly one input
- Graphically, this means the function passes the horizontal line test

**Finding the Inverse:**
1. Replace f(x) with y
2. Interchange x and y (swap them)
3. Solve for y
4. Replace y with f⁻¹(x)

**Properties of Inverse Functions:**
- If y = f(x), then x = f⁻¹(y)
- f(f⁻¹(x)) = x and f⁻¹(f(x)) = x
- The domain of f⁻¹ is the range of f
- The range of f⁻¹ is the domain of f

**Example 1:** Find the inverse of f(x) = 2x - 3

*Solution:*
*Step 1:* Replace f(x) with y
- y = 2x - 3

*Step 2:* Interchange x and y
- x = 2y - 3

*Step 3:* Solve for y
- x + 3 = 2y
- y = (x + 3)/2

*Step 4:* Replace y with f⁻¹(x)
- f⁻¹(x) = (x + 3)/2

*Verification:* 
- f(f⁻¹(x)) = 2((x + 3)/2) - 3 = x + 3 - 3 = x ✓
- f⁻¹(f(x)) = ((2x - 3) + 3)/2 = 2x/2 = x ✓

**Example 2:** Find the inverse of f(x) = x²

*Solution:*
The function f(x) = x² is not one-to-one on ℝ because multiple inputs give the same output (e.g., f(2) = f(-2) = 4).

To make it invertible, we must restrict the domain. A common choice is to restrict to x ≥ 0:

- f(x) = x² for x ≥ 0
- Then f⁻¹(x) = √x for x ≥ 0

*Verification:*
- f(f⁻¹(x)) = f(√x) = (√x)² = x ✓
- f⁻¹(f(x)) = f⁻¹(x²) = √(x²) = |x| = x (when x ≥ 0) ✓

### 2.5 Exponential Function

The exponential function is denoted as f(x) = eˣ or exp(x), where e ≈ 2.71828... is Euler's number.

**Key Properties:**
- f(0) = e⁰ = 1
- f'(x) = eˣ (self-derivative)
- eˣ > 0 for all real x
- eᵃ⁺ᵇ = eᵃ·eᵇ
- (eᵃ)ᵇ = eᵃᵇ
- Domain: ℝ (all real numbers)
- Range: (0, ∞) (all positive real numbers)

**Limits:**
- As x → ∞, eˣ → ∞
- As x → -∞, eˣ → 0

**Power Series Representation:**
eˣ = 1 + x + x²/2! + x³/3! + x⁴/4! + ...

**Example:** Evaluate e⁻², approximating e as 2.718

*Solution:*
e⁻² = 1/(e²) = 1/(2.718²) = 1/7.388 ≈ 0.135

### 2.6 Hyperbolic Functions

Hyperbolic functions are analogous to trigonometric functions but are defined using exponentials instead of angles.

**Definitions:**
- sinh(x) = (eˣ - e⁻ˣ)/2
- cosh(x) = (eˣ + e⁻ˣ)/2
- tanh(x) = sinh(x)/cosh(x) = (eˣ - e⁻ˣ)/(eˣ + e⁻ˣ)

**Properties:**
- cosh(-x) = cosh(x) (even function)
- sinh(-x) = -sinh(x) (odd function)
- cosh²(x) - sinh²(x) = 1 (analogous to sin²(x) + cos²(x) = 1)
- Domain of sinh and cosh: ℝ (all real numbers)
- Range of sinh: ℝ (all real numbers)
- Range of cosh: [1, ∞)
- Range of tanh: (-1, 1)

**Limits:**
- As x → ∞: sinh(x) → ∞, cosh(x) → ∞, tanh(x) → 1
- As x → -∞: sinh(x) → -∞, cosh(x) → ∞, tanh(x) → -1

**Example:** Evaluate sinh(0) and cosh(0)

*Solution:*
- sinh(0) = (e⁰ - e⁻⁰)/2 = (1 - 1)/2 = 0
- cosh(0) = (e⁰ + e⁻⁰)/2 = (1 + 1)/2 = 1

### 2.7 Natural Logarithm

The natural logarithm, denoted as ln(x), is the inverse of the exponential function.

**Definition:** For any positive real number x, ln(x) is the value of y for which eʸ = x.

**Key Properties:**
- ln(eˣ) = x for all x ∈ ℝ
- eᶫⁿ⁽ˣ⁾ = x for all x > 0
- ln(ab) = ln(a) + ln(b)
- ln(a/b) = ln(a) - ln(b)
- ln(aᵏ) = k·ln(a)
- Domain: (0, ∞) (all positive real numbers)
- Range: ℝ (all real numbers)

**Example:** Simplify ln(e³) and evaluate ln(5/2)

*Solution:*
- ln(e³) = 3 (using the property ln(eˣ) = x)
- ln(5/2) = ln(5) - ln(2) ≈ 1.609 - 0.693 = 0.916

### 2.8 Implicit Functions

An implicit function is a relationship between x and y expressed in the form F(x,y) = 0, rather than explicitly as y = f(x).

**Examples of Implicit Functions:**
- Circle: x² + y² = r²
- Ellipse: (x²/a²) + (y²/b²) = 1
- Hyperbola: (x²/a²) - (y²/b²) = 1

To sketch an implicit function:
1. Try to solve for y in terms of x (if possible)
2. Identify key points (intercepts, etc.)
3. Use symmetry properties if applicable

**Example:** Sketch the curve defined by x² + y² = 4

*Solution:*
*Step 1:* Solve for y
- x² + y² = 4
- y² = 4 - x²
- y = ±√(4 - x²)

*Step 2:* Determine the domain
- The expression under the square root must be non-negative
- 4 - x² ≥ 0
- x² ≤ 4
- -2 ≤ x ≤ 2

*Step 3:* Sketch the curve
- This is a circle with center at (0,0) and radius 2
- x-intercepts: (±2, 0)
- y-intercepts: (0, ±2)

## 3. Limits

### 3.1 Intuitive Understanding of Limits

A limit describes the behavior of a function as its input approaches a particular value. Intuitively, the limit of f(x) as x approaches a is the value that f(x) gets closer and closer to as x gets closer and closer to a (but not equal to a).

We write: lim(x→a) f(x) = L

This means: As x gets arbitrarily close to a (but not equal to a), f(x) gets arbitrarily close to L.

### 3.2 One-Sided Limits

Sometimes the limit from the left and the limit from the right may differ:

**Right-hand limit:** lim(x→a⁺) f(x) = L₁ (approaching a from values greater than a)
**Left-hand limit:** lim(x→a⁻) f(x) = L₂ (approaching a from values less than a)

If L₁ = L₂, then the limit exists and lim(x→a) f(x) = L₁ = L₂.
If L₁ ≠ L₂, then the limit does not exist.

### 3.3 Formal Definition of Limit (ε-δ Definition)

For a function f(x) and a number L, we say lim(x→a) f(x) = L if for every ε > 0, there exists a δ > 0 such that:

If 0 < |x - a| < δ, then |f(x) - L| < ε

This means: We can make f(x) as close as we want to L (within any small ε) by making x sufficiently close to a (within some small δ).

### 3.4 Important Limit Examples

**Example 1:** Evaluate lim(x→0) (sin x)/x

*Solution:*
This limit represents an indeterminate form (0/0) since both sin(0) = 0 and the denominator approaches 0.

We can evaluate this by looking at values of (sin x)/x as x approaches 0:

| x (radians) | sin(x) | sin(x)/x |
|-------------|--------|----------|
| 0.1         | 0.0998 | 0.9983   |
| 0.01        | 0.0100 | 0.9998   |
| 0.001       | 0.0010 | 0.9999   |

As x approaches 0, (sin x)/x approaches 1.
Therefore, lim(x→0) (sin x)/x = 1

**Example 2:** Evaluate lim(x→1) (x³-1)/(x-1)

*Solution:*
This is another indeterminate form (0/0) since when x = 1, both the numerator and denominator equal 0.

*Method 1: Factoring*
- x³-1 = (x-1)(x²+x+1)
- (x³-1)/(x-1) = (x-1)(x²+x+1)/(x-1) = x²+x+1

Now we can evaluate the limit:
lim(x→1) (x³-1)/(x-1) = lim(x→1) (x²+x+1) = 1²+1+1 = 3

*Method 2: Direct substitution after algebraic manipulation*
(x³-1)/(x-1) = ((x-1)(x²+x+1))/(x-1) = x²+x+1

Then lim(x→1) (x²+x+1) = 1²+1+1 = 3

**Example 3:** Find lim(x→0) e^(-1/x)

*Solution:*
We need to analyze the behavior from the right (x→0⁺) and left (x→0⁻) separately.

*For x→0⁺ (x is positive and approaches 0):*
- As x→0⁺, -1/x→-∞
- e^(-∞) = 0
- Therefore, lim(x→0⁺) e^(-1/x) = 0

*For x→0⁻ (x is negative and approaches 0):*
- As x→0⁻, -1/x→+∞
- e^(+∞) = ∞
- Therefore, lim(x→0⁻) e^(-1/x) = ∞

Since the left and right limits are different, lim(x→0) e^(-1/x) does not exist.

### 3.5 Properties of Limits

If lim(x→a) f(x) = L and lim(x→a) g(x) = M, then:

1. **Sum rule:** lim(x→a) [f(x) + g(x)] = L + M
2. **Difference rule:** lim(x→a) [f(x) - g(x)] = L - M
3. **Product rule:** lim(x→a) [f(x) · g(x)] = L · M
4. **Quotient rule:** lim(x→a) [f(x)/g(x)] = L/M (provided M ≠ 0)
5. **Constant multiple rule:** lim(x→a) [k·f(x)] = k·L (where k is a constant)
6. **Power rule:** lim(x→a) [f(x)]^n = L^n (for any real number n, provided L > 0 if n is not an integer)

**Example:** Find lim(x→2) (x² + 3x - 2)/(x - 1)

*Solution:*
Using the properties of limits:
- lim(x→2) x² = 2² = 4
- lim(x→2) 3x = 3·2 = 6
- lim(x→2) -2 = -2
- lim(x→2) (x - 1) = 2 - 1 = 1

Therefore:
lim(x→2) (x² + 3x - 2)/(x - 1) = (4 + 6 - 2)/1 = 8/1 = 8

## 4. Curve Sketching

### 4.1 Strategy for Sketching Curves

To sketch the graph of a function y = f(x), follow these steps:

1. **Find intercepts**
   - x-intercepts: values of x where f(x) = 0
   - y-intercept: value of f(0) (if 0 is in the domain)

2. **Identify horizontal asymptotes**
   - Find lim(x→∞) f(x) and lim(x→-∞) f(x)
   - If either limit equals some finite value L, then y = L is a horizontal asymptote

3. **Find vertical asymptotes**
   - Look for values of x where f(x) approaches ±∞
   - Typically occurs when the denominator of a rational function equals zero

4. **Determine regions where the function is undefined**
   - Check for domain restrictions (e.g., square roots of negative numbers, logarithms of non-positive numbers)

5. **Look for symmetry**
   - Even function [f(-x) = f(x)]: symmetric about the y-axis
   - Odd function [f(-x) = -f(x)]: symmetric about the origin

6. **Find critical points** (stationary points where f'(x) = 0 or f'(x) is undefined)
   - Calculate f'(x) and find where f'(x) = 0
   - Classify as maxima, minima, or inflection points

7. **Determine intervals of increase/decrease**
   - Where f'(x) > 0, f(x) is increasing
   - Where f'(x) < 0, f(x) is decreasing

8. **Find intervals of concavity**
   - Where f''(x) > 0, f(x) is concave up
   - Where f''(x) < 0, f(x) is concave down

9. **Sketch the curve using all the information gathered**

### 4.2 Detailed Example: Sketch y = 1/(x-1)

*Step 1: Find intercepts*
- Solving for x-intercepts: 1/(x-1) = 0
  - This has no solution since the numerator is never zero
  - There are no x-intercepts
- y-intercept: f(0) = 1/(0-1) = -1
  - The y-intercept is at (0, -1)

*Step 2: Find horizontal asymptotes*
- lim(x→∞) 1/(x-1) = 0
- lim(x→-∞) 1/(x-1) = 0
- Therefore, y = 0 (the x-axis) is a horizontal asymptote

*Step 3: Find vertical asymptotes*
- The function is undefined when the denominator equals zero: x - 1 = 0
- This occurs at x = 1
- Therefore, x = 1 is a vertical asymptote

*Step 4: Determine undefined regions*
- The function is undefined only at x = 1 (the vertical asymptote)

*Step 5: Check for symmetry*
- f(-x) = 1/(-x-1) = 1/-(x+1) = -1/(x+1) ≠ ±f(x)
- The function has no obvious symmetry

*Step 6: Find critical points*
- f'(x) = -1/(x-1)²
- Since f'(x) ≠ 0 for any x ≠ 1, there are no critical points

*Step 7: Determine intervals of increase/decrease*
- f'(x) = -1/(x-1)² < 0 for all x ≠ 1
- The function is always decreasing on its domain

*Step 8: Find intervals of concavity*
- f''(x) = 2/(x-1)³
- For x < 1, f''(x) < 0, so the function is concave down
- For x > 1, f''(x) > 0, so the function is concave up

*Step 9: Sketch the curve*
- Plot the y-intercept at (0, -1)
- Draw the vertical asymptote at x = 1
- Draw the horizontal asymptote at y = 0
- Sketch the curve decreasing and concave down for x < 1
- Sketch the curve decreasing and concave up for x > 1

The resulting curve is a hyperbola with two branches, one in the second quadrant and one in the fourth quadrant.

### 4.3 Example: Sketch y = x² - 4x + 3

*Step 1: Find intercepts*
- x-intercepts: x² - 4x + 3 = 0
  - Using the quadratic formula: x = (4 ± √(16-12))/2 = (4 ± 2)/2
  - x = 1 or x = 3
  - The x-intercepts are at (1, 0) and (3, 0)
- y-intercept: f(0) = 0² - 4(0) + 3 = 3
  - The y-intercept is at (0, 3)

*Step 2: Find horizontal asymptotes*
- lim(x→±∞) (x² - 4x + 3) = ∞
- There are no horizontal asymptotes

*Step 3: Find vertical asymptotes*
- The function is a polynomial, so there are no vertical asymptotes

*Step 4: Determine undefined regions*
- The function is defined for all real numbers

*Step 5: Check for symmetry*
- The function is a quadratic, so it has no symmetry about the y-axis or origin
- However, it is symmetric about its axis of symmetry at x = 2

*Step 6: Find critical points*
- f'(x) = 2x - 4
- f'(x) = 0 when x = 2
- f''(x) = 2 > 0 for all x
- Therefore, (2, -1) is a minimum point

*Step 7: Determine intervals of increase/decrease*
- f'(x) < 0 for x < 2, so f(x) is decreasing on (-∞, 2)
- f'(x) > 0 for x > 2, so f(x) is increasing on (2, ∞)

*Step 8: Find intervals of concavity*
- f''(x) = 2 > 0 for all x
- The function is always concave up

*Step 9: Sketch the curve*
- Plot the intercepts at (0, 3), (1, 0), and (3, 0)
- Plot the minimum point at (2, -1)
- Draw a parabola that is always concave up, decreasing on (-∞, 2) and increasing on (2, ∞)

The resulting curve is a parabola opening upward with vertex at (2, -1).

## 5. Differentiation

### 5.1 The Concept of a Derivative

The derivative of a function represents its rate of change. Geometrically, it is the slope of the tangent line to the curve at a specific point.

**Definition:** The derivative of f(x) at x = a is defined as:

f'(a) = lim(h→0) [f(a+h) - f(a)]/h

provided this limit exists.

**Notation:** If y = f(x), the derivative can be written as:
- f'(x) (Lagrange notation)
- dy/dx (Leibniz notation)
- y' (prime notation)

### 5.2 Geometric Interpretation

The derivative f'(a) represents:
- The slope of the tangent line to the curve y = f(x) at the point (a, f(a))
- The instantaneous rate of change of f(x) with respect to x at x = a

### 5.3 Rules of Differentiation

Here are the fundamental rules for calculating derivatives:

1. **Constant Rule:** If f(x) = c (constant), then f'(x) = 0

2. **Power Rule:** If f(x) = xⁿ, then f'(x) = nxⁿ⁻¹

3. **Constant Multiple Rule:** If f(x) = c·g(x), then f'(x) = c·g'(x)

4. **Sum/Difference Rule:** If f(x) = g(x) ± h(x), then f'(x) = g'(x) ± h'(x)

5. **Product Rule:** If f(x) = g(x)·h(x), then f'(x) = g'(x)·h(x) + g(x)·h'(x)

6. **Quotient Rule:** If f(x) = g(x)/h(x), then f'(x) = [g'(x)·h(x) - g(x)·h'(x)]/[h(x)]²

7. **Chain Rule:** If f(x) = g(h(x)), then f'(x) = g'(h(x))·h'(x)

8. **Derivatives of Trigonometric Functions:**
   - d/dx(sin x) = cos x
   - d/dx(cos x) = -sin x
   - d/dx(tan x) = sec² x

9. **Derivatives of Exponential and Logarithmic Functions:**
   - d/dx(eˣ) = eˣ
   - d/dx(aˣ) = aˣ·ln(a)
   - d/dx(ln x) = 1/x
   - d/dx(logₐ x) = 1/(x·ln a)

### 5.4 Examples of Differentiation

**Example 1:** Find the derivative of f(x) = 3x⁵ - 2x³ + 4x - 7

*Solution:*
Using the power rule and the sum/difference rule:
- d/dx(3x⁵) = 3·5x⁴ = 15x⁴
- d/dx(-2x³) = -2·3x² = -6x²
- d/dx(4x) = 4·1x⁰ = 4
- d/dx(-7) = 0

Therefore:
f'(x) = 15x⁴ - 6x² + 4

**Example 2:** Find the derivative of f(x) = x²·sin x

*Solution:*
Using the product rule with g(x) = x² and h(x) = sin x:
- g'(x) = 2x
- h'(x) = cos x

f'(x) = g'(x)·h(x) + g(x)·h'(x)
      = 2x·sin x + x²·cos x

**Example 3:** Find the derivative of f(x) = (3x+2)/(x-1)

*Solution:*
Using the quotient rule with g(x) = 3x+2 and h(x) = x-1:
- g'(x) = 3
- h'(x) = 1

f'(x) = [g'(x)·h(x) - g(x)·h'(x)]/[h(x)]²
      = [3·(x-1) - (3x+2)·1]/[(x-1)]²
      = [3x-3 - 3x-2]/[(x-1)]²
      = [-5]/[(x-1)]²
      = -5/[(x-1)]²

**Example 4:** Find the derivative of f(x) = sin(x²)

*Solution:*
Using the chain rule with g(x) = sin(x) and h(x) = x²:
- g'(h(x)) = cos(h(x)) = cos(x²)
- h'(x) = 2x

f'(x) = g'(h(x))·h'(x) = cos(x²)·2x = 2x·cos(x²)

**Example a5:** Find the derivative of f(x) = eˣ·ln x

*Solution:*
Using the product rule with g(x) = eˣ and h(x) = ln x:
- g'(x) = eˣ
- h'(x) = 1/x

f'(x) = g'(x)·h(x) + g(x)·h'(x)
      = eˣ·ln x + eˣ·(1/x)
      = eˣ·(ln x + 1/x)

### 5.5 L'Hôpital's Rule

L'Hôpital's Rule provides a method for evaluating limits of indeterminate forms.

**Theorem:** If lim(x→a) f(x) = 0 and lim(x→a) g(x) = 0, and the derivatives f'(x) and g'(x) exist with g'(x) ≠ 0 near a, then:

lim(x→a) [f(x)/g(x)] = lim(x→a) [f'(x)/g'(x)]

provided the limit on the right exists.

This also applies to the indeterminate form ∞/∞.

**Example 1:** Evaluate lim(x→0) (sin 3x)/(5x)

*Solution:*
This is an indeterminate form 0/0 since sin(3·0) = 0 and 5·0 = 0.

Using L'Hôpital's Rule:
- f'(x) = 3·cos(3x)
- g'(x) = 5

lim(x→0) [(sin 3x)/(5x)] = lim(x→0) [3·cos(3x)/5]
                           = 3·cos(0)/5 = 3/5

**Example 2:** Evaluate lim(x→0) (e^x - 1 - x)/(x²)

*Solution:*
This is an indeterminate form 0/0. Using L'Hôpital's Rule:
- f'(x) = e^x - 1
- g'(x) = 2x

lim(x→0) [(e^x - 1 - x)/(x²)] = lim(x→0) [(e^x - 1)/(2x)]

This is still an indeterminate form 0/0, so we apply L'Hôpital's Rule again:
- f''(x) = e^x
- g''(x) = 2

lim(x→0) [(e^x - 1 - x)/(x²)] = lim(x→0) [e^x/2] = e⁰/2 = 1/2

### 5.6 Higher Order Derivatives

The second derivative f''(x) is the derivative of the first derivative f'(x).
Similarly, the third derivative f'''(x) is the derivative of f''(x), and so on.

**Notation:**
- Second derivative: f''(x) or d²y/dx²
- Third derivative: f'''(x) or d³y/dx³
- n-th derivative: f^(n)(x) or dⁿy/dxⁿ

**Example:** Find the first four derivatives of f(x) = x³ - 3x² + 2x - 5

*Solution:*
- f(x) = x³ - 3x² + 2x - 5
- f'(x) = 3x² - 6x + 2
- f''(x) = 6x - 6
- f'''(x) = 6
- f⁽⁴⁾(x) = 0

## 6. Stationary Points and Their Classification

### 6.1 What is a Stationary Point?

A stationary point (or critical point) of a function f(x) is a point where the derivative equals zero or is undefined.

At a stationary point, the tangent to the curve is horizontal, indicating that the function has temporarily stopped increasing or decreasing.

### 6.2 Types of Stationary Points

There are three main types of stationary points:

1. **Local Maximum:** The function reaches a peak and then decreases
2. **Local Minimum:** The function reaches a valley and then increases
3. **Point of Inflection:** The function changes concavity but continues in the same direction

### 6.3 Classification Using the Second Derivative

To classify a stationary point at x = a:

1. Calculate f'(a). If f'(a) = 0, it's a stationary point.
2. Calculate f''(a).
   - If f''(a) > 0: Local minimum
   - If f''(a) < 0: Local maximum
   - If f''(a) = 0: Need to use higher derivatives or the first derivative test

### 6.4 The First Derivative Test

To use the first derivative test:

1. Identify all values of x where f'(x) = 0 or f'(x) is undefined
2. Determine the sign of f'(x) just before and just after each critical point
3. Classify based on the sign change:
   - If f'(x) changes from positive to negative, it's a local maximum
   - If f'(x) changes from negative to positive, it's a local minimum
   - If f'(x) doesn't change sign, it's a point of inflection

### 6.5 Points of Inflection

A point of inflection occurs when the concavity of the function changes.

To find points of inflection:
1. Calculate f''(x)
2. Find all values of x where f''(x) = 0 or is undefined
3. Check if f''(x) changes sign at these points

### 6.6 Examples

**Example 1:** Find and classify the stationary points of f(x) = x³ - 6x² + 9x + 2

*Solution:*
*Step 1:* Calculate the first derivative and set it equal to zero
- f'(x) = 3x² - 12x + 9
- 3x² - 12x + 9 = 0
- x² - 4x + 3 = 0
- (x - 1)(x - 3) = 0
- x = 1 or x = 3

*Step 2:* Calculate the second derivative
- f''(x) = 6x - 12

*Step 3:* Evaluate f''(x) at each stationary point
- f''(1) = 6(1) - 12 = -6 < 0
- f''(3) = 6(3) - 12 = 6 > 0

*Step 4:* Classify the stationary points
- At x = 1, f''(1) < 0, so this is a local maximum
- At x = 3, f''(3) > 0, so this is a local minimum

**Example 2:** Find and classify the stationary points of f(x) = x⁴ - 4x³ + 10

*Solution:*
*Step 1:* Calculate the first derivative and set it equal to zero
- f'(x) = 4x³ - 12x²
- 4x²(x - 3) = 0
- x = 0 or x = 3

*Step 2:* Calculate the second derivative
- f''(x) = 12x² - 24x

*Step 3:* Evaluate f''(x) at each stationary point
- f''(0) = 0
- f''(3) = 12(9) - 24(3) = 108 - 72 = 36 > 0

*Step 4:* Classify the stationary points
- At x = 3, f''(3) > 0, so this is a local minimum
- At x = 0, f''(0) = 0, so the second derivative test is inconclusive

*Step 5:* Use the first derivative test for x = 0
- For x < 0, f'(x) = 4x³ - 12x² = 4x²(x - 3) is negative (since x - 3 < 0 and x² > 0)
- For 0 < x < 3, f'(x) is still negative
- Since f'(x) doesn't change sign at x = 0, this is a point of inflection

**Example 3:** Find and classify all stationary points of f(x) = x² - 2x + 3

*Solution:*
*Step 1:* Calculate the first derivative and set it equal to zero
- f'(x) = 2x - 2
- 2x - 2 = 0
- x = 1

*Step 2:* Calculate the second derivative
- f''(x) = 2 > 0 for all x

*Step 3:* Classify the stationary point
- Since f''(1) = 2 > 0, x = 1 is a local minimum
- The function value at this point is f(1) = 1² - 2(1) + 3 = 1 - 2 + 3 = 2

## 7. Taylor Series

### 7.1 What is a Taylor Series?

A Taylor series is a way to represent a function as an infinite sum of terms calculated from the function's derivatives at a particular point.

The Taylor series of a function f(x) centered at x = a is:

f(x) = f(a) + f'(a)(x-a) + (f''(a)/2!)(x-a)² + (f'''(a)/3!)(x-a)³ + ...

Or more compactly:

f(x) = ∑[n=0 to ∞] (f⁽ⁿ⁾(a)/n!)(x-a)ⁿ

Where f⁽ⁿ⁾(a) is the nth derivative of f at x = a, and n! is the factorial of n.

### 7.2 Maclaurin Series

A Maclaurin series is a Taylor series centered at x = 0:

f(x) = f(0) + f'(0)x + (f''(0)/2!)x² + (f'''(0)/3!)x³ + ...

Or more compactly:

f(x) = ∑[n=0 to ∞] (f⁽ⁿ⁾(0)/n!)xⁿ

### 7.3 Common Taylor Series Expansions

**Exponential function:**
e^x = 1 + x + x²/2! + x³/3! + x⁴/4! + ...

**Sine function:**
sin(x) = x - x³/3! + x⁵/5! - x⁷/7! + ...

**Cosine function:**
cos(x) = 1 - x²/2! + x⁴/4! - x⁶/6! + ...

**Natural logarithm:**
ln(1+x) = x - x²/2 + x³/3 - x⁴/4 + ... (for -1 < x ≤ 1)

### 7.4 Applications of Taylor Series

1. **Approximating functions:** Use the first few terms of a Taylor series to approximate a function near a specific point

2. **Evaluating difficult limits:** Convert expressions to Taylor series to compute limits

3. **Numerical calculations:** Use truncated Taylor series for numerical algorithms

4. **Solving differential equations:** Use series solutions for differential equations

5. **Understanding behavior near a point:** Analyze the behavior of a function near a stationary point

### 7.5 Taylor Polynomials

A Taylor polynomial of degree n is the sum of the first n+1 terms of the Taylor series:

Pₙ(x) = ∑[k=0 to n] (f⁽ᵏ⁾(a)/k!)(x-a)ᵏ

Taylor polynomials provide approximations to functions, with higher-degree polynomials typically giving better approximations near x = a.

### 7.6 Examples

**Example 1:** Find the Maclaurin series for f(x) = cos x up to the x⁶ term

*Solution:*
We need to calculate the derivatives of cos x at x = 0:
- f(x) = cos x
- f'(x) = -sin x
- f''(x) = -cos x
- f'''(x) = sin x
- f⁽⁴⁾(x) = cos x
- f⁽⁵⁾(x) = -sin x
- f⁽⁶⁾(x) = -cos x

Evaluating at x = 0:
- f(0) = cos(0) = 1
- f'(0) = -sin(0) = 0
- f''(0) = -cos(0) = -1
- f'''(0) = sin(0) = 0
- f⁽⁴⁾(0) = cos(0) = 1
- f⁽⁵⁾(0) = -sin(0) = 0
- f⁽⁶⁾(0) = -cos(0) = -1

The Maclaurin series up to the x⁶ term is:
cos x = 1 + 0·x + (-1/2!)x² + 0·x³ + (1/4!)x⁴ + 0·x⁵ + (-1/6!)x⁶ + ...
      = 1 - x²/2 + x⁴/24 - x⁶/720 + ...

**Example 2:** Find the Taylor series for ln(x) about x = 1

*Solution:*
We need to calculate the derivatives of ln(x) at x = 1:
- f(x) = ln(x)
- f'(x) = 1/x
- f''(x) = -1/x²
- f'''(x) = 2/x³
- f⁽⁴⁾(x) = -6/x⁴
- f⁽⁵⁾(x) = 24/x⁵

Evaluating at x = 1:
- f(1) = ln(1) = 0
- f'(1) = 1/1 = 1
- f''(1) = -1/1² = -1
- f'''(1) = 2/1³ = 2
- f⁽⁴⁾(1) = -6/1⁴ = -6
- f⁽⁵⁾(1) = 24/1⁵ = 24

The Taylor series about x = 1 is:
ln(x) = 0 + 1·(x-1) + (-1/2)(x-1)² + (2/6)(x-1)³ + (-6/24)(x-1)⁴ + (24/120)(x-1)⁵ + ...
      = (x-1) - (x-1)²/2 + (x-1)³/3 - (x-1)⁴/4 + (x-1)⁵/5 + ...

**Example 3:** Use a Taylor polynomial of degree 2 to approximate e^0.1

*Solution:*
We'll use the Maclaurin series for e^x and evaluate at x = 0.1:
e^x = 1 + x + x²/2! + x³/3! + ...

The second-degree approximation is:
P₂(x) = 1 + x + x²/2

Therefore:
e^0.1 ≈ 1 + 0.1 + (0.1)²/2 = 1 + 0.1 + 0.005 = 1.105

The actual value is approximately 1.10517, so our approximation is accurate to four decimal places.

### 7.7 Taylor Series at Stationary Points

Taylor series are particularly useful for analyzing the behavior of a function near a stationary point.

If f'(a) = 0, the Taylor series starts with the constant term and the second-degree term:

f(x) = f(a) + (f''(a)/2)(x-a)² + higher-order terms

This helps classify the stationary point:
- If f''(a) > 0, it's a local minimum (the parabola opens upward)
- If f''(a) < 0, it's a local maximum (the parabola opens downward)
- If f''(a) = 0, we need to look at higher-order terms

**Example:** Analyze the function f(x) = x⁴ - 4x² + 3 near x = 0

*Solution:*
- f'(x) = 4x³ - 8x
- f'(0) = 0, so x = 0 is a stationary point
- f''(x) = 12x² - 8
- f''(0) = -8 < 0, so x = 0 is a local maximum

The Taylor series at x = 0 is:
f(x) = f(0) + f'(0)x + (f''(0)/2)x² + (f'''(0)/6)x³ + (f⁽⁴⁾(0)/24)x⁴ + ...
     = 3 + 0 + (-8/2)x² + 0 + (24/24)x⁴ + ...
     = 3 - 4x² + x⁴ + ...

The negative coefficient of x² confirms that this is a local maximum.

## 8. Integration

### 8.1 The Indefinite Integral

Integration is the inverse operation of differentiation. The indefinite integral of a function f(x) is denoted by:

∫f(x)dx = F(x) + C

Where:
- F(x) is a function such that F'(x) = f(x)
- C is an arbitrary constant called the constant of integration

### 8.2 Basic Integration Rules

1. **Constant Rule:** ∫k dx = kx + C (where k is a constant)

2. **Power Rule:** ∫xⁿ dx = x^(n+1)/(n+1) + C (for n ≠ -1)

3. **Logarithmic Rule:** ∫(1/x) dx = ln|x| + C

4. **Exponential Rule:** ∫e^x dx = e^x + C

5. **Trigonometric Rules:**
   - ∫sin(x) dx = -cos(x) + C
   - ∫cos(x) dx = sin(x) + C
   - ∫tan(x) dx = -ln|cos(x)| + C

6. **Sum/Difference Rule:** ∫[f(x) ± g(x)] dx = ∫f(x) dx ± ∫g(x) dx

7. **Constant Multiple Rule:** ∫k·f(x) dx = k·∫f(x) dx

### 8.3 Examples of Basic Integration

**Example 1:** Find ∫(3x² + 2x - 5) dx

*Solution:*
Using the sum/difference rule and the power rule:
∫(3x² + 2x - 5) dx = 3∫x² dx + 2∫x dx - 5∫dx
                     = 3(x³/3) + 2(x²/2) - 5x + C
                     = x³ + x² - 5x + C

**Example 2:** Find ∫√x dx

*Solution:*
Rewrite using the power rule:
∫√x dx = ∫x^(1/2) dx = x^(3/2)/(3/2) + C = (2/3)x^(3/2) + C

**Example 3:** Find ∫(e^x + 1/x) dx

*Solution:*
Using the sum rule:
∫(e^x + 1/x) dx = ∫e^x dx + ∫(1/x) dx = e^x + ln|x| + C

### 8.4 The Definite Integral

The definite integral of a function f(x) from x = a to x = b is denoted by:

∫[a to b] f(x) dx = F(b) - F(a)

Where F(x) is an antiderivative of f(x).

Geometrically, the definite integral represents the signed area between the curve y = f(x) and the x-axis from x = a to x = b.

### 8.5 Examples of Definite Integration

**Example 1:** Calculate ∫[0 to 1] (3x² + 2) dx

*Solution:*
First, find the indefinite integral:
∫(3x² + 2) dx = 3(x³/3) + 2x + C = x³ + 2x + C

Then, evaluate at the endpoints:
∫[0 to 1] (3x² + 2) dx = (1³ + 2·1) - (0³ + 2·0) = 3 - 0 = 3

**Example 2:** Calculate ∫[0 to π/2] sin(x) dx

*Solution:*
First, find the indefinite integral:
∫sin(x) dx = -cos(x) + C

Then, evaluate at the endpoints:
∫[0 to π/2] sin(x) dx = [-cos(x)]₀^(π/2) = -cos(π/2) - (-cos(0)) = 0 - (-1) = 1

**Example 3:** Calculate ∫[1 to 2] (1/x) dx

*Solution:*
First, find the indefinite integral:
∫(1/x) dx = ln|x| + C

Then, evaluate at the endpoints:
∫[1 to 2] (1/x) dx = [ln|x|]₁^₂ = ln(2) - ln(1) = ln(2) - 0 = ln(2) ≈ 0.693

### 8.6 Properties of Definite Integrals

1. **Reversal of Limits:** ∫[a to b] f(x) dx = -∫[b to a] f(x) dx

2. **Additivity of Intervals:** ∫[a to b] f(x) dx + ∫[b to c] f(x) dx = ∫[a to c] f(x) dx

3. **Linearity:** ∫[a to b] [k·f(x) + m·g(x)] dx = k·∫[a to b] f(x) dx + m·∫[a to b] g(x) dx

4. **Comparison:** If f(x) ≤ g(x) for all x in [a, b], then ∫[a to b] f(x) dx ≤ ∫[a to b] g(x) dx

### 8.7 Integration by Substitution

Integration by substitution is a technique used to simplify integrals by making a substitution that transforms the integral into a more manageable form.

**Method:**
1. Let u = g(x)
2. Then du = g'(x) dx
3. Substitute to get ∫f(g(x))·g'(x) dx = ∫f(u) du
4. Integrate with respect to u
5. Substitute back in terms of x

### 8.8 Examples of Integration by Substitution

**Example 1:** Find ∫cos(3x) dx

*Solution:*
*Step 1:* Let u = 3x, then du = 3 dx, so dx = du/3
*Step 2:* Substitute:
∫cos(3x) dx = ∫cos(u)·(du/3) = (1/3)∫cos(u) du = (1/3)·sin(u) + C
*Step 3:* Substitute back:
∫cos(3x) dx = (1/3)·sin(3x) + C

**Example 2:** Find ∫x·e^(x²) dx

*Solution:*
*Step 1:* Let u = x², then du = 2x dx, so x dx = du/2
*Step 2:* Substitute:
∫x·e^(x²) dx = ∫e^u·(du/2) = (1/2)∫e^u du = (1/2)·e^u + C
*Step 3:* Substitute back:
∫x·e^(x²) dx = (1/2)·e^(x²) + C

**Example 3:** Find ∫x·√(1+x²) dx

*Solution:*
*Step 1:* Let u = 1+x², then du = 2x dx, so x dx = du/2
*Step 2:* Substitute:
∫x·√(1+x²) dx = ∫√u·(du/2) = (1/2)∫u^(1/2) du = (1/2)·(u^(3/2)/(3/2)) + C = (1/3)·u^(3/2) + C
*Step 3:* Substitute back:
∫x·√(1+x²) dx = (1/3)·(1+x²)^(3/2) + C

### 8.9 Integration by Parts

Integration by parts is based on the product rule for differentiation and is used when integrating products of functions.

**Formula:** ∫u·v' dx = u·v - ∫v·u' dx

Where:
- u and v are functions of x
- u' is the derivative of u
- v' is the derivative of v

In practice, we set:
- u = first function
- dv/dx = second function
- Then du/dx = derivative of u
- v = antiderivative of dv/dx

### 8.10 Examples of Integration by Parts

**Example 1:** Find ∫x·e^x dx

*Solution:*
*Step 1:* Choose u = x and dv/dx = e^x
*Step 2:* Calculate du/dx = 1 and v = ∫e^x dx = e^x
*Step 3:* Apply the integration by parts formula:
∫x·e^x dx = x·e^x - ∫e^x·1 dx = x·e^x - e^x + C = e^x·(x-1) + C

**Example 2:** Find ∫ln(x) dx

*Solution:*
*Step 1:* Choose u = ln(x) and dv/dx = 1
*Step 2:* Calculate du/dx = 1/x and v = ∫1 dx = x
*Step 3:* Apply the integration by parts formula:
∫ln(x) dx = ln(x)·x - ∫x·(1/x) dx = x·ln(x) - ∫1 dx = x·ln(x) - x + C

**Example 3:** Find ∫x²·sin(x) dx

*Solution:*
*Step 1:* Choose u = x² and dv/dx = sin(x)
*Step 2:* Calculate du/dx = 2x and v = ∫sin(x) dx = -cos(x)
*Step 3:* Apply the integration by parts formula:
∫x²·sin(x) dx = x²·(-cos(x)) - ∫(-cos(x))·2x dx = -x²·cos(x) + 2∫x·cos(x) dx

We now need to evaluate ∫x·cos(x) dx using integration by parts again:
*Step 1:* Choose u = x and dv/dx = cos(x)
*Step 2:* Calculate du/dx = 1 and v = ∫cos(x) dx = sin(x)
*Step 3:* Apply the integration by parts formula:
∫x·cos(x) dx = x·sin(x) - ∫sin(x)·1 dx = x·sin(x) - (-cos(x)) + C = x·sin(x) + cos(x) + C

Now substitute back:
∫x²·sin(x) dx = -x²·cos(x) + 2(x·sin(x) + cos(x)) + C
                = -x²·cos(x) + 2x·sin(x) + 2cos(x) + C

### 8.11 Area Between Curves

The area between two curves y = f(x) and y = g(x) from x = a to x = b, where f(x) ≥ g(x) on [a, b], is given by:

Area = ∫[a to b] [f(x) - g(x)] dx

### 8.12 Example of Finding Area Between Curves

**Example:** Find the area between the curves y = x² and y = x³ from x = 0 to x = 1

*Solution:*
*Step 1:* Determine which function is greater on the interval [0, 1]
- For 0 ≤ x ≤ 1, x² ≥ x³
- Therefore, f(x) = x² and g(x) = x³

*Step 2:* Calculate the area
Area = ∫[0 to 1] [x² - x³] dx = ∫[0 to 1] [x²(1-x)] dx
     = [x³/3 - x⁴/4]₀¹
     = (1/3 - 1/4) - (0 - 0)
     = 1/12
     = 0.0833...

The area between the curves is 1/12 square units.

## 9. Differential Equations

### 9.1 Introduction to Differential Equations

A differential equation is an equation that relates a function with its derivatives. The order of a differential equation is the highest derivative that appears in the equation.

For example:
- dy/dx = 2x (first-order)
- d²y/dx² + 3(dy/dx) + 2y = 0 (second-order)

### 9.2 First-Order Differential Equations

A first-order differential equation has the form:

dy/dx = f(x, y)

The solution to a differential equation is a function y = y(x) that satisfies the equation.

### 9.3 Separable Differential Equations

A first-order differential equation is separable if it can be written in the form:

dy/dx = g(x)·h(y)

To solve separable equations:
1. Rearrange to separate variables: (1/h(y))·(dy/dx) = g(x)
2. Integrate both sides: ∫(1/h(y)) dy = ∫g(x) dx + C
3. Solve for y if possible

### 9.4 Examples of Separable Differential Equations

**Example 1:** Solve the differential equation dy/dx = 2xy

*Solution:*
*Step 1:* Separate the variables
- dy/dx = 2xy
- (1/y) dy = 2x dx

*Step 2:* Integrate both sides
- ∫(1/y) dy = ∫2x dx
- ln|y| = x² + C

*Step 3:* Solve for y
- y = ±e^(x² + C) = ±e^C·e^(x²) = Ae^(x²)

Where A = ±e^C is an arbitrary constant.

**Example 2:** Solve dy/dx = y² with the initial condition y(0) = 1

*Solution:*
*Step 1:* Separate the variables
- dy/dx = y²
- (1/y²) dy = dx

*Step 2:* Integrate both sides
- ∫(1/y²) dy = ∫dx
- -1/y = x + C

*Step 3:* Solve for y
- y = -1/(x + C)

*Step 4:* Apply the initial condition y(0) = 1
- 1 = -1/(0 + C)
- C = -1

*Step 5:* Substitute to get the particular solution
- y = -1/(x - 1)
- y = 1/(1 - x)

**Example 3:** Solve the differential equation dy/dx + 3y = 0

*Solution:*
*Step 1:* Separate the variables
- dy/dx + 3y = 0
- dy/dx = -3y
- (1/y) dy = -3 dx

*Step 2:* Integrate both sides
- ∫(1/y) dy = ∫(-3) dx
- ln|y| = -3x + C

*Step 3:* Solve for y
- y = ±e^(-3x + C) = ±e^C·e^(-3x) = Ae^(-3x)

Where A = ±e^C is an arbitrary constant.

### 9.5 Applications of Differential Equations

#### 9.5.1 Newton's Law of Cooling

Newton's Law of Cooling states that the rate of change of temperature of an object is proportional to the difference between its temperature and the ambient temperature.

Mathematically: dT/dt = -k(T - T₀)

Where:
- T is the temperature of the object
- T₀ is the ambient temperature
- k is a positive constant
- t is time

**Example:** A cup of coffee at 90°C is placed in a room at 20°C. After 10 minutes, the coffee temperature is 60°C. How long will it take for the coffee to cool to 30°C?

*Solution:*
*Step 1:* Set up the differential equation
- dT/dt = -k(T - 20)

*Step 2:* Separate variables
- dT/(T - 20) = -k dt

*Step 3:* Integrate both sides
- ∫dT/(T - 20) = ∫(-k) dt
- ln|T - 20| = -kt + C

*Step 4:* Solve for T
- T - 20 = e^(-kt + C) = e^C·e^(-kt) = Ae^(-kt)
- T = 20 + Ae^(-kt)

*Step 5:* Apply the initial condition T(0) = 90
- 90 = 20 + Ae^(0)
- A = 70
- T = 20 + 70e^(-kt)

*Step 6:* Apply the condition T(10) = 60
- 60 = 20 + 70e^(-10k)
- 40 = 70e^(-10k)
- e^(-10k) = 40/70 = 4/7
- -10k = ln(4/7)
- k = -ln(4/7)/10 = ln(7/4)/10

*Step 7:* Find the time t when T = 30
- 30 = 20 + 70e^(-k·t)
- 10 = 70e^(-k·t)
- e^(-k·t) = 10/70 = 1/7
- -k·t = ln(1/7)
- t = -ln(1/7)/k = ln(7)/k = ln(7)/(ln(7/4)/10) = 10·ln(7)/ln(7/4)

Using a calculator:
t ≈ 10·1.946/0.5596 ≈ 34.8 minutes

The coffee will cool to 30°C after approximately 35 minutes.

#### 9.5.2 Exponential Growth and Decay

Many natural processes follow exponential growth or decay, which can be modeled by the differential equation:

dy/dt = ky

Where:
- y is the quantity
- t is time
- k is a constant (positive for growth, negative for decay)

The solution to this equation is:

y = y₀e^(kt)

Where y₀ is the initial value of y.

**Example:** A radioactive substance decays according to the equation dA/dt = -0.12A, where A is the amount and t is measured in years. If initially there are 100 grams, how much remains after 10 years?

*Solution:*
*Step 1:* Solve the differential equation
- dA/dt = -0.12A
- A = A₀e^(-0.12t)

*Step 2:* Apply the initial condition A₀ = 100
- A = 100e^(-0.12t)

*Step 3:* Calculate the amount after 10 years
- A(10) = 100e^(-0.12·10) = 100e^(-1.2) = 100·0.301 = 30.1 grams

After 10 years, approximately 30.1 grams of the radioactive substance remain.
