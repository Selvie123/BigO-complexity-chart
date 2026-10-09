# BigO-complexity-chart
A beginner-friendly reference chart for DSA time complexity and space complexity, including Big O notation.

#  Big O Complexity Reference Table

| Big O Complexity | Name         | Typical LeetCode Example           | Performance                     |
| ---------------- | ------------ | ---------------------------------- | ------------------------------- |
| `O(1)`           | Constant     | Access an array element            | Excellent                       |
| `O(log n)`       | Logarithmic  | Binary Search                      | Excellent                       |
| `O(n)`           | Linear       | Find the Largest Number            | Good                            |
| `O(n log n)`     | Linearithmic | Merge Sort                         | Moderate                        |
| `O(n²)`          | Quadratic    | Nested Loops / Two Sum Brute Force | Slow for large inputs           |
| `O(2ⁿ)`          | Exponential  | Generate All Subsets               | Very slow for large inputs      |
| `O(n!)`          | Factorial    | Generate All Permutations          | Extremely slow for large inputs |

#Key Takeaway

* Best performance:`O(1)` and `O(log n)`
* Common complexity:`O(n)` and `O(n log n)`
* Avoid for large inputs when possible:`O(n²)`, `O(2ⁿ)`, and `O(n!)`

How to Identify Time Complexity

One simple operation → O(1)
Repeatedly divide the search space → O(log n)
One loop over all elements → O(n)
Two nested loops over all elements → O(n²)
Divide-and-conquer sorting → often O(n log n)
Explore every possible subset → often O(2ⁿ)

Time Complexity vs Space Complexity
Time Complexity: How the number of operations grows with input size.
Space Complexity: How the extra memory usage grows with input size.
