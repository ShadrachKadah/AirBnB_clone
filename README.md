0x00. AirBnB clone - The console
********************************




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
