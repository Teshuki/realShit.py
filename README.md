## realShit.py
#It's none of your business.
#Write a program that has a user guess your name, but they only get 3 chances to do so until the program quits.
import sys

i=0
for i in range(3):
    name=input("What is your name?\n")
    password=input("What is the password?\n")
    if name=="Johnny" and password=="yellowfeet":
       print("Welcome, master. :3")
       break
    else:
        i=i+1
sys.exit()
