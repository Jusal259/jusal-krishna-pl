[4:50 am, 30/4/2024] Jusal Krishna: import turtle as t
import time
time.sleep(3)
t.speed(6)
t.penup()
t.goto(-200,0)
t.right(-90)
t.fd(200)

t.begin_fill()
t.pendown()
t.right(90)
t.fd(250)
t.right(90)
t.fd(50)
t.right(90)
t.fd(250)
t.right(90)
t.fd(50)
t.fillcolor("orange")
t.end_fill()



t.penup()
t.right(180)
t.fd(50)
t.begin_fill()
t.pendown()
t.fd(50)
t.right(-90)
t.fd(250)
t.right(-90)
t.fd(50)
t.fillcolor("white")
t.end_fill()


t.penup()
t.right(-180)
t.fd(50)
t.begin_fill()
t.pendown()
t.fd(50)
t.right(90)
t.fd(250)
t.right(90)
t.fd(50)
t.fillcolor("green")
t.end_fill()


t.penup()
t.right(90)
t.fd(125)
t.begin_fill()
t.pendown()
t.circle(25)
t.fillcolor("blue")
t.end_fill()



t.mainloop()
[7:59 am, 30/4/2024] Raghul: from tkinter import *
from tkinter import messagebox
window =Tk()
def submit():
    messagebox.showinfo("Submitted", "Registration Successful")

window.title("Registration Form")
title = Label(window, text="REGISTRATION FORM", font=("Times new roman", 16))
title.grid(row=0, column=0)

l1=Label(window, text="Full Name").grid(row=1)
l2=Label(window, text="Email").grid(row=2)
l3=Label(window, text="Gender").grid(row=3)
l4=Label(window, text="Country").grid(row=4)
l5=Label(window, text="Programming Language").grid(row=5)

e1=Entry(window).grid(row=1, column=1)
e2=Entry(window).grid(row=2, column=1)

gender = StringVar()
r1=Radiobutton(window, text="Male", variable=gender, value="Male").grid(row=3, column=1)
r2=Radiobutton(window, text="Female", variable=gender, value="Female").grid(row=3, column=2)

countries = ["India", "USA", "UK", "Australia", "Canada"]
country = StringVar()
country.set(countries[0])  # default value
o1=OptionMenu(window, country, *countries).grid(row=4, column=1)

language = StringVar()
c1=Checkbutton(window,text="Java",variable=language).grid(row=5, column=1)
c2=Checkbutton(window,text="python",variable=language).grid(row=5, column=2)
b1=Button(window,text='Submit', command=submit,bg='red',fg='white',font=('Times new roman',10)).grid(row=6, pady=1)
window.mainloop()










Git exp 1
git
git config --global user.name "UN github"
git config --global user.email "Umail github"

Git exp 2
git cd repository 
Create a file
git add .
git commit -m "message"
git push origin main

Git exp 3
Create branch
git status
git pull
git checkout  branch name
Create a new file in vs code
#this is to add some changes and add that in GitHub page.
git add .
git commit -m "msg"
git push origin branch name
#this is to merge the file in both main and sub branch
git checkout main
git merge branch name

Git exp 4
Create a new issue in github page 
Add label, and other stuff in 
Add description
Commit issue
Close issue

Git exp 5
Search for form owner:urk23cs1242
Go to repository
Create fork 
Copy link
In vs code
git clone link 
git cd repository name 
git remote add  any name link 
git fetch name given in above

Git exp 6
git config --global alias.ak 'clone'
git ak URL
