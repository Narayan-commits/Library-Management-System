# 📚 Library Management System -Java


<a href="https://github.com/harismuneer"><img alt="views" title="Github views" src="https://komarev.com/ghpvc/?username=harismuneer&style=flat-square" width="125"/></a>
[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](#)
[![GitHub Forks](https://img.shields.io/github/forks/harismuneer/Library-Management-System-JAVA.svg?style=social&label=Fork&maxAge=2592000)](https://www.github.com/harismuneer/Library-Management-System-JAVA/fork)
[![GitHub Issues](https://img.shields.io/github/issues/harismuneer/Library-Management-System-JAVA.svg?style=flat&label=Issues&maxAge=2592000)](https://www.github.com/harismuneer/Library-Management-System-JAVA/issues)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat&label=Contributions&colorA=red&colorB=black	)](#)


A Library Management System made using the concepts of Object Oriented Analysis and Design. Minimal Code is written in the GUI and the entities are decoupled as well. The interface is console based. This project was designed during the course "Object Oriented Analysis and Design".



## Actors:
The actors include the following: 
* Librarian
* Checkout Clerk
* Borrower
* Administrator

## Use Cases:
After determining the actors, the second step in use case analysis is to determine the tasks that each actor will need to do with the system. Each task is called a use case because it represents one particular way the system will be used.

**In other words, only those use cases are listed that actors will need to do when they are using the system to solve the customer’s problem.** 

### Borrower:
* ❏ Search for items by title.
* ❏ ... by author.
* ❏ ... by subject.
* ❏ Place a book on hold if it is on loan to somebody else.
* ❏ Check  the  borrower’s  personal  information  and  list  of  books  currently
borrowed.

### Checkout Clerk:
* ❏ All the Borrower use cases, plus
* ❏ Check out an item for a borrower.
* ❏ Check in an item that has been returned.
* ❏ Renew an item.
* ❏ Record that a fine has been paid.
* ❏ Add a new borrower.
* ❏ Update a borrower’s personal information (address, telephone number etc.).

### Librarian:
* ❏ All of the Borrower and Checkout Clerk use cases, plus
* ❏ Add a new item to the collection.
* ❏ Delete an item from the collection.
* ❏ Change the information the system has recorded about an item.

### Administrator:
* ❏ Add Clerk.
* ❏ Add Librarian.
* ❏ View Issued Books History.
* ❏ View All Books in Library.
