# Homework 06, CPSC-4175, Chapter 15

## 1. Consider the programing languages you may have studied and their differences. Think of two problem domains you would use for each language. For each problem domain, explain why your choice of the other language would be a poorer choice for an implementation language.
### Currently, I only know particularly well Java and Swift. 
### Considering a problem domain of developing a piece of software that interacts with both a database as well as a web page, Java would be best. Despite the similarities in Java and Swift, Swift is particularly a language best for developing apps in the IOS environment. Java already has many different frameworks and interface options that work with existing environments to integrate database capability as well as web page based interactions.
### Another problem domain, of developing an app for IOS users, the obvious go to language of the two for this would be Swift.

## 2. Give some concrete counter-examples of good programming practices as discussed in the book. These include meaningful variable names, self documenting code, symbolic constants, and code layout. In other words, give examples of what not to do.
### When naming variables, try not to use mutliple words referring to the same thing, (ie... mean and average)
### Self-documenting code is useful, however truly self-documenting code is exceedingly rare. A poor implementation at an attempt at self-documenting code would be code that has ambiguous references/variable names as well as poorly named functions or methods.
### Symbolic constants are used in code to allow for easier maintenance and changing code. A poor implementation would be to not use symbolic constants and instead hard code values, doing so makes changing your code a complicated task especially if that value is used often because you'd have to go to each instance of it being used in a possibly large piece of software and you may miss an instance somewhere in the code giving you an incorrect calculation or result.
### Poor code layout practices can result in hard to read lines of code to understand the proper structure or funcionality. An example of this is why we use nested if statements. Not following good code layout practices would be to not separate the different if statements on different lines to increase readability.

## 3. Give two versions of coding standards for subprocedure blocks. This may require an internet search. Which do you prefer, and why?


## 4. An informal description of the DRY principle is this: “The second time you write exactly the same code, stop what you are doing and place that functionality in a subprocedure. Then, invoke the subprocedure whenever you need that functionality.” Give one example of this from your previous programming experience. If you have never experienced this in practice, make up an example.
### In the current software we are working on I've had to design a variety of subprocedures in order to perform a multitude of checks based on different variables passed to a function in order to proceed with the correct actions.

## 5. What is a stub? What is a driver? Have you ever used stubs or drivers in your previous programming experience? If so, give an example. If not, consider a function that takes a unit price, a sales tax rate, and the quantity ordered, and write a stub (using pseudo code or a language of your choice) that takes these three arguments and returns a value.
### A stub is a code artifact that is similar to what a subprocedure would be considered. Often within the scope of a driver and only used to return values necessary for the driver to proceed.
### A driver is a code artifact that calls on a stub one or more times often to test stub code artifacts.
### stubProcedure(unit_price, sales_tax_rate, quantity_ordered) -> [Int] { return value_array [ unite_price, sales_tax_rate, quantity_ordered ]; }

## 6. List two strengths and one weakness of top down integration.
### Two strengths of top down integration can be fault isolation and an early recognition of major design flaws.
### One weakness of top down integration can be that potentially reusable code artifacts may not be adequately tested.

## 7. List two strengths and one weakness of bottom up integration.
### Two strenghts of bottom up integration can be that operational artifacts are tested thoroughly and fault isolation.
### One weakness of bottom up integration can be that major design faults are detected late in the implementation workflow.

## 8. This is not in the book and will require some independent research. A domain specific language (DSL) is a small, incomplete language typically use as a “glue” language between a lower level language (like C) and a higher level language (like Python). An example of a DSL might be a helper language for HTML, e.g. div(...) might resolve to <div> ...</div>. How might a DSL promote what the book calls sandwich integration? This is not a trick question but it will require some thought. If you work as a developer, you will eventually write your own DSLs for various purposes.
### A DSL might help with sandwich integration specifically in the role that the interfaces that would be considered the sandwich filling, the logic artifacts as the top of the sandwich, and the operational artifacts as the bottom of the sandwich.

## 9. What is the difference in testing carried out by the implementation group and the testing carried out by the SQA group?
### The testing of the implementation group would be considered integration testing. This involves a number of techniques to test the different code artifacts at different times of integration to assure that adding or changing or removing anything hasn't impaired the software in its functionality.
### The testing of the SQA group would be considered product testing. This also involves a number of testing techniques to assure that the product passes acceptance tests. The results of this range from making sure the product satisfies all of its contraints, documentation conforms to standards and is accurate, and the robustness of the product as well.

## 10. Read the letter by Edgar Dijkstra to the Communications of the ACM (in the PDF directory as dijkstra68.pdf) and write a one paragraph appreciation of this letter.
### The letter written by Edgar Dijkstra addresses the practice of using goto statements in programming at the time of the penning of the letter. The letter seemed to be released at a time that the first computer theory discussions on structured programming began to crop up. As stated in the letter this was due to the lack of built in program control structures to allow for subroutines, loops, and switch-case statements. This allowed for more flexibility when writing programs and I'd even say the start of Object Oriented Designed progamming languages.