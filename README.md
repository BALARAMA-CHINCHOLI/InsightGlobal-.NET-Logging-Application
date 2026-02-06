# InsightGlobal-.NET-Logging-Application
  This application was developed as part of the Insight Global coding assessment. The goal of the exercise was to design a simple, maintainable application that logs events into a text file while following clean coding practices and structured design.  The solution focuses on separation of concerns, exception handling, and basic system design.

Objective:
Capture application events
Log them into a text file
Maintain a clear and structured logging mechanism

Skills: .NET 8, C#, File I/O

Threading concepts 
Exception handling
Design Approach
Logger Class

A dedicated Logger class was created to separate logging functionality from the main program.

Responsibilities of Logger:
Handle file creation
Write logs to text file
Manage file path
Handle exceptions during file operations

Logs are written to: '/log/out.txt'

Docker Support:
A Dockerfile was created to containerize the application.
Due to system limitations (Windows version compatibility), Docker Desktop installation could not be completed within the available time. However:
Docker configuration was prepared
File paths were updated for Linux container execution
The project is ready to run in a Docker-enabled environment
This demonstrates willingness to adapt to unfamiliar tools and learn quickly.
How to Run the Application
Navigate to project folder

Run: dotnet run
