# string-dsa-python
# String DSA in Python

A structured collection of **String Data Structures and Algorithms (DSA)** problems and solutions implemented in **Python**.

This repository is designed for learning, interview preparation, and improving problem-solving skills through progressively challenging string-based problems.

## 📌 Topics Covered

* String Basics
* String Traversal
* String Manipulation
* Character Frequency
* Anagrams
* Palindromes
* Substrings and Subsequences
* String Searching
* Pattern Matching
* Two Pointer Technique
* Sliding Window
* Hashing
* Stack-Based String Problems
* Sorting-Based String Problems
* Regular Expressions
* Advanced String Algorithms

## 📂 Repository Structure

```text
string-dsa-python/
│
├── README.md
│
├── basics/
│   ├── reverse_string.py
│   ├── count_characters.py
│   └── remove_spaces.py
│
├── frequency/
│   ├── character_frequency.py
│   └── first_non_repeating_character.py
│
├── palindrome/
│   ├── palindrome_check.py
│   └── longest_palindromic_substring.py
│
├── anagram/
│   ├── valid_anagram.py
│   └── group_anagrams.py
│
├── substring/
│   ├── longest_substring.py
│   └── substring_search.py
│
├── sliding_window/
│   ├── longest_unique_substring.py
│   └── minimum_window_substring.py
│
├── two_pointer/
│   ├── reverse_vowels.py
│   └── valid_palindrome.py
│
└── advanced/
    ├── pattern_matching.py
    └── string_algorithms.py
```

> The folder structure can be expanded as more problems are added.

## 🎯 Goals

The main goals of this repository are to:

* Build strong fundamentals in string manipulation.
* Understand common DSA patterns.
* Practice writing clean and efficient Python code.
* Improve time and space complexity analysis.
* Prepare for coding interviews and competitive programming.
* Maintain a well-organized collection of solved problems.

## 🧠 Problem-Solving Approach

Each problem aims to include:

1. **Problem Statement**
2. **Approach / Intuition**
3. **Python Implementation**
4. **Time Complexity**
5. **Space Complexity**
6. **Example / Test Cases**, where useful

Example:

```python
def is_palindrome(s: str) -> bool:
    left, right = 0, len(s) - 1

    while left < right:
        if s[left] != s[right]:
            return False

        left += 1
        right -= 1

    return True
```

### Complexity

* **Time:** `O(n)`
* **Space:** `O(1)`

## 📈 Difficulty Levels

Problems can be organized according to difficulty:

| Level     | Description                          |
| --------- | ------------------------------------ |
| 🟢 Easy   | Fundamental string concepts          |
| 🟡 Medium | Common interview patterns            |
| 🔴 Hard   | Advanced algorithms and optimization |

## 🛠️ Tech Stack

* **Language:** Python 3
* **Concepts:** Data Structures & Algorithms
* **Testing:** Python `unittest` / `pytest` (as applicable)

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/<your-username>/string-dsa-python.git
```

Navigate to the project:

```bash
cd string-dsa-python
```

Run a solution:

```bash
python basics/reverse_string.py
```

## 📚 Recommended Learning Path

For a systematic approach, follow this order:

```text
String Fundamentals
        ↓
Traversal & Manipulation
        ↓
Frequency Counting
        ↓
Palindrome & Anagram Problems
        ↓
Two Pointers
        ↓
Sliding Window
        ↓
Hashing
        ↓
Substring Problems
        ↓
Pattern Matching
        ↓
Advanced String Algorithms
```

## 🤝 Contributing

Contributions are welcome!

If you would like to contribute:

1. Fork the repository.
2. Create a new branch.

```bash
git checkout -b feature/add-string-problem
```

3. Add your solution with a clear explanation.
4. Test your implementation.
5. Commit your changes.

```bash
git commit -m "Add solution for longest substring problem"
```

6. Push the branch.

```bash
git push origin feature/add-string-problem
```

7. Open a Pull Request.

## 📝 Code Guidelines

Please follow these guidelines when adding solutions:

* Use **Python 3**.
* Follow **PEP 8** where practical.
* Use meaningful variable and function names.
* Include type hints when appropriate.
* Avoid unnecessary complexity.
* Mention time and space complexity.
* Keep each problem focused on a single concept.
* Add test cases for non-trivial solutions.

## 📊 Progress Tracker

| Topic               | Progress |
| ------------------- | -------: |
| String Basics       |        ⬜ |
| Frequency           |        ⬜ |
| Palindrome          |        ⬜ |
| Anagram             |        ⬜ |
| Two Pointers        |        ⬜ |
| Sliding Window      |        ⬜ |
| Hashing             |        ⬜ |
| Substrings          |        ⬜ |
| Pattern Matching    |        ⬜ |
| Advanced Algorithms |        ⬜ |

Update the tracker as problems are completed.

## ⭐ Why This Repository?

String problems are among the most common DSA questions in coding interviews. This repository focuses on understanding **patterns and problem-solving techniques**, rather than simply collecting solutions.

The goal is to make each solution easy to understand, analyze, and revisit.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Happy Coding! 🐍**
