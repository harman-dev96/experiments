Set up the Express server and connected it with the MySQL database to store user authentication tokens.
Created custom logging middleware to display request method, route, and execution flow in the terminal.
Developed authentication middleware that reads the token from request headers and validates it against the MySQL users table.
Applied middleware to protected routes such as /dashboard to allow access only to authorized users.
Tested all routes in Postman for successful access, unauthorized requests (401), and verified correct middleware sequence.