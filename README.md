\# Sorting Algorithms — Bubble Sort \& Merge Sort



This repository contains \*\*educational implementations\*\* of two classic sorting algorithms:



\- \*\*Bubble Sort\*\*

\- \*\*Merge Sort\*\*



The goal of this project is \*\*understanding algorithmic logic\*\*, not performance optimization or use of built-in methods.



---



\## 📌 Why this repository exists



Sorting algorithms are often memorized or copied without real comprehension.

This project was created to:



\- understand \*how\* and \*why\* sorting algorithms work,

\- clearly see the difference between \*\*iterative\*\* and \*\*recursive\*\* thinking,

\- practice translating algorithmic ideas into clean Python code.



No shortcuts were taken — no `sorted()` and no `.sort()`.



---



\## 🫧 Bubble Sort



Bubble Sort is an \*\*iterative, in-place\*\* algorithm that works by repeatedly comparing \*\*neighboring elements\*\* and swapping them if they are in the wrong order.



Key characteristics:

\- compares adjacent elements (`i` and `i+1`)

\- pushes the largest values to the end step by step

\- simple to understand, inefficient for large datasets

\- time complexity: \*\*O(n²)\*\*



The implementation prints the list after each pass to make the algorithm’s behavior explicit and observable.



---



\## 🧩 Merge Sort



Merge Sort is a \*\*recursive, divide-and-conquer\*\* algorithm.



The list is:

1\. divided into halves until single-element lists are reached,

2\. then merged back together in sorted order.



Important ideas:

\- sorting happens \*\*only during merging\*\*

\- each recursive call works on its own sublist

\- the algorithm never sorts “in place”

\- time complexity: \*\*O(n log n)\*\*



The implementation is split into:

\- `merge()` — responsible only for merging two already sorted lists

\- `merge\_sorting()` — responsible for dividing the list and coordinating recursion



---



\## 🧠 What this project demonstrates



\- the conceptual difference between \*\*local fixes\*\* (Bubble Sort) and \*\*global structure rebuilding\*\* (Merge Sort),

\- how recursion works in practice,

\- how algorithmic ideas translate into readable Python code.



This repository is intentionally educational rather than optimized.

