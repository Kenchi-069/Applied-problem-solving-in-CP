# What I Learned – Applied Problem Solving in CP (SoC 2025)

This document summarizes my learnings over the 8-week *Applied Problem Solving in Competitive Programming* (SoC 2025) program.

## Key Takeaways Week-by-Week

### Week 1: Introductory Problems
- Mastered CSES basics like Missing Number, Two Knights, and Weird Algorithm
- Learned efficient brute-force and simulation techniques
- Built initial speed and accuracy in solving standard problems

### Week 2: Sorting + Prefix Sums + Sets
- Learned about sorting-based logic and multiset applications
- Solved problems involving prefix sums, event processing, and greedy techniques
- Developed understanding of time complexity trade-offs

### Week 3: Binary Search and Variants
- Practiced binary search on arrays and on answers
- Understood rotated sorted array problems and frequency-based searches
- Improved skill in writing custom binary search conditions

### Week 4: Advanced Binary Search
- Applied binary search to allocation problems like Book Allocation and Aggressive Cows
- Learned optimization on search space using problem constraints
- Grasped the pattern of "minimum possible answer" binary search

### Week 5: Strings & Manipulation
- Practiced real-world string problems like reverse words, anagrams, and palindromes
- Learned how to handle characters, hash maps, and frequency arrays
- Gained confidence in parsing and transforming input strings

### Week 6: Recursion & Backtracking
- Mastered recursive generation of subsets, combinations, and valid parentheses
- Practiced pruning and backtracking for optimization
- Understood subset sum variants deeply

### Week 7: Dynamic Programming Basics
- Learned memoization vs. tabulation
- Solved problems like Climbing Stairs, House Robber, LCS, LIS
- Gained foundational understanding of state transition and overlapping subproblems

### Week 8: Advanced DP & Digit DP
- Implemented subset sum, coin change, edit distance, and digit DP problems
- Learned how to define tight DP states for optimization
- Developed logic for base case handling and recursive DP trees

---

##  Concepts Mastered
- Brute-force and Greedy Patterns
- Binary Search on Arrays and Answers
- Sorting and Prefix Sum Techniques
- Recursion and Backtracking
- 1D & 2D Dynamic Programming
- String Manipulation and Frequency Maps
- Subset, Subsequence & Combination Logic
- Digit DP (Introductory Level)

---

##  Personal Growth
- Improved debugging and speed under time constraints
- Learned to write cleaner, modular code in C++
- Gained better problem pattern recognition and topic-wise mastery
- Became confident in applying DSA to real problems systematically

---

##  Tools Used
- C++ (main language)
- LeetCode, Codeforces, CSES, GeeksforGeeks
- VS Code for development

---

**– Prasoon Badjatya**  
2nd Year, CSE  
IIT Bombay  


# Week 1: Introductory Problems
### Main Problems

