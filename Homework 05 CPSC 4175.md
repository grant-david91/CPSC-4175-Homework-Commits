# Homework 05, CPSC 4175

## 1. What are the two basic ways of designing a product? Explain what they are and how they differ.
### Operation-oriented design has an emphasis on high cohesion with the designed modules.
### Data-oriented design is when the data is considered first focusing on how the data is stored and its structure and then the procedures are designed to conform to this.
### These two design methods differ in that operation-oriented design is concentrated highly on functionality first and then dealing with how to process the data after and the other is focused on the data first and the structure of how it's stored then functionality is implemented after.

## 2. What are the inputs and the outputs to the design workflow, according to the book? Briefly explain why the particular inputs are important and how they impact design. Briefly explain how the particular outputs are important and how they influence design.
### The inputs for the design workflow are the analysis workflow artifacts.
### The outputs range from the programming language the software will be implemented in, what parts of existing software products to reuse, decisions having to do with portability, and the allocation of each software component to the hardware component on which it runs.
### These different aspects are important because of it will affect the inherent structure and process of developing the project.
Language is important in how it streamlines the process of design by selecting an appropriate language for the problem domain.
Reusability and reuse is integral to a project due to the inherent cost reduction the proper application of varying techniques and uses of already made software artifacts.
Portability and allocation of the software components to the appropriate hardware is also an important aspect because this can also affect the inherent structure of the project and how it is broken up into subsystems.

## 3. Traditionally, a computer program was seen as a data processing application. Variables were divided into three categories: input variables, output variables, and processing variables. The book describes a design process based on this paradigm that is recursive. Explain in detail how you would design a student’s graduation requirements in terms of in[ut variables, utvariables, and processing variables. This is not asking for a design, but just identification of varibles you might want to create and where in the design you would place them.
### Input Variables: student identification information, student current academic information
### Output Variables: identified graduation requirements for the student and appropriate actions to take to fulfill those
### Processing Variables: logical modules that take the input variables and gives the output variables

## 4. Perform a transaction analysis for the graduation requirements problem you used for the previous question. Your answer should be a sequential list of subprocedures you would design to solve the problem. Notice that the previous question called for what was, in essence, a list of nouns, while this question calls for, in essence, a list of verbs.
### See HW05 Transaction Analysis Diagram

## 5. Object-oriented analysis and design conceptually is seen as a grouping of objects, instantiated from classes. Classes encapsulate both states (variables, nouns) and bejhavior (subprocedures, verbs). Based on your answers to the two previous questions, describe one class that jight be appropriate for a graduation requirements application. Identify the attributes (properties) and behaviours (methods) this class might contain.
### Student Class Variables: Name, Gender, Age, Nationality, Department, Degree, College Year
### Student Class Behaviors: Request Graduation Information, Request Academic Information

## 6. As discussed in the book, the design workflow can be considered an iterative, spiral process in itself. As we have been discussing in class, the design phase can be seen as part of an iterative that also includes analysis, implementation, and testing phases. The answer to this question obviously depends on the nature of the software under development, so there is no one correct answer to this question. Here is the question: Consider the software project you are working on for this class, and briefly state which view you think is more appropriate to your work. Justify your answer by making a reasonable argument as to why you answered this question the way you did.
### I believe the design workflow on our current project would be of an iterative, spiral nature in itself. This is due to the nature of how the initial design was done. Fulfilling responsibility driven design requirements the cross-module communication functions and operations would be developed further after addressing the functionality and structure of the entities within the problem domain.

## 7. What is the difference between desting an implementation and testing a design? Write a procedure for testing the design of the student graduation requirements problem in the questions above. Define a procedure for one of the following: either a data analysis design, a transaction analysis design, or an object oriented design.
### To test the design of the student graduation problem, we would need to check the algorithms to see if the syntax and logic is correct for interacting with the entities in the database that they would be stored.
### An object oriented design procedure to test the design itself would include being able to test to see if all objects instantiated to have the appropriate variables and methods to potray the entity in its functionality.

## 8. What is the cyclomatic complexity of figure 1? Explain your answer.
### The cyclomatic complexity of figure 1 is 3, this is due to the fact that the formula given in the book is that it is the number of binary decisions plus 1, and there is only 2 binary conditional statements in that figure.

## 9. Discuss one CASE tool you have previously used. If you have never used a CASE tool, find an open source CASE tool using an internet search, download and install it, complete a “Hello World” application, and discuss your experience.

## 10. Read the article “the-right-stuff.pdf” in the pdf directory. (You may find a better copy online.) Write a one paragraph appreciation of the article.
### The article portrays software engineering as it should, in it's infancy when it comes to having a industry spread practice to maintain a high standard in the process of making software. With how integral software is in our lives now why should we not hold ourselves to the same standards as other engineering disciplines? Problems and faults in calculations of a building or bridge or other engineering product that could result in critical failure of the product are unnacceptable in those professions and it should be in software engineering as well. The rigorous process that "the-right-stuff" is needed to go through to be what it is just as important as the actual sitting down and coding of a product.