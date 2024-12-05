# Permutations

Permutations are used to find the number of ways to arrange a set of items where the order of arrangement matters. 

## Formula for Permutations

The formula for calculating the number of permutations of \( n \) items taken \( r \) at a time is:

\[
nPr = \frac{n!}{(n-r)!}
\]

Where:
- \( n \) is the total number of items.
- \( r \) is the number of items being chosen.
- \( ! \) (factorial) represents the product of all positive integers up to that number.

## Explanation

Permutations are different from combinations because **order matters** in permutations. For example:
- The arrangements "AB" and "BA" are considered different permutations.

## Examples

### Example 1: Permutation of 5 items taken 3 at a time
\[
n = 5, \, r = 3
\]

Using the formula:
\[
5P3 = \frac{5!}{(5-3)!} = \frac{5 \times 4 \times 3 \times 2 \times 1}{2 \times 1} = 60
\]

So, there are 60 different ways to arrange 5 items taken 3 at a time.

### Example 2: Permutation of 4 items taken 2 at a time
\[
n = 4, \, r = 2
\]

Using the formula:
\[
4P2 = \frac{4!}{(4-2)!} = \frac{4 \times 3 \times 2 \times 1}{2 \times 1} = 12
\]

Thus, there are 12 different ways to arrange 4 items taken 2 at a time.


## Types in the Permutations

## 1. Numbers
### 1.1 Zero and Non-Zero
- **Zero**: Special considerations when it is at the start of a number.
- **Non-Zero**: Can occupy any position in the arrangement.

## 2. Words
### 2.1 Repeating and Non-Repeating
- **Repeating**: Letters or digits can repeat in the arrangement.
- **Non-Repeating**: Each letter or digit is used only once.

### 2.2 Repetition Allowed and Not Allowed
- **Repetition Allowed**: Elements can appear multiple times in the arrangement.
- **Repetition Not Allowed**: No element can be used more than once.

### 2.3 Always Together and Not Always Together
- **Always Together**: A group of elements must be treated as a single block.
- **Not Always Together**: No restriction on how elements are placed.

### 2.4 Odd and Even Places
- **Odd Places**: Elements can only occupy 1st, 3rd, 5th, etc., positions.
- **Even Places**: Elements can only occupy 2nd, 4th, 6th, etc., positions.

### 2.5 No Two Together
- **No Two Together**: Adjacent elements cannot be the same or part of a specific group.




## Note

- If  there are repeated numbers we should  divide it with the number of times it occurs




















## Applications

Permutations are widely used in:
- Arranging people or objects in order.
- Cryptography for generating codes.
- Solving probability problems.

## Key Notes

1. If \( r = n \), then \( nPr = n! \).
2. If \( r = 0 \), then \( nP0 = 1 \) (only one way to arrange zero items).
3. \( nPr \) is defined only if \( n \geq r \).

## Related Concepts

- **Combinations**: Arrangements where the order does not matter.
- **Factorial**: The product of all positive integers up to a given number.

---

Happy Learning!
