# C++ Data Structures & Algorithms Portfolio

This repository tracks my solutions, patterns, and time/space complexity analyses as I build competitive programming proficiency in C++.

## Progress Tracker

| # | Title | Pattern | Time | Space | Solution |
|---|---|---|---|---|---|
| 0027 | Remove Element | Two Pointers (Read/Write) | $\mathcal{O}(N)$ | $\mathcal{O}(1)$ | [C++](./Easy/0027-remove-element/solution.cpp) |
| 0026 | Remove Duplicates from Sorted Array | Two Pointers (Read/Write) | $\mathcal{O}(N)$ | $\mathcal{O}(1)$ | [C++](./Easy/0026-remove-duplicates-from-sorted-array/solution.cpp) |
| 0125 | Valid Palindrome | Two Pointers (Opposite Ends) | $\mathcal{O}(N)$ | $\mathcal{O}(1)$ | [C++](./Easy/0125-valid-palindrome/solution.cpp) |
| 0392 | Is Subsequence | Two Pointers (Two Strings) | $\mathcal{O}(N)$ | $\mathcal{O}(1)$ | [C++](./Easy/0392-is-subsequence/solution.cpp) |
| 0001 | Two Sum | Hash Map (`std::unordered_map`) | $\mathcal{O}(N)$ | $\mathcal{O}(N)$ | *In Progress* |

---

## Pattern Cheat Sheet

### 1. Two Pointers (Read / Write)
Used for in-place array/string modification without allocating auxiliary arrays.
* **Read Pointer (`i`):** Scans every element from index `0` to `n - 1`.
* **Write Pointer (`k`):** Maintains the boundary of valid output.
* **Key Invariant:** `k <= i` ensures unread data is never overwritten.
