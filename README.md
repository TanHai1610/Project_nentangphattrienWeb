# Website sends and approves multiple choice questions

## Introduction
1. Language: HTML, CSS, JS.
2. Topic: Knowledge of HTML, CSS, JS (only 1 of 3 topics).
3. Actors and functions:
   
3.1. Question sent by:

+ Add, edit, delete questions: Select question type; Enter question; Enter the answer; Enter the correct answer; Submit a question
+ Displays a list of recently sent questions including: STT, Sending time, question, answer, correct answer, status (Waiting for approval, not approved, Approved)
  
3.2. Question reviewer:
+ Displays a list of sent questions including: STT, Sending time, question, answer, correct answer, question sender
+ Approve and disapprove questions
4. System components:
  
4.1. Home page: Displays account information and introductory information about the website

4.2. Question Set page: has 3 corresponding subpages: HTML Question Set, CSS Question Set, JS Question Set, of which 1 subpage is a well-functioning group topic (eg: Group topic is CSS → Just the CSS Question Set subpage needs to work). In this subpage, the following requests need to be handled:

4.2.1. Question sender account:
+ Select question type
+ Enter question
+ Enter the answer
+ Enter the correct answer
+ Submit a question
+ Displays a list of recently sent questions including: STT, Sending time, question, answer, correct answer, status (Waiting for approval, not approved, Approved)
+ Function Add, edit, delete questions
  
4.2.2. Question reviewer account:
+ Displays a list of sent questions including: STT, Sending time, question, answer, correct answer, question sender
+ Function: approve and unapproved questions
  
4.3. Contact page: Shows contact methods
