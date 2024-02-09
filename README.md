0x00. AirBnB clone - The console
********************************


Description of the Project
------------------------
The AirBnB clone - The Console project is a command-line interface (CLI) implementation of a simplified 
version of the AirBnB booking platform. It provides functionality for managing and interacting with 
AirBnB-like objects such as users, places, amenities, reviews, and bookings. The console serves as a basic 
tool for performing various operations related to these objects, including creating, updating, deleting, 
and displaying them.

Description of the Command Interpreter
-------------------------------------
The command interpreter provides a text-based interface for interacting with the AirBnB clone application. 
It allows users to execute commands to perform operations on the available objects. These commands are designed to 
mimic the actions one might perform on the AirBnB website or app, such as creating users, adding places,
leaving reviews, and making bookings.

How to start it
---------------
These instructions will get you a copy of the project up and running on your local machine (Linux distro) for development and testing purposes.

Installing
-------------

You will need to clone the repository of the project from Github. This will contain the simple shell program and all of its dependencies.

```
git clone https://github.com/ShadrachKadah/AirBnB_clone.git

add the second person as collabrator of this project into the repository
```
After cloning the repository you will have a folder called AirBnB_clone. In here there will be several files that allow the program to work.

> /console.py : The main executable of the project, the command interpreter.
>
> models/engine/file_storage.py: Class that serializes instances to a JSON file and deserializes JSON file to instances
>
> models/__ init __.py:  A unique `FileStorage` instance for the application
>
> models/base_model.py: Class that defines all common attributes/methods for other classes.
>
> models/user.py: User class that inherits from BaseModel
>
>models/state.py: State class that inherits from BaseModel
>
>models/city.py: City class that inherits from BaseModel
>
>models/amenity.py: Amenity class that inherits from BaseModel
>
>models/place.py: Place class that inherits from BaseModel
>
>models/review.py: Review class that inherits from BaseModel
