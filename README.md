# ST10518128-POE-PART3
This is the final part of project.
QuickChat is a Java console application that allows users to register, login, send messages, store messages, and manage stored messages.

## Features
- User Registration and Login with validation
- Send messages with Message ID, Hash, Recipient and Flag
- Store messages to JSON file
- Read JSON file into parallel arrays and display to user
- Display details for the longest message
- Search messages by Recipient
- Search messages by Message ID
- Delete message using Message Hash
- Display full Message Report
- 
## Technologies Used
- Java 17
- NetBeans IDE
- Apache Ant
- JUnit for Unit Testing
- GitHub Actions for Automated Testing

## How to Run
1. Open the project in NetBeans
2. Right-click project > Run
3. Follow the menu to Register, Login, and Send Messages

## How to Run Tests
Right-click project > Test
Or via terminal:
ant test

Tests included:
- LoginTest
- QuickChatTest
- StoredMessagesTest

- ## Automated Tests
This project uses GitHub Actions. On every push, .github/workflows/TestJava.yml runs ant test automatically.

## Project Structure
- src/shaun/ - Main application code
- test/ - Unit tests
- .github/workflows/TestJava.yml - CI workflow

## Author
Shaun - PROG5121 Programming 1A


