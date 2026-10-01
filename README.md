# HackerRank 3rd Semester Algorithm Portfolio

## Student Details

* **Name:** Dhanushree A R
* **USN / Student ID:** R25EF074
* **Semester:** 3rd Semester
* **Programming Language:** C
* **HackerRank Profile:** https://www.hackerrank.com/profile/d41959509
* **GitHub Repository:** https://github.com/Dhanushree12340/HackerRank-3rdSem-Algorithm-Portfolio

## About This Portfolio

This repository contains my solutions to the five mandatory algorithmic problems completed as part of the 3rd Semester HackerRank Algorithms activity. The problems cover arrays, implementation, sorting, searching, and greedy algorithm techniques.

Each solution is written in C and is organized in a separate folder. The repository also documents the approach, time complexity, and auxiliary space complexity for each problem.

## Problems Completed

| No. | Problem                 | Topic                   | Time Complexity | Auxiliary Space |
| --- | ----------------------- | ----------------------- | --------------- | --------------- |
| 1   | Mini-Max Sum            | Arrays / Implementation | O(N)            | O(1)            |
| 2   | Birthday Cake Candles   | Arrays / Counting       | O(N)            | O(1)            |
| 3   | Insertion Sort – Part 1 | Sorting                 | O(N)            | O(1)            |
| 4   | Binary Search           | Searching               | O(log N)        | O(1)            |
| 5   | Mark and Toys           | Greedy / Sorting        | O(N log N)      | O(N)            |

## 1. Mini-Max Sum

### Approach

The program calculates the total sum of all five numbers while tracking the minimum and maximum values. The minimum sum is obtained by excluding the maximum value, while the maximum sum is obtained by excluding the minimum value.

### Complexity

* **Time Complexity:** O(N)
* **Auxiliary Space:** O(1)

### HackerRank

* **Challenge:** Mini-Max Sum
* **Accepted Submission:** YOUR_SUBMISSION_LINK

---

## 2. Birthday Cake Candles

### Approach

The program traverses the array and finds the maximum candle height. It then counts how many candles have the maximum height.

### Complexity

* **Time Complexity:** O(N)
* **Auxiliary Space:** O(1)

### HackerRank

* **Challenge:** Birthday Cake Candles
* **Accepted Submission:** YOUR_SUBMISSION_LINK

---

## 3. Insertion Sort – Part 1

### Approach

The last element is stored as the value to be inserted. Larger elements are shifted one position to the right until the correct position for the value is found. The value is then inserted into that position.

### Complexity

* **Time Complexity:** O(N)
* **Auxiliary Space:** O(1)

### HackerRank

* **Challenge:** Insertion Sort – Part 1
* **Accepted Submission:** YOUR_SUBMISSION_LINK

---

## 4. Binary Search

### Approach

Binary search is performed on a sorted array. The middle element is compared with the target. If the target is larger, the left half is discarded; if it is smaller, the right half is discarded. This process continues until the target is found or the search range becomes empty.

### Complexity

* **Time Complexity:** O(log N)
* **Auxiliary Space:** O(1)

### HackerRank / Coding Evidence

* **Challenge / Platform:** YOUR_CHALLENGE_LINK
* **Accepted Submission / Evidence:** YOUR_SUBMISSION_LINK

---

## 5. Mark and Toys

### Approach

The toy prices are sorted in ascending order. The cheapest toys are purchased first while the total cost remains within the available budget. This greedy strategy maximizes the number of toys purchased.

### Complexity

* **Time Complexity:** O(N log N)
* **Auxiliary Space:** O(N)

### HackerRank

* **Challenge:** Mark and Toys
* **Accepted Submission:** YOUR_SUBMISSION_LINK

---

## Algorithm Techniques Learned

Through these problems, I practiced several important algorithmic techniques:

* Array traversal
* Minimum and maximum tracking
* Counting
* Insertion sorting
* Binary search
* Sorting
* Greedy algorithm
* Time and space complexity analysis

## Reflection

This activity helped me improve my understanding of fundamental algorithmic problem solving. I learned how to analyze a problem before selecting an appropriate algorithm and how different approaches affect time and space complexity. Mini-Max Sum and Birthday Cake Candles helped me practice efficient array traversal and tracking values without unnecessary operations. Insertion Sort – Part 1 helped me understand how elements can be shifted to maintain sorted order. Binary Search showed how a sorted array can be searched efficiently by repeatedly reducing the search space. Mark and Toys introduced the greedy approach, where sorting the prices allows the cheapest available items to be selected first within a fixed budget. I also learned the importance of documenting algorithms using Big-O notation and organizing solutions clearly in a GitHub repository. Completing the HackerRank problems and maintaining their solutions in GitHub gave me practical experience in coding, version control, documentation, and algorithm analysis.

## Evidence

### HackerRank Profile

YOUR_HACKERRANK_PROFILE_URL

### GitHub Repository

YOUR_GITHUB_REPOSITORY_URL

### Accepted Submission Screenshots

Screenshots of the accepted HackerRank submissions are included as evidence of completion.

### HackerRank Badge

Badge evidence will be added here if earned.

## Repository Structure

```text
HackerRank-3rdSem-Algorithm-Portfolio/
│
├── README.md
│
├── 01-Mini-Max-Sum/
│   └── solution.c
│
├── 02-Birthday-Cake-Candles/
│   └── solution.c
│
├── 03-Insertion-Sort-Part-1/
│   └── solution.c
│
├── 04-Binary-Search/
│   └── solution.c
│
└── 05-Mark-and-Toys/
    └── solution.c
```

## Conclusion

This portfolio demonstrates my implementation and analysis of five fundamental algorithmic problems using C. It provides evidence of my HackerRank problem-solving practice and organizes the solutions in a structured GitHub repository.
