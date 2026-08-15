A beginner-friendly Expense Tracker REST API built with Java, Spring Boot, Spring Data JPA, and H2 Database. Supports CRUD operations, expense categorization, validation, and expense summaries, with APIs tested using Postman.
expense-tracker-rest-api
│
├── src
│   └── main
│       ├── java
│       │   └── com
│       │       └── example
│       │           └── expensetracker
│       │               ├── controller
│       │               │   └── ExpenseController.java
│       │               ├── entity
│       │               │   └── Expense.java
│       │               ├── exception
│       │               │   ├── ExpenseNotFoundException.java
│       │               │   └── GlobalExceptionHandler.java
│       │               ├── repository
│       │               │   └── ExpenseRepository.java
│       │               ├── service
│       │               │   └── ExpenseService.java
│       │               └── ExpenseTrackerApplication.java
│       │
│       └── resources
│           └── application.properties
│
├── .gitignore
├── pom.xml
└── README.md
