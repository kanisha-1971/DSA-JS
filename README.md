# DSA-JS

# 📚 Big O Notation Explained with JavaScript Examples

Understanding how your code performs as data grows is essential for efficient programming. Big O Notation gives us a way to classify algorithms based on their efficiency and scalability. In this guide, we’ll explore key time complexities and use JavaScript examples to bring each one to life.

---

## 📖 Table of Contents
1. [What is Big O Notation?](#what-is-big-o-notation)
2. [Common Time Complexities](#common-time-complexities)
   - [Constant Time - O(1)](#constant-time---o1)
   - [Linear Time - O(n)](#linear-time---on)
   - [Quadratic Time - O(n²)](#quadratic-time---on²)
   - [Logarithmic Time - O(log n)](#logarithmic-time---olog-n)
3. [Conclusion](#conclusion)
4. [Further Reading](#further-reading)

---

## What is Big O Notation?

**Big O Notation** is a mathematical way to measure an algorithm's efficiency, especially in terms of its execution time as input grows. It lets us compare and predict how fast or slow an algorithm will be, which is critical for optimizing programs to handle large datasets.

---

## Common Time Complexities

### 1. Constant Time - O(1)

In constant time, the execution duration stays the same regardless of the input size. It’s like picking the first item in a list — it’s instant, no matter how many items there are.

#### Example:

```javascript
function getFirstElement(arr) {
  return arr[0]; // Accessing the first element takes the same time, no matter the array size.
}

const candies = ["chocolate", "gum", "lollipop"];
console.log(getFirstElement(candies)); // Output: "chocolate"
