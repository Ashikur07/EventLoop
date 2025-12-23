# 🔄 Event Loop in JavaScript  
### Web APIs | Callback Queue | Microtask Queue 🔥  
**Namaste JavaScript – Episode 15**

This repository is created while learning **JavaScript Event Loop & Asynchronous Behavior** from  
🎥 **Namaste JavaScript – Episode 15** by **Akshay Saini**.

> 📚 Learning Source:  
> https://www.youtube.com/watch?v=8aGhZQkoFbQ

---

## 📖 What This Repository Covers

In this repository, I’m learning and practicing:

- ✅ How **JavaScript Engine** executes code  
- ✅ Role of the **Call Stack**  
- ✅ How JavaScript handles **Asynchronous tasks**  
- ✅ **Web APIs** (setTimeout, fetch, DOM Events)  
- ✅ **Event Loop** and its responsibility  
- ✅ **Callback Queue vs Microtask Queue**  
- ✅ How **fetch() & Promises** work internally  
- ✅ **Starvation** in Callback Queue  

---

## 🧠 Core Concepts Explained

### 📌 Call Stack
The Call Stack keeps track of function execution in JavaScript.

```js
function one() {
  two();
}

function two() {
  console.log("Hello Event Loop");
}

one();
