# solid-principles

Ejemplos de los proncipios SOLID con clases en JAVA


Single Responsibility Principle

	The class must provide a very focused functionality and, there should never be more than 1 reason for a class to change.

Open Closed principle

	Should be opened for extension, but closed for modification
	We should be able to extend existing behavior
	FOr that use must stablish a Base class, make this abstract and identify the necessary methods that must be 
	override to implement the Openn for extension.

	Abstract method means - Open for extension
	Abstract method variables - Close for modifications

Liskov Substitution Principle

	We should be to substitute base class objetcs with child class objects and this should not alter behavior/characteristics of program.

Interface Segregation

	Clients should not be forced to depend upon interfaces that they do not use.
	Break interfaces which methods dont make sense into a particular class.
	Remove the method from the interface that is no common to all classes, and add it only to the corresponding class.


Dependency Inversion
	Not create instances in our high level module but let another modules to give those dependencies.

