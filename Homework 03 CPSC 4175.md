# CPSC 4175 HW03

## 1. What two kinds of things must a software requirements speciﬁcation contain?
### Software requirements specification have to contain an intelligible and clear conveyance of the specifications to the client, this usually entails language that is able to satisfy and inform the client who is not a computer specialist. It also is required to be complete and detailed due to the fact that it is virtually the only source of info for drawing up the design of the software.

## 2. Give an example of an ambiguous requirement in English (that is, using a natural language). Explain the ambiguity.
### An ambiguous requirement example would be a client wishing for the software to do a reduction regarding an amount contained in the software but not specifying how much of a reduction to meet their standards. This ambiguous kind of requirement is easy to remedy hopefully but it is ambiguous due to the fact that an exact amount was not specified.

## 3. Consider the domain of processing student grades. Draw a simple data ﬂow diagram of the process. Create the drawing as a PDF and upload the ﬁle to your Github repository. Explain the drawing in English as your answer to this question.
### The Data Flow Diagram Processing Student Grades.PDF attached starts with the first external actor of the Student:

1. Student passes work\_to\_be_done to the process do\_work\_to\_be\_graded
2. do\_work\_to\_be\_graded processes the work\_to\_be\_done and passes work\_to\_be\_turned\_in to STUDENT_WORK data storage
3. STUDENT_WORK data storage then is accessed by the Teacher and pulls turned\_in\_student\_work
4. Teacher grades turned\_in\_student\_work in the grade\_turned\_in\_student\_work process and gets graded\_turned\_in\_student\_work back
5. Teacher then passes graded\_turned\_in\_student\_work to the STUDENT_WORK data storage.
6. STUDENT_WORK automatically updates all\_student\_work in the update\_all\_student\_work\_grade process which sends updated\_all\_student\_work\_grade back to Student

## 4. Consider the domain of an online shopping cart. Draw a simple ﬁnite state machine of the process. Create the drawing as a PDF and upload the ﬁle to your Github repository. Explain the drawing in English as your answer to this question.
### The Finite State Machine for the online shopping cart has two initial states to properly describe the finite state machine diagram. The two are either an Empty Online Shopping Cart as well as an Non-Empty Online Shopping Cart. From there you can either navigate the site that has the Online Shopping Cart without selecting a product or select a product to add to the shopping cart. From here it checks if the product is available and you may only proceed to check out if you have a Non-Empty Online Shopping Cart. Once you proceed to check out you must provide valid information in order to finish the transaction. Once a transaction is finished you result with an Empty Online Shopping Cart. If at any point the product that is selected to add to the cart is not available it reverts to the previous state before selecting a product.

## 5. Consider the domain of a database with customer, products, and orders tables. Draw a simple entity- relation diagram of the database. Create the drawing as a PDF and upload the ﬁle to your Github repository. Give an account of the data structure in English as your answer to this question.
### The ERD of this domain shows that any one customer can order multiple products and any number of products can be on multiple order tables made when products are ordered.

## 6. Consider the project you have chosen as a team. Draw a simple SADT (structured analysis and design technique) diagram of the project. Create the drawing as a PDF and upload the ﬁle to your Github repository. Explain your project on a high level in English as your answer to this question.

## 7. This is not in the book. Consider the project you have chosen as a team. Draw a simple SDL (Speciﬁcation and Description Language) diagram of the project. Create the drawing as a PDF and upload the ﬁle to your Github repository. Explain your project on a high level in English as your answer to this question.

## 8. Find an image or document online of a simple function using Z. Convert the image or document to a PDF and upload it to your Github repository. Explain the speciﬁcation in English as your answer to this question. Note that the Z language is diﬃcult and takes years to learn. This course is not a course in Formal Methods, where you might spend an entire semester learning the Z language. You don’t have to understand the Z speciﬁcation. All you have to do is have some faint idea about its concept and operation.