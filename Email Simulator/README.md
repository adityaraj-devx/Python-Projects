📧 Email Simulator

A command-line Email Simulator built in Python as part of the freeCodeCamp Python Certification Course.

This project simulates basic email functionality such as sending, receiving, reading, and deleting emails between users in a structured and organized way.

📚 About This Project

This project was completed during the freeCodeCamp Python Certification under the Classes and Objects workshop section.

The objective of this project was to:

Practice organizing code using multiple classes

Model a simple real-world system

Manage interactions between connected components

Implement basic user-based functionality

Handle errors gracefully

🚀 Features

Create multiple users

Send emails between users

Automatically generate timestamps for emails

Track read/unread status

View inbox messages

Read specific emails

Delete emails

Handle invalid email selections safely

🏗️ Project Structure

The application is divided into three main components:

📩 Email

Represents a single email message.

Stores sender, receiver, subject, and body

Automatically records the time the email was created

Tracks whether the email has been read

Displays formatted email details

📬 Inbox

Manages a user's email collection.

Stores incoming emails

Lists emails with read/unread status

Allows reading a specific email

Allows deleting an email

👤 User

Represents a user in the system.

Has a personal inbox

Can send emails to other users

Can check, read, and delete emails

🖥️ Example Usage
tory = User("Tory")
ramy = User("Ramy")

tory.send_email(ramy, "Hello", "Hi Ramy, just saying hello!")
ramy.send_email(tory, "Re: Hello", "Hi Tory, hope you are fine.")

ramy.check_inbox()
ramy.read_email(1)
ramy.delete_email(1)
ramy.check_inbox()
📌 Sample Output
Email sent from Tory to Ramy!

Ramy's Inbox:
1. [Unread] From: Tory | Subject: Hello | Time: 2026-02-20 14:35

--- Email ---
From: Tory
To: Ramy
Subject: Hello
Received: 2026-02-20 14:35
Body: Hi Ramy, just saying hello!
------------

Email deleted.
🛠️ How to Run
Requirements

Python 3.8 or higher

Run the Project
git clone https://github.com/your-username/email-simulator.git
cd email-simulator
python main.py


📁 Project Structure
email-simulator/
│
├── main.py
└── README.md


👨‍💻 Author

Aditya Raj

Built as part of the freeCodeCamp Python Certification Course.


give me the copy paste version just one click and  everything is copied