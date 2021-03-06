# Homework 04, CPSC-4175
## Chapter 13, Object-Oriented and Classical Software Engineering
## August 30, 2017

## 1. What is an entity class? A boundary class? A control class?
### 1) an entity class is a class that stores information that lasts for long periods of time.
### 2) a boundary class is a class that usually is associated with inputs and outputs, modeling interactions between the software product and its actors
### 3) a control class is a class that usually has functions that implement complex computations and algorithms

## 2. Write a use case pertaining to your project.
### see Basic Use Case Diagram

## 3. Write a successful scenario pertaining to your project.
### 1) You, the current_player, grab a graphical asset representing a Road object on the Graphical User Interface.
### 2) The Player class, that you, the current_player, is represented by, determines you have the resources to build the road.
### 3) You drag the graphical asset representing a Road object, that you previously grabbed on the Graphical User Interface, to a location that you would like to build a Road on.
### 4) The Graphical User Interface then determines the nearest Edge that you, as the current_player, dragged the Road graphical asset to.
### 5) The Graphical User Interface then passes the Edge object, that it determined you, as the current_player, wished to build a Road object on, to the Game Engine class.
### 6) The Game Engine then determines the Edge object that was passed is a valid edge to build a Road object for you, the current_player.
### 7) The Game Engine then creates a Road object and links the edge attribute to the Edge that was passed.
### 8) The Game Engine then passes the newly created Road object to the Player class of the current_player, you.
### 9) The Player class representing the current_player, you, then links the previously passed Road object's attribute of owner to itself, the current_player, you.

## 4. Write an unsuccessful scenario pertaining to your project.
### 1) You, the current_player, grab a graphical asset representing a Road object on the Graphical User Interface.
### 2) The Player class, that you, are represented by, current_player, determines that you have the resources to build the road.
### 3) You drag the graphical asset representing a Road object, that you previously grabbed on the Graphical User Interface, to a location that you would like to build a Road on.
### 4) The Graphical User Interface then determines the nearest Edge that you, as the current_player, dragged the Road graphical asset to.
### 5) The Graphical User Interface then passes the Edge object, that it determined you, as the current_player, wished to build a Road object on, to the Game Engine class.
### 6) The Game Engine then determines the Edge object that was passed is not a valid edge to build a Road object for you, the current_player.
### 7) The Game Engine then passes a None value back to the Player class representing the current_player, you.

## 5. Using your answers to the three previous questions, use the noun extraction method to extract the classes. If practicable, identify the classes you extract as entity, boundary, and control classes. If all your classes are entity classes, you will not be able to do this.
### Entity Classes Identified:
Player, Game State, Edge, Road, Inventory
### Boundary Classes Identified:
Graphical User Interface
### Control Classes Identified:
Game Engine

## 6. Using your answer to the previous question, draw an appropriate class diagram.
### see Class Diagram

## 7. Complete a CRC card for one of your classes.
### see https://echeung.me/crcmaker/?share=W3sibmFtZSI6IkdhbWUgU3RhdGUiLCJzdXBlcmNsYXNzZXMiOiIiLCJzdWJjbGFzc2VzIjoiIiwidHlwZSI6MSwicmVzcG9uc2liaWxpdGllcyI6WyJCb2FyZCIsIlBsYXllcl9BcnJheSIsIkN1cnJlbnRfUGxheWVyIl0sImNvbGxhYm9yYXRvcnMiOlsiR2FtZUVuZ2luZSIsIkdyYXBoaWNhbFVzZXJJbnRlcmZhY2UiXX1d

## 8. Draw a statechart for one specific behavior of your project.
### see Settlers of Definitely Not Katan Build Road State Chart

## 9. Draw a communication diagram for one specific realization of a use case.
### see Settlers of Definitely Not Katan Comm Diagram

## 10. Draw a sequence diagram for one specific realization of a use case.
### see Settlers of Definitely Not Katan Sequence Diagram