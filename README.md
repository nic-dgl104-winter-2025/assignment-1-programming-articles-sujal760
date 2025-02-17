[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/_Y4t8UXw)
# dgl104-programming-article-repo

## Refactoring Practices ##

Refactoring is a crucial skill for software developers, as it helps to clarify, improve efficiency, and address assumptions made in initial problem-solving attempts. It is essential to preserve the original meaning and intent of the code, and only when a complete understanding of the program is achieved can refactor effectively. 

Refactoring is not code rewriting, which is a more substantial effort that may involve discarding some or all of the original code. Reasons for rewriting may include major changes to a dependency or porting the project to a new language or framework. Best practices for refactoring include making incremental changes that clearly demonstrate the progression from the original code to the final product, with small refactors being easier to manage and roll back if necessary.

## Refactoring is the process of cleaning up and improving code without changing how it works for the end user.##

The goal of refactoring is to preserve the functionality of the code while making it simpler to read, maintain, and grow. Refactoring speeds up the creation of new features while lowering the long-term expenses of software maintenance and updates for enterprises.

There are several types of refactoring, depending on the problem at hand:

**Code-level refactoring:** Making methods simpler, renaming confusing variables, and removing duplicate code.
**Architectural refactoring:** Redesigning how the system is structured, like introducing abstraction layers or shifting to microservices.
**Performance refactoring:** Speeding up the software by optimizing algorithms or reducing resource use.
**Data refactoring:** Cleaning up databases, improving data integrity, or adding caching to speed things up.
**UI/UX refactoring:** Breaking front-end code into reusable components to make design changes easier.

## When Should the Code Be Refactored? ##

 **When Code is Hard to Understand**

- Signs:
1. You or your teammates struggle to understand the code.
2. Comments are needed to explain what the code does.
3. Variable or function names are unclear or misleading.

**When There is Duplicated Code**

- Signs:
1. The same logic appears in multiple places.
2. Fixing a bug requires changes in multiple locations.

**When Functions or Methods are Too Long**

- Signs:
1. A function or method does more than one thing.
2. The function is hard to read or test.

**When Performance Issues Arise**

- Signs:
1. The code is slow or inefficient.
2. Profiling reveals bottlenecks in specific areas.

**Conclusion** 

Refactoring should be done when code becomes hard to understand, maintain, or extend. It’s not a one-time task but a continuous process that ensures your codebase remains clean, efficient, and adaptable. By refactoring at the right time, you can prevent technical debt, improve collaboration, and make your codebase more resilient to change.

Some Of the example of the code refactoring process are:
Code Duplication.
![image](https://github.com/nic-dgl104-winter-2025/assignment-1-programming-articles-sujal760/blob/main/project%20screenshot%201.png?raw=true))