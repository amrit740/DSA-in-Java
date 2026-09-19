# DSA-in-Java
A complete collection of Data Structures and Algorithms problems and solutions in Java.
# 🧠 Data Structures & Algorithms in Java

A structured collection of **Data Structures and Algorithms
problems and solutions implemented in Java**, designed to
strengthen problem-solving skills and prepare for technical
interviews.

---

## 📚 Topics Covered

| # | Topic | Status |
|---|---|---|
| 1 | Arrays | 🔄 In Progress |
| 2 | Strings | 🔄 In Progress |
| 3 | Searching Algorithms | 🔄 In Progress |
| 4 | Sorting Algorithms | 🔄 In Progress |
| 5 | Recursion | 🔄 In Progress |
| 6 | Linked Lists | 🔄 In Progress |
| 7 | Stacks | 🔄 In Progress |
| 8 | Queues | 🔄 In Progress |
| 9 | Trees | 🔄 In Progress |
| 10 | Graphs | 🔄 In Progress |
| 11 | Greedy Algorithms | 🔄 In Progress |
| 12 | Dynamic Programming | 🔄 In Progress |

---

## 🗂️ Repository Structure

```text
DSA-in-Java/
│
├── Arrays/
├── Strings/
├── Searching/
├── Sorting/
├── Recursion/
├── LinkedList/
├── Stack/
├── Queue/
├── Trees/
├── Graphs/
├── Greedy/
├── DynamicProgramming/
└── README.md
```

---

## 💻 Example Problem

### 🔹 Binary Search

**Problem:** Find an element in a sorted array.

```java
public class BinarySearch {

    public static int search(int[] arr, int target) {
        int left = 0;
        int right = arr.length - 1;

        while (left <= right) {
            int mid = left + (right - left) / 2;

            if (arr[mid] == target) {
                return mid;
            } else if (arr[mid] < target) {
                left = mid + 1;
            } else {
                right = mid - 1;
            }
        }

        return -1;
    }
}
```

---

## 🎯 Objectives

- Improve problem-solving skills
- Master core data structures
- Understand algorithm complexity
- Prepare for coding interviews
- Practice writing clean and efficient Java code

---

## 🛠️ Technologies Used

- Java
- Object-Oriented Programming
- Data Structures & Algorithms

---

## 📈 Learning Progress

This repository is continuously updated with new
problems, solutions, and explanations.

---

## 🤝 Contributions

Suggestions and improvements are welcome!

---

⭐ If you find this repository useful, consider starring it.