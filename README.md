# Birthday-Reminder
This is a birthday reminder app that I made using Python. This will notify the user if there are any birthday of his/her friends. 
When the user boots up his/her PC, the program will launch automatically and send you a Notification to remind you of the Birthday. 
> Note that this program will run succesfully in Linux and the instructions to make it a startup app, which is mentioned below is for Linux Systems only. I have yet to make this for Windows,

## Steps to make this a startup app in Linux
1. Firstly, we have to create an executable file for our app.py script. This can be done with the following command:
    `sudo chmod +x app.py`


2. Now we have to transfer this file to the path where Linux searches for its default files. This can be done using the following command:
    ` sudo cp <original path of the app.py file> /usr/bin`

3. In global search, search for **Startup Applications**
    3.1. Click on **"Add"** and give a desired name for the process.
    3.2. Type in the command. For example, our file name is _app.py_ then type reminder.py in the command field and Select **"Add"**

And all set!