Task 1: The Logic Master (FizzBuzz)
Objective: Master conditional logic and loops.

Requirements:
Create a function named fizzbuzz_checker(limit).

The function should use a for loop to iterate from 1 to the limit.

Logic Rules:

If the number is divisible by both 3 and 5, print "FizzBuzz".

If divisible by 3, print "Fizz".

If divisible by 5, print "Buzz".

Otherwise, just print the number itself.

Task 2: The Security Auditor (Modules & Tuples)
Objective: Practice cross-file imports and using immutable data types.

Requirements:
Create scanner.py (The Module):

Define a Tuple named DANGEROUS_PORTS containing (21, 23, 445).

Create a function check_ports(active_ports) that loops through a list and prints a warning if a port is found in your DANGEROUS_PORTS tuple.

Create app.py (The Execution Script):

Import the scanner module.

Define a list of ports: [22, 80, 21, 443, 23, 8080].

Call the function from your module to audit the list.

Task 3: The System Health Check (JSON & Error Handling)
Objective: Safely handle external data strings using json and try/except.

Requirements:
Create a function process_server_data(json_string).

Inside the function, use json.loads() to parse the input.

Wrap the parsing logic in a try/except block to catch json.JSONDecodeError.

If successful, loop through the resulting list of servers and print the status of each.

Test Data:
Use this string to test your function:

mock_api = '{"servers": [{"name": "web-01", "status": "up"}, {"name": "db-01", "status": "down"}]}'
How to Submit
Create a virtual environment: python -m venv .venv

Activate it and ensure your code runs without errors.

Organize your files clearly in your project folder.