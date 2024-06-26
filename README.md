# Xpense Tracker App
![Xpense Tracker](https://happay.com/blog/wp-content/uploads/sites/12/2022/08/expense-categories.webp)
## The Xpense Tracker Application is a simple web application designed to help users keep track of their expenses. Users can log their expenses, categorize them, and view their expense history.

## Table of Contents
- [Xpense Tracker](#xpense-tracker-app)
- [Feature](#features)
- [Technology Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

# Features
![Feature](https://t4.ftcdn.net/jpg/03/03/55/51/360_F_303555158_0h7YQZePL54n1UFE0Y5u4xqLSvHklqwc.jpg)
1. **Expense Logging**: Users can log their expenses by providing details such as name, amount, category, and description.
2. **Category Filtering**: Users can filter their expenses based on categories to view specific types of expenses.
3. **User Authentication**: Users must authenticate themselves to access the application and log their expenses.
4. **Expense History**: Users can view their expense history, including details such as name, amount, category, and date.
5. **Incremental ID Generation**: Each expense is assigned a unique incremental ID for easy reference.

# Technologies Used.
## Backend Implementation Only.
- Node.js: Server-side JavaScript runtime environment.
- Express.js: Web application framework for Node.js used for routing and middleware handling.
- MongoDB: NoSQL database used to store expense data.
- Mongoose: MongoDB object modeling tool for Node.js used for data validation and schema definition.
- axios: A promise-based HTTP client for the browser and server side(Nodejs).
- Bcrypt: A cryptographic hashing library used for securely hashing passwords.


# Getting Started
![Get Started](https://www.lean.org/wp-content/uploads/2020/11/924_large.png)
## To get started with the Expense Tracker App, follow these steps:
1. Clone the repository: `git clone [repository]-url`
    - Open the terminal and run:
    ```
    git clone https://github.com/line75/XpenseTracker.git
    ```
2. Install dependencies:
    - Navigate to the Backend directory:
    ```
    cd ~/Backend/ && npm install
    ```
3. Set up environment variables:
    - Create a '.env' file in the root directory.
    - Define environment variables such as database connection URI, session secret, etc.
4. Start the server:
    ```
    npm run devStart
    ```
5. Access the application in the web browser or test in an API testing tools.
    - Testing tools like (Postman, ApiDog etc) or
    ```
    http://127.0.0.1:5000
    ```
# Usage
![Usage](https://grammarist.com/wp-content/uploads/Usage-in-English-Grammar-List-of-Examples-2.png)
- **Logging Expenses**: Navigate to the appropriate section of the application to log your expenses. Provide details such as name, amount, category, and description.
- **Filtering Expenses**: Use the category filter option to view expenses based on specific categories.
- **Viewing Expense History**: Access the expense history section to view a list of all logged expenses.

# Contributing
![Contributing](https://images.squarespace-cdn.com/content/v1/5e957a3497df352a10e04d84/400d22bb-b17a-46d4-ad03-2a0b4b497f3d/Whats+your+unique+contribution.png)
## Contributions to the Expense Tracker App are welcome! To contribute:
- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes.
- Test your changes.
- Submit a pull request.
