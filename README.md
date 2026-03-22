🎂 Birthday Email Automator
A Python automation script that automatically sends personalized
birthday emails to your contacts using Gmail and Pandas.
📋 About
This project checks if today matches any birthday in your CSV file
and automatically sends a personalized birthday email with a randomly
selected letter template. Set it up once and never forget a birthday again!
✨ Features

🎂 Automatic birthday detection
💌 Personalized email with recipient's name
🎲 Randomly selects from 3 letter templates
📊 Reads contacts from CSV file
🔒 Secure credential handling with environment variables
📧 Sends via Gmail SMTP

🖥️ Example Output
Today is someone's birthday!
Sending email to John...
Birthday email sent! 🎂
🛠️ Built With

Python 3
Pandas — CSV data handling
smtplib — Email sending
datetime — Date checking
python-dotenv — Secure credentials

🚀 How to Run

Make sure Python is installed
Install requirements:

pip install pandas python-dotenv

Clone this repository:

git clone https://github.com/alexisn1989/birthday-email-automator

Create .env file with your credentials:

MY_EMAIL=your_gmail@gmail.com
MY_PASSWORD=your_gmail_app_password

Add birthdays to birthdays.csv
Run the program:

python main.py
📁 Project Structure
birthday-email-automator/
├── main.py                      ← main program
├── birthdays.csv                ← contacts and birthdays
├── .env                         ← credentials (never push to GitHub!)
├── .gitignore                   ← ignores .env file
└── letter_templates/
    ├── letter_1.txt             ← template 1
    ├── letter_2.txt             ← template 2
    └── letter_3.txt             ← template 3
📊 birthdays.csv Format
name,email,year,month,day
John,john@email.com,1990,3,22
Sarah,sarah@email.com,1985,7,15
📝 Letter Template Format
Dear [NAME],

Wishing you a wonderful birthday!

Best wishes,
Alexi
🔒 Security Notes

Never hardcode email credentials in your code
Always use environment variables for sensitive data
Create Gmail App Password at myaccount.google.com
Add .env to .gitignore before pushing to GitHub

📦 Requirements
pandas
python-dotenv
smtplib (built into Python)
datetime (built into Python)
💡 What I Learned

Sending emails with Python smtplib
Gmail SMTP SSL configuration
Creating Gmail App Passwords
Reading CSV data with Pandas
Dictionary comprehensions
Date and datetime handling
Environment variables for security
File reading and string replacement
Random selection from files

👨‍💻 Author
Alexi — Aspiring Python Developer
Currently completing Angela Yu's 100 Days of Code bootcamp
📍 Virginia Beach, VA | Open to remote opportunities
🔗 LinkedIn: your-linkedin-url
🐙 GitHub: github.com/alexisn1989