| #  | Problem                | Link                                                                 |
|----|------------------------|----------------------------------------------------------------------|
| 1  | Missing Number         | [CSES - Missing Number](https://cses.fi/problemset/task/1083)       |
| 2  | Repetitions            | [CSES - Repetitions](https://cses.fi/problemset/task/1069)          |
| 3  | Coin Combinations I    | [CSES - Coin Combinations I](https://cses.fi/problemset/task/1635)  |
| 4  | Ferris Wheel           | [CSES - Ferris Wheel](https://cses.fi/problemset/task/1090)        |
| 5  | Weird Algorithm        | [CSES - Weird Algorithm](https://cses.fi/problemset/task/1068)      |
| 6  | Increasing Array       | [CSES - Increasing Array](https://cses.fi/problemset/task/1094)     |
| 7  | Tower of Hanoi         | [CSES - Tower of Hanoi](https://cses.fi/problemset/task/2165)       |
| 8  | Coin Piles             | [CSES - Coin Piles](https://cses.fi/problemset/task/1754)           |
| 9  | Walking Master         | [CSES - Grid Paths](https://cses.fi/problemset/task/1625)           |
| 10 | Two Knights            | [CSES - Two Knights](https://cses.fi/problemset/task/1072)          |


### Additional Problems

| #  | Problem Description                                         | Platform/Link                                                                                  |
|----|-------------------------------------------------------------|------------------------------------------------------------------------------------------------|
| 1  | Longest Subarray with Given Sum K (Positive integers only) | [GeeksforGeeks - Longest Subarray Sum K](https://practice.geeksforgeeks.org/problems/longest-sub-array-with-sum-k0809/1) |
| 2  | Longest Subarray with Sum K (Positives + Negatives)        | [GFG - Longest Subarray Sum with Pos/Neg](https://www.geeksforgeeks.org/longest-sub-array-sum-k/) |
| 3  | Majority Element (> n/2 times)                              | [LeetCode - Majority Element](https://leetcode.com/problems/majority-element/)                |
| 4  | Maximum Subarray Sum (Kadane's Algorithm)                  | [LeetCode - Maximum Subarray](https://leetcode.com/problems/maximum-subarray/)               |
| 5  | Hotel Bookings Possible                                     | [CodeChef - HOTEL](https://www.codechef.com/practice/course/2-star-difficulty-problems/DIFF1500/problems/HOTEL) |
| 6  | Array Halves                                                | [CodeChef - ARRHALVES](https://www.codechef.com/practice/course/2-star-difficulty-problems/DIFF1500/problems/ARRHALVES) |


# Week 2:(26 May - 2 June)

| #  | Problem Title                | Link                                                                 |
|----|------------------------------|----------------------------------------------------------------------|
| 1  | Distinct Values Subsequences | [CSES - Distinct Values Subsequences](https://cses.fi/problemset/task/1734) |
| 2  | Josephus Problem II          | [CSES - Josephus Problem II](https://cses.fi/problemset/task/2163)  |
| 3  | Nested Ranges Check          | [CSES - Nested Ranges Check](https://cses.fi/problemset/task/2168)  |
| 4  | Room Allocation              | [CSES - Room Allocation](https://cses.fi/problemset/task/1164)      |
| 5  | Factory Machines             | [CSES - Factory Machines](https://cses.fi/problemset/task/1620)     |
| 6  | Sum of Three Values          | [CSES - Sum of Three Values](https://cses.fi/problemset/task/1641)  |
| 7  | Odd Queries                  | [Codeforces - Odd Queries](https://codeforces.com/problemset/problem/1807/D) |
| 8  | Mainak and Array             | [Codeforces - Mainak and Array](https://codeforces.com/problemset/problem/1349/A) |
| 9  | AvtoBus                      | [Codeforces - AvtoBus](https://codeforces.com/problemset/problem/1051/B) |
| 10 | Make It Increasing           | [Codeforces - Make It Increasing](https://codeforces.com/problemset/problem/1675/D) |

# Week 3: (2 June - 9 June)

| #  | Problem Title                                        | Link                                                                                     |
|----|------------------------------------------------------|------------------------------------------------------------------------------------------|
| 1  | Binary Search to find X in sorted array              | [GFG - Binary Search](https://www.geeksforgeeks.org/binary-search/)                     |
| 2  | Count occurrences of a number in a sorted array      | [GFG - Count Occurrences](https://www.geeksforgeeks.org/count-number-of-occurrences-or-frequency-in-a-sorted-array/) |
| 3  | Search in Rotated Sorted Array I                     | [LeetCode - Problem 33](https://leetcode.com/problems/search-in-rotated-sorted-array/)  |
| 4  | Search in Rotated Sorted Array II                    | [LeetCode - Problem 81](https://leetcode.com/problems/search-in-rotated-sorted-array-ii/) |
| 5  | Find minimum in Rotated Sorted Array                 | [LeetCode - Problem 153](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) |
| 6  | Find how many times the array has been rotated       | [GFG - Rotation Count](https://www.geeksforgeeks.org/find-rotation-count-rotated-sorted-array/) |
| 7  | Single element in a Sorted Array                     | [LeetCode - Problem 540](https://leetcode.com/problems/single-element-in-a-sorted-array/) |
| 8  | Find peak element                                    | [LeetCode - Problem 162](https://leetcode.com/problems/find-peak-element/)              |
| 9  | Find the Nth root of a number using binary search    | [GFG - Nth Root](https://www.geeksforgeeks.org/find-nth-root-number-using-binary-search/) |
| 10 | Koko Eating Bananas                                  | [LeetCode - Problem 875](https://leetcode.com/problems/koko-eating-bananas/)            |


# Week 4: (9 June - 16 June)

| #  | Problem Title                                        | Link                                                                                     |
|----|------------------------------------------------------|------------------------------------------------------------------------------------------|
| 1  | Minimum days to make M bouquets                      | [LeetCode - Problem 1482](https://leetcode.com/problems/minimum-number-of-days-to-make-m-bouquets/) |
| 2  | Find the smallest Divisor                            | [LeetCode - Problem 1283](https://leetcode.com/problems/find-the-smallest-divisor-given-a-threshold/) |
| 3  | Capacity to Ship Packages within D Days              | [LeetCode - Problem 1011](https://leetcode.com/problems/capacity-to-ship-packages-within-d-days/) |
| 4  | Kth Missing Positive Number                          | [LeetCode - Problem 1539](https://leetcode.com/problems/kth-missing-positive-number/)   |
| 5  | Aggressive Cows                                      | [GFG - Aggressive Cows](https://www.geeksforgeeks.org/aggressive-cows-dynamic-programming-solution/) |
| 6  | Book Allocation Problem                              | [GFG - Book Allocation](https://www.geeksforgeeks.org/allocate-minimum-number-pages/)    |
| 7  | Split Array - Largest Sum                            | [LeetCode - Problem 410](https://leetcode.com/problems/split-array-largest-sum/)         |
| 8  | Painter's Partition Problem                          | [GFG - Painter's Partition](https://www.geeksforgeeks.org/painters-partition-problem/)   |
| 9  | Minimize Max Distance to Gas Station                 | [LeetCode - Problem 774](https://leetcode.com/problems/minimize-max-distance-to-gas-station/) |
| 10 | Median of Two Sorted Arrays                          | [LeetCode - Problem 4](https://leetcode.com/problems/median-of-two-sorted-arrays/)       |


# Week 5: (16 June - 23 June)

| #  | Problem Title                                             | Link                                                                                   |
|----|-----------------------------------------------------------|----------------------------------------------------------------------------------------|
| 1  | Remove Outermost Parentheses                              | [LeetCode - Problem 1021](https://leetcode.com/problems/remove-outermost-parentheses/) |
| 2  | Reverse Words in a String                                 | [LeetCode - Problem 151](https://leetcode.com/problems/reverse-words-in-a-string/)     |
| 3  | Largest Odd Number in a String                            | [LeetCode - Problem 1903](https://leetcode.com/problems/largest-odd-number-in-string/) |
| 4  | Longest Common Prefix                                     | [LeetCode - Problem 14](https://leetcode.com/problems/longest-common-prefix/)          |
| 5  | Isomorphic Strings                                        | [LeetCode - Problem 205](https://leetcode.com/problems/isomorphic-strings/)            |
| 6  | Check if one string is a rotation of another              | [GFG - String Rotation](https://www.geeksforgeeks.org/check-if-a-string-is-rotation-of-another-string/) |
| 7  | Check if Two Strings are Anagrams                         | [LeetCode - Problem 242](https://leetcode.com/problems/valid-anagram/)                 |
| 8  | Sort Characters by Frequency                              | [LeetCode - Problem 451](https://leetcode.com/problems/sort-characters-by-frequency/)  |
| 9  | Longest Palindromic Substring (without DP)                | [LeetCode - Problem 5](https://leetcode.com/problems/longest-palindromic-substring/)   |
| 10 | Roman Number to Integer and vice versa                    | [LeetCode - Problem 13](https://leetcode.com/problems/roman-to-integer/)               |

# Week 6: (23 June - 30 June)

| #  | Problem Title                             | Link                                                                                      |
|----|-----------------------------------------|-------------------------------------------------------------------------------------------|
| 1  | Generate All Binary Strings              | [GeeksforGeeks - Generate Binary Strings](https://practice.geeksforgeeks.org/problems/generate-all-binary-strings/1) |
| 2  | Generate Parentheses                     | [LeetCode - Problem 22](https://leetcode.com/problems/generate-parentheses/)               |
| 3  | Print All Subsequences / Power Set      | [GeeksforGeeks - Print Subsequences](https://practice.geeksforgeeks.org/problems/power-set4302/1) |
| 4  | Combination Sum III                     | [LeetCode - Problem 216](https://leetcode.com/problems/combination-sum-iii/)               |
| 5  | Count All Subsequences with Sum K       | [GeeksforGeeks - Count Subsequences with Sum K](https://practice.geeksforgeeks.org/problems/count-subsequences-with-sum-k/0) |
| 6  | Check if There Exists a Subsequence with Sum K | [GeeksforGeeks - Subsequence with Sum K](https://practice.geeksforgeeks.org/problems/subsequence-with-sum-k/0) |
| 7  | Combination Sum                         | [LeetCode - Problem 39](https://leetcode.com/problems/combination-sum/)                    |
| 8  | Combination Sum II                      | [LeetCode - Problem 40](https://leetcode.com/problems/combination-sum-ii/)                 |
| 9  | Subset Sum I                           | [GeeksforGeeks - Subset Sum Problem](https://practice.geeksforgeeks.org/problems/subset-sum-problem-1611555638/1) |
| 10 | Subset Sum II                          | [GeeksforGeeks - Subset Sum II](https://practice.geeksforgeeks.org/problems/subset-sum-ii/0) |


