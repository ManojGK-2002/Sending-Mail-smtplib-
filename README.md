🎉 Automated Birthday Wisher App with Python! 🎂🍰🎈
This is a simple Python application that automatically sends personalized birthday emails at 12:00 PM (noon) to users based on their date of birth.
It reads user data from a CSV or Excel file, checks if today is their birthday, and uses SMTP to send a heartfelt birthday email.

📌 Features
✅ Reads user info (Full Name, DOB, Email) from .csv or .xlsx files
✅ Checks daily for matching birthdays
✅ Sends customized birthday emails via Gmail SMTP
✅ Automatically runs daily at 12:00 PM using PythonAnywhere
✅ Fully customizable birthday message
✅ Lightweight, fast, and easy to deploy

🛠️ Tech Stack
Python 3
smtplib – for sending emails
pandas – for handling CSV/Excel files
openpyxl – for reading .xlsx files
email.message.EmailMessage – to create MIME email messages
PythonAnywhere – to schedule and host the script online

🕛 How It Works
Store user data (Full Name, DOB, Email Address) in a .csv or .xlsx file
Every day at 12:00 PM, the script:
Reads the file
Checks if the current date matches any DOBs
Sends a birthday email using your Gmail account
Hosted on PythonAnywhere to run automatically without your local machine

  
