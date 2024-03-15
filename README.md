# Keylogger-and-email-sender

## Overview
This project implements a keylogger writed in Python that periodically sends a log of keystrokes to a specified email address. The program utilizes the smtplib library to connect to email servers and multiprocessing to ensure continuous logging and emailing without interruption.

## Motivation
The main goal of this project is to create a stealthy keylogger that can run in the background of a computer, logging keystrokes and sending them via email. This project serves as a learning experience for utilizing multiprocessing in Python projects and exploring potential applications of keyloggers.

## Usage
Modify the following directories in the code to match your setup:


    log_dir = "your-directory"
    keylog_name = 'your-keylog-name.txt'
    Update the email credentials in the code (the password should be a Google App password):


    email_sender = r'your-email'
    email_password = r'your-password'
    email_receiver = r'other-email'
Run the program and let it log keystrokes and send emails automatically.

## Contact
For any questions, doubts, or advice, please contact me at **gustavohetrich@outlook.com**.

Feel free to adjust the content to better match your project's goals and structure!
