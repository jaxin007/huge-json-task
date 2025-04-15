# ✅ JSON Validation Task (Senior Node.js Live Coding)

## 🧠 Task Summary

You are given a large JSON file (`huge_100mb.json`, ~100MB, 162k+ entries) stored as a string or read from disk.

### 🎯 Goal:
Implement an efficient solution to check whether the file content is valid JSON.

---

## 📌 Requirements

- ✅ You **must not** use `JSON.parse()` directly on the entire string.
- ✅ Use a **streaming approach** to avoid blocking the event loop or crashing the process.
- ✅ Your solution should return `true` if the JSON is valid, and `false` otherwise.

### Bonus (Optional)
- Report whether the root is an **array** or **object**
- Handle malformed JSON and return a helpful error message
- Support both string input and file stream input

---

## 🧪 Example

```ts
const isValid = await isValidJsonFile('./huge_100mb.json')
console.log(isValid) // true
