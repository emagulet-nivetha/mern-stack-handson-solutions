# Activity 1: How the Internet Works
Students simulate the interaction between a browser, server, and database to understand how requests are processed and responses are returned.

# Solution

# Activity 1: How the Internet Works

Aim: To understand how a browser, web server, and database communicate to process requests and return responses.

## 1. Flowchart

START

1\. Browser

User enters a website URL or requests information

2\. HTTP/HTTPS Request

Browser sends the request over the internet

3\. Web Server / Backend

Receives and processes the request

4\. Database

Retrieves the requested information

5\. Server Response

Server receives data from the database and prepares a response

6\. Browser Displays the Result

The requested webpage or information appears on the screen

STOP

## 2. Example scenario

A student wants to view their exam results on a college website.

1. Browser: The student opens the college website and clicks “View Results.”
2. Request: The browser sends a request to the web server.
3. Server: The backend receives the request and checks the student's identity and permissions.
4. Database: The server retrieves the student's marks from the database.
5. Response: The server sends the result back to the browser.
6. Display: The browser displays the marks on the screen.

## 3. Simulation activity

Students can act out the roles of the different components.

| Participant | Role       | Action                |
| ----------- | ---------- | --------------------- |
| Student     | User       | Requests exam results |
| Student 1   | Browser    | Sends the request     |
| Student 2   | Web server | Processes the request |
| Student 3   | Database   | Finds the exam marks  |
| Student 1   | Browser    | Displays the response |

Simulation example:

- Browser: “I need the student's exam result.”
- Server: “I will request the result from the database.”
- Database: “The student's mark is 85.”
- Server: “Here is the result.”
- Browser: “Your mark is 85.”

## 4. Basic Python simulation

```
# Browserprint("Browser: Requesting student result...")# Serverprint("Server: Processing request...")# Databasedatabase = {    "Nila": 85,    "Arun": 90}name = input("Enter student name: ")# Server retrieves data from the databaseif name in database:    result = database[name]    print("Server: Sending response...")    # Browser displays response    print("Browser: Student mark =", result)else:    print("Browser: Student record not found.")
```

Example output:

```
Browser: Requesting student result...
Server: Processing request...
Enter student name: Nila
Server: Sending response...
Browser: Student mark = 85
```

Note: This is a simplified simulation. The Python dictionary represents a database, and the program simulates request processing without an actual internet connection.

## 5. Result

Students understand how a browser sends requests, how a server processes them, how a database provides information, and how the browser displays the returned response.
