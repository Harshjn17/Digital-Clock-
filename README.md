⏰ Digital Clock

A simple digital clock built using HTML, CSS, and JavaScript that displays the current time in real-time.

---

🚀 Features

- Displays current time (hours, minutes, seconds)
- Updates every second
- Clean and minimal UI
- Beginner-friendly project

---

🛠️ Technologies Used

- HTML
- CSS
- JavaScript

---

📂 Project Structure

digital-clock/
│── index.html
│── style.css
│── script.js

---

⚙️ How It Works

- JavaScript uses the built-in "Date" object to get current time.
- "setInterval()" updates the clock every second.
- Time is formatted and displayed inside the DOM.

---

▶️ How to Run

1. Download or clone the project
2. Open "index.html" in your browser
3. The clock will start automatically

---

💡 Example Logic

- Get current time:

let now = new Date();

- Extract values:

let hours = now.getHours();
let minutes = now.getMinutes();
let seconds = now.getSeconds();

- Update every second:

setInterval(updateClock, 1000);

---

🔧 Possible Improvements

- Add AM/PM format
- Add date display
- Add dark/light mode
- Add timezone support
- Add alarm feature

---

📌 Learning Outcome

This project helps you understand:

- DOM manipulation
- Time-based functions ("setInterval")
- Working with real-time data
- Structuring small JavaScript projects

---

📜 License

This project is open-source and free to use.

---
