Description 
This is the first phase of the Airbnb Clone: the console. This repository holds a command interpreter and classes (i.e. BaseModel class and several other classes that inherit from it: Amenity, City, State, Place, Review, User), and a command interpreter. The command interpreter, like a shell, can be activated, take in user input, and perform certain tasks to manipulate the object instances.

Command: help
Sample Usage: help
Function: displays all commands available

Command: create
Sample Usage: create <class>
Function: creates new object (ex. a new User, Place)

Command: update
Sample Usage: User.update('123', {'name' : 'Greg_n_Mel'})
Function: updates attribute of an object

Command: destroy
Sample Usage: User.destroy('123')
Function: destroys specified object

Command: show
Sample Usage: User.show('123')
Function: retrieve an object from a file, a database

Command: all
Sample Usage: User.all()
Function: display all objects in class

Command: count
Sample Usage: User.count()
Function: returns count of objects in specified class

Command: quit
Sample Usage: quit
Function: exits
