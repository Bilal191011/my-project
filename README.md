# CPS 350 — Assignment 1: Linked Lists (SLL & DLL)

**Goal:** Implement `SinglyLinkedList<T>` and `DoublyLinkedList<T>` with the required operations and complexities.

## Required Operations

For both SLL and DLL:

- `void addFirst(T x)` — O(1)
- `void addLast(T x)` — O(1) for DLL; O(n) for SLL unless you maintain a tail (optional)
- `T removeFirst()` — O(1), throws if empty
- `T removeLast()` — O(1) for DLL; O(n) for SLL (or O(1) with tail+prev in DLL)
- `boolean remove(T x)` — remove first occurrence; O(n)
- `boolean contains(T x)` — O(n)
- `int size()` — O(1) if you track size (required)
- `T get(int k)` — O(n)
- `void clear()` — O(1)
- `Iterator<T> iterator()` — forward iteration
- DLL additionally: `ListIterator<T> listIterator()` with bidirectional iteration

## Correctness & Complexity
- Do **not** use `java.util.LinkedList`.
- Maintain invariants: head/tail correctness, size tracking, and null-safe behavior.
- Throw `NoSuchElementException` where appropriate.

## How you’ll be graded
- **Before deadline:** “Basic” tests run on every push (green check in GitHub).
- **After deadline:** “Final” test suite (stricter, larger, randomized) runs automatically via the course workflow.
- You’ll see test results in the _Actions_ tab and on the Classroom dashboard.

## What to submit
- Commit and push your code to the `main` branch. No PR required.
- Keep package names unchanged.

## Local dev
`mvn -q -DskipTests=false test`


## Academic Integrity
Do your own work; follow UD policies.


