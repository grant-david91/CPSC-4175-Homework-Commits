# Homework 10, CPSC-4175

## This homework includes significant research requirements beyond the text. It’s more important to focus on the general concepts than it is to memorize formulas. It’s also important to illustrate your understanding of the concepts by giving examples, and by writing brief summaries of the material.

## 1. In building a software product, the book identifies two kinds of planning that must occur. Name the two types and give two examples of each.
### The book denotes the two different types of planning as being planning that proceeds throughout the project as well as the intense planning that must be carried out once the specifications are complete.
### Planning that proceeds throughout the project: 
1. Quality Control Planning
2. Metrics Collection Planning
### Intense planning carried out once the specifications are complete:
1. Internal Structure Planning
2. External Interfaces Planning

## 2. What does figure 9.1 tell you about the range of cost estimates during the various workflows of a software project? Be specific as to the percentage of uncertainty at each of the four workflows shown on the X axis of the chart.
### Figure 9.1 shows that at the Requirements stage the uncertainty multiplier is 1/4 to 4 in range, at the Analysis stage the uncertainty multiplier is 1/3 to 3 in range, at the Design stage the unvertainty multiplier is 1/2 to 2 in range, and finally at the Implementation stage the uncertainty multiplier is narrowed down to 1. This tells me that as the software project moves further into development the uncertainty range narrows down.

## 3. The book identifies two different kinds of costs associated with building a software product. Identify the two kinds of costs, and for each give two examples.
### Internal Costs:
1. salaries of the development teams, managers, and support personnel
2. cost of the hardware and software used in developing the project
### External Costs:
1. economic factors for pricing for the client
2. psychological factors for pricing for the client

## 4. The book lists six reasons why the LOC (lines of code) metric may not be satisfactory. List four of them and for each, give an example (preferably from your own personal experience) showing the problematic nature of that reason.
### How to count lines of code:
Example: Counting lines of code that are comments can lead to incentivizing unproductive time spent on code, not counting lines of code that are comments incentivizes not commenting to increase productivity.
### Not all the code implemented is delivered to client: Reuse of code and other tools used in implementation are not actually delivered as part of the product to the client despite being able to use these tools.
### Implementation in different languages result in different different numbers of lines: Coding in two different languages can result in drastically different number of lines of code to be measured, Python vs Swift.
### Creation of source code is only a small part of the total software development effort: While in OOD class, the project that was worked on had all use-cases planned out and data structures designed before hand so to more quickly and easily implement the actual code.

## 5. The function point metric is widely used. Do some independent research on function point analysis/- function point estimation and write a brief summary of your research. In particular, Does there seem to be a widely accepted formula for function point estimation?
### With some independent research, it doesn't seem to be any one particular standard that is used more often and the different formulas and methods to go about measuring the function point metric are modified particularly around a variety of different metrics. These range from the different fields it may be used in and even algorithmic complexity.

## 6. The book references IEEE-158. This standard has been superseded by IEEE-16326. I have placed a copy of IEEE-16326 in the SWE directory of my Github repository for CPSC-4175. Select one major subsection of subsection 5 (Elements of the project management plan) and write a brief discussion of that major subsection. Choose whatever item interests you.
### Section 5.2 References is the a very important subsection despite the short description that it has. This section provides information from where communication and gaining the knowledge of the problem domain has happened and continues to happen. This is important because of the fact that without appropriate communication the SPMP might go off the rails when considering the needs of a client for the product. Knowing where the information comes from and when that is changed or gathered is important for accountability of both the developer and the client in the process of developing the product.

## 7. The book notes that, for every 100 hours developers spent on implementation, they spent 150 hours on activities related to documentation. Give some thought to your project in this class, and state some practices and/or guidelines you may adopt in an effort to generate appropriate documentation for your project. As you will discover when you work as a developer, in many cases, a failure to document your efforts is tantamount to a failure to complete the project.
### I would normally say that the standard that the book notes for time spent on implementation vs documentation is somewhat accurate. Documentation is a broad term that can refer to official planning, comments, and such in the process of developing the product. These are all important parts of documentation and assist in streamlining the actual implementation of the product. It also leaves a paper trail of when, where, and why modifications, additions, or deductions are made on the project.

## 8. Why do you think a user would conclude that you did not write a piece of software if you did not document the software?
### A user may think that you did not write a piece of software if there is no comments because it may hint that you did not fully understand the code despite knowing its function when you may have found it online.
