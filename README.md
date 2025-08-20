# Typing Speed Test  

This is a small project I built to practice JavaScript and improve my typing skills at the same time. It’s a simple typing speed test that shows a random quote, highlights your input in real time, and keeps track of how long you take to finish.  

At first, the app pulled quotes from the **Quotable API**, but since that service isn’t being hosted anymore, I switched it over to use a set of local quotes stored in the project. I left the code flexible so it can easily be swapped back to an API in the future.  

---

# What it does
- Shows a random quote for you to type  
- Highlights each character green (correct) or red (incorrect) as you type  
- Starts a timer automatically when you begin typing  
- Loads a new quote automatically when the current one is typed correctly  

---

# How I built it
- **HTML/CSS** for the layout and basic styling  
- **JavaScript** for all the logic (input handling, timer, validation, etc.)  
- Originally used an external API for quotes, now uses a local array  

---

# My Coding Timeline
I’ve been consistently building projects and improving my skills since high school. Here’s a quick snapshot of where I was at different times:  

- **Feb 2022** → Grade 9, Semester 2 (just starting out, experimenting with code)  
- **2022–23** → Grade 10 (working on small side projects, building fundamentals)  
- **2023–24** → Grade 11 (developing larger projects, more structured learning)  
- **2024–25** → Grade 12 (final year of high school, refining portfolio projects)  
- **Summer 2025** → Preparing to enter university with a portfolio of personal coding projects  

---

# What I learned
- How to work with **event listeners** to track user input  
- Handling **timing functions** with `setInterval`  
- Managing **DOM updates** efficiently (highlighting characters on the fly)  
- How to handle cases where an API becomes unavailable and still keep the app working  

---

# Things I want to add next
- Words per minute (WPM) calculation  
- Accuracy percentage  
- Saving best times in `localStorage`  
- Cleaner UI and mobile-friendly layout  

---

# Project Structure
typing-speed-test/
│── index.html # Main page
│── style.css # Styling
│── script.js # Main app logic
│── README.md # Documentation


---

# Getting Started
1. Clone this repository or download the files.  
2. Open `index.html` in your browser.  
3. Start typing in the text box and the timer will begin automatically.  

Optional: Modify `script.js` to adjust the quotes list or re-enable API fetching if you want to use an external service.  

---

# Final note
This started as a fun way to mix coding practice with something interactive. It’s a small project, but it helped me strengthen my JavaScript fundamentals and get more comfortable with asynchronous code and DOM manipulation.  

