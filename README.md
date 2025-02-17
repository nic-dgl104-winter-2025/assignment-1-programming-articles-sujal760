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

**Code Duplication.** 

![image](https://github.com/nic-dgl104-winter-2025/assignment-1-programming-articles-sujal760/blob/main/project%20screenshot%201.png?raw=true)

**An Example of a code being too long and it being refactored.**

![image](https://github.com/nic-dgl104-winter-2025/assignment-1-programming-articles-sujal760/blob/main/screenshot%202.png?raw=true)

# How Refactoring Helps Avoid Technical Debt  

Refactoring helps avoid technical debt by improving code structure, maintainability, and efficiency without changing its external behavior.  

## 1. Improves Code Readability & Maintainability  
- Refactoring simplifies complex code, making it easier for developers to understand and modify in the future.  
- Clearer code reduces onboarding time for new developers and prevents mistakes caused by confusion.  

## 2. Enhances Scalability & Performance  
- By optimizing inefficient logic, refactoring ensures that the codebase can handle future growth without major rewrites.  
- Improves execution speed and memory usage by eliminating redundant operations.  

## 3. Reduces Bug Accumulation   
- Improves testability, making it easier to catch and fix bugs early.  

## 4. Encourages Best Practices & Standardization  
- Refactoring aligns the codebase with coding standards and modern best practices.  
- Ensures consistency across different modules, reducing friction when integrating new features.  

## 5. Minimizes Future Rework Costs  
- Technical debt accumulates when poor code quality requires frequent fixes.  
- By continuously refactoring, teams prevent expensive rewrites and major overhauls later.   

By making refactoring a routine practice, teams can maintain a healthy, efficient, and adaptable codebase while preventing the accumulation of technical debt. 

# Best Practices for Code Refactoring  

Maintaining software that is scalable, effective, and clean requires the technique of code restructuring. Understanding the current code, its dependencies, and any potential negative impacts is essential before making any changes in order to rework it successfully. By first developing a failed test (Red), then implementing code to pass the test (Green), and lastly refining the code structure while making sure the test still passes (Refactor), the "Red-Green-Refactor" cycle guarantees a methodical approach. By keeping refactoring modest and incremental, significant disruptions may be avoided and enhancements can be made gradually without overwhelming the development process.  

When refactoring, version control is essential because it allows developers to commit changes incrementally and undo them as necessary. Maintaining a robust test suite is also necessary to ensure that refactored code doesn't interfere with already-existing functionality. Stability can be ensured by running integration and unit tests both before and after refactoring. A more manageable and readable codebase is produced by following coding standards and best practices, such as consistent naming conventions, the SOLID principles, DRY (Don't Repeat Yourself), and KISS (Keep It Simple, Stupid).  

**Here is a more detailed picture for the coding practices**
![Image](https://github.com/nic-dgl104-winter-2025/assignment-1-programming-articles-sujal760/blob/main/screenshot%203.png?raw=true)

The References taken are :
1. for the pictures it was take from ashleys video :https://www.youtube.com/watch?v=iA5cFchPu0I
2. The topic are also taken from asleys video and my notes that i wrote in the class. 
3. The last picture was from google: https://cdn.sketchbubble.com/pub/media/catalog/product/optimized1/4/0/409d9a1914fd8abd3537fd79b4354d3a0bae3c4b0dfc6c7957d6646dc01a4c73/coding-best-practices-mc-slide5.png
