# reimagined-design-patterns

Give a summary description of Four design patterns that you choose from the following design patterns: **Adapter,  Builder, Composite, Decorator, Observer, Interpreter, State, Mediator, Memento, Prototype, Proxy**. In your summaries say:

- what kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example
- how the pattern works, what the basic idea of the pattern is
- what the main advantage and what the the main disadvantage is of using this pattern
- Write a short summary for each of the four patterns, about half a page for each pattern (rather less than more). 

> Do not add diagrams, and do not try to give a complete description of the patterns as found in the books. Rather think of how you would explain the essential ideas of these patterns in a few sentences to a colleague while drinking coffee.
> 



**1.Adapter Pattern:

          -Adapter pattern works as a connection between two incompatible interfaces.
          
	-This pattern has a single class that is responsible to join functionalities of the incompatible interfaces.

**Problem statement:

    Whenever try to communicate two application with two different platform (XML and JSON), then we should need interface.
      
      
      A( XML)      ----(Adapter)----- B( JSON)


**Advantages:

          -This pattern is used to achieve two independent process communication    
          
          
          
  
**2. Builder Pattern:
 
        	-Builder pattern provides a step by step approach to build a complex object using simple object.

		-It creates the final object step by step

		-The builder will be independent of other objects
          
  **Problem statement:        
              
	    This can be  used when you want to build different immutable objects using same object building process.

**Advantages:
		
		-This pattern provides clear separation between the construction and representation of an object.

	     
	     
**3. Decorator Pattern:**

	-The decorator pattern acts as a wrapper to existing class, it is used to add new functionality to an existing object without altering its structure.
	
**Problem statement:  
		
		-The Coffee Ordering System has multiple types of Coffees, a new flavour of coffee can be added to the system without altering the existing feature.

**Advantages:
	This design pattern simplifies the coding by allowing to develop a series of functionality from targeted classes instead of coding all of the behavior into the object.
		


**4. Prototype pattern:**

	This pattern involves implementing a prototype interface which tells to create a clone of the current object. 
	The state pattern allows to change its behavior, when its internal state change. 
	
**Problem statement: 

	When ever program having multiple states, instead of using switch case
	we can go to state design pattern(abstract class)

**Advantages:
	-	It hides complexities of creating objects.

