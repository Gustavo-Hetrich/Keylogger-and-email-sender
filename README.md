# Keylogger-and-email-sender

Hello, the following code is a project where i made a keylogger in python and wanted it to send me a email with the keylog text file in my email every hour.
For this i used the smtplib for connecting to the email servers and multiprocessing to make the code dont stop logging the keys and sending the email at the same time

I had never used multiprocessing in a project befora, so if it looks strange or not optimized, please let me know

i plan to make this project to work like a virus, enterirng someone's computer, runing in second plan and creating the kaylog.txt in some hidden directory, and maybe try to turn this into a .exe.

for running the program yourself is really ease, you just need to change the following directories for  yours:

log_dir = "your-directory"
keylog_name = 'your-keylog-name.txt"

and changing the amils and password (the password is the google app paswword)

    email_sender = r'your-email'
    email_password = r'your-password'
    email_receiver = r'other-email'

any doubts or advce please contact me at gustavohetrich@outlook.com

