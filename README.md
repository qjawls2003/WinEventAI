# WinEventAI


## Project Description
Windows application written in Python that allows Users to utilize GPT to craft a powershell command that returns the output of the command.

## Concept
1. User needs to find an event related to Process creation of an .exe
2. User inputs "find me a process that was created yesterday named Chrome.exe"
3. The application will make necessary API call to OpenAI to receive a crafted powershell command.
4. The command is executed on the user's machine (additional security layer to ensure that only read commands are executed)
5. The results from the powershell command is return to the user.


pip install pyinstaller
pyi-makespec main.py
pyinstaller main.py