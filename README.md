# Simple-Calculator
Python, HTML/CSS
________________________________________
🧮 Simple Calculator — Python Flask + HTML
📌 Project Overview
This is a basic web-based calculator built using Python (Flask framework) for the backend and HTML/CSS for the frontend. It allows users to perform four fundamental arithmetic operations: addition, subtraction, multiplication, and division.
________________________________________
🎯 Features
•	Input two numbers and select an operation.
•	Perform +, −, ×, or ÷.
•	Displays result instantly after submitting.
•	Clean, real calculator-style UI using CSS.
•	Input validation and zero-division error handling.
________________________________________
🗂️ Project Structure
calculator/
├── app.py                  # Flask backend logic
└── templates/
    └── index.html          # Frontend UI (calculator interface)
________________________________________
⚙️ Technologies Used
Component	Tool
Backend	Python (Flask)
Frontend	HTML, CSS
Web Framework	Flask
________________________________________
▶️ How to Run
1.	Install Flask:
2.	pip install flask
3.	Run the app:
4.	python app.py
5.	Open your browser and visit:
http://localhost:5000
________________________________________
📄 Code Highlights
app.py
•	Receives form inputs via POST request.
•	Handles basic math operations.
•	Returns result to the frontend for display.
index.html
•	Uses <form> to collect user input.
•	Styled like a real calculator with CSS grid.
•	Dynamically displays the result using Flask's Jinja2 templating.
________________________________________
🔐 Validations
•	Converts inputs to float.
•	Catches invalid inputs.
•	Prevents divide-by-zero errors with a message.
________________________________________
🚀 Future Enhancements (Optional)
•	Add keyboard support
•	Add advanced functions (%, √, memory)
•	Enable history of calculations
•	Add dark/light mode toggle
________________________________________
👨‍💻 Author
Created by Pavan Kalyan as a basic Python web development project with real-time computation using Flask and a styled UI.
________________________________________
