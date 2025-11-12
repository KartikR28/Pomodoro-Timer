# Pomodoro-Timer
⏰ Pomodoro Timer (Python + Tkinter)
A simple Pomodoro Timer built with Python’s tkinter GUI library.
 This app helps you manage focused work sessions and breaks using the classic Pomodoro Technique — 25 minutes of work followed by short breaks, with a longer break after several cycles.

🧠 What is the Pomodoro Technique?
The Pomodoro Technique is a time management method developed by Francesco Cirillo.
 It uses a timer to break work into focused intervals (traditionally 25 minutes), separated by short breaks.
Cycle overview:
🕐 25 min Work

☕ 5 min Short Break

🌴 20 min Long Break (after 4 work sessions)


🖥️ Features
✅ Simple and elegant UI using Tkinter
 ✅ Countdown timer with minutes and seconds display
 ✅ Automatically switches between work and break sessions
 ✅ Visual label updates for "Work" / "Break" sessions
 ✅ Easily customizable timer durations

🧩 Tech Stack
Language: Python 3.x

GUI Framework: Tkinter

Math Module: Used for formatting the countdown


🚀 How to Run
Clone this repository:

 
Make sure you have Python installed (3.10 or higher):

 python --version

Run the app:

 python main.py

Ensure you have the tomato image in the same directory:

 pomodoro-timer/
├── main.py
└── tomato.png


📸 Screenshot




⚙️ Customization
You can change session durations by modifying these constants at the top of main.py:
WORK_MIN = 25
SHORT_BREAK_MIN = 5
LONG_BREAK_MIN = 20
