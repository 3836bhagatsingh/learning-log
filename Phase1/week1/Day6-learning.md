
Day6-Learning

#What  I  learnt


#SQL
Data Formats and Databases
Structured, Semi Structured and Unstructured Data

##Python Project 1-Samrt Task Management CLI
What is README ->A README.md is the entry point of your project.
It explain:
1-What  this project is
2-Why it exist
3-How to use it
4-How it is built

##Why README is important
1-First impression on GitHub
2-Shows your engineering maturity
3-Help you later

##What Should a Good README Contain?
1-Project Title
2-Description
3-Features
4-Project Structures
5-Installation Instructions
6-Usage
7-Technologies Used
8-Concepts Covered
9-Future Enhancements
10-Author Section


Project - Smart Task Management CLI
PHASE 1 -> Problem Understanding
 Clearly define what problem you are solving
 Identify user operations (CRUD)
 Decide what data you will store
 Think about failure scenarios

PHASE 2  ->  System Design

 Divide system into layers:

Interface (CLI)
Business logic
Data storage

 Define modules/files
 Define flow of data


PHASE 3 -> Data Modelling
 Define task structure
 Decide required fields
 Ensure data consistency

PHASE 4 -> Coding

4.1 Writing Modular Functions
 One function = one responsibility
 Use meaningful names
 Avoid long functions

4.2 Input Validation
 Validate all inputs
 Use assert for assumptions
 Use raise for business errors

4.3 Exception Handling
 Wrap risky operations in try/except
 Log errors
 Do not crash program

4.4 File Handling
 Always check file existence
 Handle JSON decode errors
 Backup before writing

4.5 Logging
Log every major action
 Log errors separately
 Use log levels (INFO, ERROR)

PHASE 5 -> CLI Design

Use loop for continuous interaction
 Show clear menu
 Handle invalid choices

PHASE 6 -> Testing

 Test each function individually
 Test edge cases
 Test failure scenarios

PHASE 7 -> Security & Vulnerability Thinking
Data Corruption
Input Injection


Data Loss
Unhandled Exceptions
Hardcoded Values


PHASE 8 -> Code Quality
 Follow naming conventions
 Add comments where needed
 Keep functions small
 Avoid duplicate code

PHASE 9 -> Documentation(README)
Explain problem
 Explain architecture
 Add installation steps
 Add features list

PHASE 10 -> Future Readiness
 Can I convert this into API?
 Can I switch JSON to DB?
 Can I scale this?
