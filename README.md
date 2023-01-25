# Lab-1_202001083

IT - 314 Software Engineering 
Lab assignment 1

Name:- Vedant Patel
Student ID:- 202001083


Q.1. Identify FRs and NFRs:

Functional Requirements

1) Log In/ Sign up
-> If user wants to issue a book he must be member of LIS
-> So, before issuing user must login with his credential 
-> If user is not member of the LIS then he must sign up using his details and register his/her    self

2) Maintain records of the book
-> System must contain the database of all book
-> It should contain a unique ID, location, book name, type, author name, publication, edition, registered date etc.

3) Search
-> Search is open for all users.(no need to login)
-> Users can search by book name, type, author, publication etc.
-> there should be filters for normal books, journals, Scholar articles, daily/ monthly magazines etc. 

4) Acknowledgement of new arrivals
-> it should highlight newly added books
-> If user already searched for an item and at that time it is not available and now it is available then it should notify that user about it


5) Issue/ returning a book
-> if the user found the desired book and wants to issue it then the system should show all copies of that book with its availability.
-> If it is available then the user can issue it for a strict time period. He/she must return the book within that time period otherwise they have to pay the penalty amount.
-> if the user wants to extend his time period then the system allows it if no one is asked to issue that book.
-> If it is not available then it should show the user the date when it will be available.


6) Update records
->  System should be allowed to update the database for newly arrived books or if any book is removed.
-> this can be done by only authorized people (librarian, staff)

7) Generate report
-> System should be able to generate reports of all transactions when it is required.
-> Daily, Monthly, Yearly


Non - Functional Requirements

User is able to open the website only if he/ she is connected to the institute's network.(no via private network)
Privacy - Personal details of the users should not be leaked at any cost.
Security - only authorized people can access the database of LIS. confidential information like password should not be stored as plain text. It must be encrypted.
Speed - Servers should be capable of high traffic. (at least 75 % of the population of institute can be able to access it smoothly )
Ease of use  - System should have a normal easy to understand interface. Users should be able to find required information easily.



Q.2. Identify scope, features and non-functional aspects of the following problem.

Scope

The app able to identify the different alert sounds like car horn, bell rings, door knocks,
Call rings, fire alarms, Animal sound etc. After that it should replicate that alerts via vibration and flash lights in a real time environment. (quick).

Features 

-> User can set his alert method (vibration rhythm, flash blinking)
-> It does not stop until user don’t stop it
-> Only user can stop the alert (fingerprint verification or else)

Non functional Requirements

1)  Reliability - App should accurately identify voice and response accordingly
2)  Security - Only user can change the setting
3)  low latency - App should be optimized and response time should be very quick so it can usable in real time
4) Scalability - App should be able to entertain 5% of the world population 
