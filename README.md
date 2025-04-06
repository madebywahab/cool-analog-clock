# 🕰️ Cool Analog Clock

## 🔗 Live Link  
👉 [Click here to view the clock in action!](https://madebywahab.github.io/cool-analog-clock/)

---

## 📚 Explanation  

This is a simple yet functional **analog clock** built with HTML, CSS, and JavaScript. Here's a breakdown of how it works:

- 🔧 **Element Selection**  
  I started by storing the DOM elements (using their `id`s) into variables for easier manipulation.

- ⏱️ **Real-Time Update**  
  A `setInterval()` function runs every **1 second** to continuously update the clock.

- 🕒 **Fetching Time**  
  Inside the interval function:
  - I use `new Date()` to fetch the current system time.
  - Extract **seconds**, **minutes**, and **hours** from it.
  - Store them in variables for further use.

- 📐 **Time to Degrees Conversion**  
  To rotate the clock hands:
  - A full circle = **360 degrees**
  - There are 60 seconds/minutes → **6 degrees per second/minute** (360 / 60)
  - 12 hours on the clock → **30 degrees per hour** (360 / 12)

- 🧪 **Debugging Tip**  
  You can open the browser **console** to see the values and how the clock updates in real-time.

---

Let me know if you'd like to add images, code snippets, or even a GIF of the clock in action!
