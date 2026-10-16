# Activity 1: How the Internet Works
Students simulate the interaction between a browser, server, and database to understand how requests are processed and responses are returned.

# Solution


Aim: To understand how a browser communicates with a server and database to process a request and return a response.

Example: A student opens a college website and views their results.

### Flowchart

Start

Browser

Student requests results

Web Server / Backend

Receives and processes the request

Database

Retrieves the student's result

Server sends the response

Browser displays the result

End

### Explanation

1. The user enters a website URL in the browser.
2. The browser sends an HTTP or HTTPS request to the server.
3. The backend processes the request.
4. The server queries the database for the required information.
5. The database returns the result to the server.
6. The server sends an HTTP response to the browser.
7. The browser displays the result.

Result: Students understand how a browser, server, and database work together to deliver website content.

# Activity 2: Logic Building Challenge

Aim: To solve logical problems using flowcharts and pseudocode before writing a program.

Problem: Find whether a given number is even or odd.

### Flowchart

Start

Input number `N`

Is N % 2 = 0?

Yes

Print Even

End

No

Print Odd

End

### Pseudocode

```
START
INPUT N

IF N MOD 2 = 0 THEN
    PRINT "Even"
ELSE
    PRINT "Odd"
END IF

STOP
```

### Python implementation

```
n = int(input("Enter a number: "))if n % 2 == 0:    print("Even number")else:    print("Odd number")
```

Example output:

```
Enter a number: 7
Odd number
```

Result: Students learn to analyze a problem, create a flowchart, write pseudocode, and convert the logic into executable code.

Other challenges can include finding the largest of three numbers, calculating factorials, and checking whether a number is prime.

# Activity 3: Real-world Scenario Mapping

Aim: To identify frontend, backend, and database components in everyday applications.

Example: An online shopping application.

[Ecommerce Mobile App - UI UX Design by Tariqul islam on Dribbble](https://images.openai.com/static-rsc-4/g5EEynZbpjgDJCKqrZslFxagux9KTPnYY8cpxV4OpgLSDP8bBJQTiit6Ww8QlInQGdBdwDSp2fowzytnJ94iKFWEIIYMVeLPHNvUhyHzYcO-aTP4WXwuWYOXS4qcIIyYIrlGmwnW3IjF4LIzflUb12f1p5q5XmNQ6mpjowinuHM?purpose=inline)

[dribbble.com](https://dribbble.com/shots/22047333-Ecommerce-Mobile-App-UI-UX-Design?utm_source=chatgpt.com)

### Flowchart

User

Searches for a product

Frontend

HTML, CSS, JavaScript, React

Displays products and the shopping cart

Backend

Processes requests and business logic

Checks product availability and orders

Database

Stores products, prices, users, and orders

Backend returns the data

Frontend displays products to the user

### Component mapping

| Component | Purpose                             | Examples                   |
| --------- | ----------------------------------- | -------------------------- |
| Frontend  | User interface                      | HTML, CSS, React           |
| Backend   | Handles requests and business logic | Node.js, Express           |
| Database  | Stores and retrieves information    | MySQL, PostgreSQL, MongoDB |

### Other real-world examples

| Application    | Frontend                        | Backend function                           | Database information         |
| -------------- | ------------------------------- | ------------------------------------------ | ---------------------------- |
| WhatsApp       | Chats and messages UI           | Sends and receives messages                | Messages and account data    |
| YouTube        | Video player and search UI      | Finds videos and manages playback requests | Video metadata and user data |
| Banking app    | Balance and transaction screens | Processes authorized banking requests      | Accounts and transactions    |
| College portal | Student dashboard               | Handles marks and attendance requests      | Student records and results  |

Result: Students understand how frontend, backend, and database components work together to build real-world applications.

## Final conclusion

These three activities demonstrate the basic principles of web development:

- Activity 1: How data travels between a browser, server, and database.
- Activity 2: How to solve problems using logical thinking, flowcharts, and pseudocode.
- Activity 3: How real-world applications use frontend, backend, and database components together.

