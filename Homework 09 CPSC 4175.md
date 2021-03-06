# Homework 09 CPSC 4175

## 1. The book depicts an ideal software process as a linear flow, like this:
## Requirements ⇒ Analysis ⇒ Design ⇒ Implementation
## The book then notes that “software development is considerably different in practice[.]” Which reason do you think is more important for this difference, human error or changing requirements? Why?
### I think human error is the primary reason for the difference due to the fact right now the software process is not as refined or as perfected as other engineering domains due to its infancy.

## 2. What do you think that the book means when it says that “the waterfall model, which was first put forward in 1970, is iterative (but not incremental)?”
### The book refers to the "waterfall model" in that it is developed iteratively, in a fashion that each each stage of the model brings the overall product closer to the final product, but not incrementally because the waterfall model assumes that you are attempting to develop each functional portion of the product at the same time. 

## 3. Using the book’s explanation of stepwise refinement, relate an account from your previous personal experience when you used this type of development model. This does not have to be software related. Were you successful in your development? Why or why not?
### Stepwise refinement was used when I was working on my OOD project. This included me breaking down the components of the problem domain of Twin King's Chess into objects that were created with responsibility driven design in mind.

## 4. Looking at figure 2.4 in the book, you see that the Requirements workflow ceases at some point early in iteration 3, while the Test workflow runs from the very beginning of iteration 1 and ends at the very end of iteration 4. Make the case that the Requirements workflow should occur in all iterations. Make the case that the Test workflow should not begin until iteration 2 at the earliest.
### Assuming that a well designed and understood SRS has been created, the case that the Requirements workflow should occur in all iterations stems from the fact that a well made SRS should be constantly referred to if the SPMP is well designed as well. This includes any kind of modifications to the SRS from the Analysis, Design, Implementation, or Test workflows.
### The Test workflow perhaps shouldn't begin till iteration 2 at the earliest because the Test workflow that is most commonly referred to has to do with testing relations and interaction between already soundly designed and implemented artifacts. The first iteration being when those individual artifacts are designed.

## 5. Iterative and Incremental Model The book notes that “each iteration can be viewed as a small but complete waterfall model.” This is sometimes called the cascade model. Think about your experience in building your class project. How would you explain the iterative and incremental model to a young programmer who asked you how it worked. This question calls for a reflection on your experience, not a textbook answer. (Note that the iterative and incremental model and the spiral model are not the same thing — in this class we are using the spiral model.)
### The iterative and incremental model can be readily explained using an example from personal experience in designing the Board object that contains the 2d array of Tile objects that should have the proper linkage to all the designed data structures to represent the game board (Tiles, Vertexes, Edges). The algorithms for properly connecting the data structures and populating the Board object look complicated and ardouos but the reason for going through this process has to do with the simplification of the algorithmic logic that is necessary to implement the functionality the game board must have for the rules of the game. Before the linkage was not a priority till we iteravely looked back at the Board anlysis and design then incremented those workflows. 

## 6. The book notes that “[a] critical point regarding the waterfall model is that no phase is complete until the documentation for that phase has been completed[.]” Do you agree with this statement? If this statement were true, what changes in your personal process would you make to conform to this dictate?
### I think in theory that the statement or policy to finish all documentation of a phase before moving on to the next or considering it complete is a true statement. Theory and practice are not the same though as stated a multitude of times in the book. In my personal process I would if I were to apply the concept in a disciplined fashion I would make sure that the documentation would have its own process that would be followed at the end of any changes or actions taken.

## 7. The book discusses nine process models:
## (a) Evolution-tree Life-cycle Model
## (b) Iterative-and-incremental Life-cycle Model
## (c) Code-and-Fix Life-Cycle Model
## (d) Waterfall Life-Cycle Model
## (e) Rapid-Prototyping Life-Cycle Model
## (f) Open-Source Life-Cycle Model
## (g) Agile Processes
## (h) Synchronize-and-Stabilize Life-Cycle Model
## (i) Spiral Life-Cycle Model
## Of these seven, which do you think fits most closely with the software development process you think you would feel comfortable with? What is it about this process that appeals to you?
### Personally, the Agile Processes seem to fit most closely with the software development process I would be comfortable with. However, I do realize the possible pitfalls that could result in the following the agile processes strictly, mostly in the form of lacking design and analysis phases. I think this could be counteracted well with a concentration on design and analysis by those who are skilled or have expertise in creating structures for the software product that promote robustness so that the possible issues of poor design or analysis phases during the agile process is counteracted since the system is resilient to change or the issues possibly arising from poorly performed analysis or design.


## 8. This question is semi-optional — I don’t expect you to spend more that 15 minutes answering this, and I’ll be very lenient in grading this question. Open the paper Recursive Functions of Symbolic Expressions and Their Computation by Machine, Part I, which is recursive.pdf in the PDF directory of my Github account. Read Part 2 only, pages 2 to 8. I won’t ask you to study this paper, to do so would be an onerous assignment in itself. Write a one paragraph appreciation of Part 2. Those of you who are mathematically inclined may find that this suits your taste. For those of you who aren’t, this is an essential paper that you should at least have seen, even if you don’t have much patience with the mathematics.
### Part 2 of the recursive.pdf document denotes some basics in how functions are defined and labeled in a more mathematical approach so to allow for programmers to actually proof their algorithms and logic equations. This is important for a number of reasons having to do with safety and testing. Having this information on hand and being able to call on it when programming and designing algorithms can lead to more efficiently and safely producing algorithms that are able to be proven to be correct mathematically which in turn results in having less faults in the code.