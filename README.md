This project is a build-up of the AirBnB clone project
In this step, we add a tool, like a control panel, to handle program information. By typing commands into this control panel, users can make, change, or remove things and also deal with saving files. We use a method called JSON to keep the information saved even when you close and reopen the program.

Supported Commands:

These are commands that can be executed by the command interpreter. They have the format command [argument]... but you could also use the format Model.command([argument]...), with the exception of the first 3 commands below.

Format	Description
help [command]	Prints helpful information about a command (command). If command is not provided, it prints the help menu.
quit	Closes the command interpreter.
EOF	Closes the command interpreter.
create Model [prop_key=prop_value]...	Creates a new instance of the Model class with the given properties. prop_value can be a double-quoted string with double-quotes escaped and spaces replaced with underscores. prop_value can also be a float or integer.
count Model	Prints the number of instances of the Model class.
show Model id	Prints the string representation of an instance of the Model class with the given id.
destroy Model id	Deletes an instance of the Model class with the given id.
all [Model]	Prints a list containing the string representation of all instances of the Model class. Model is optional and if it isn't provided, all the availble objects are printed.
update Model id attr_name attr_value	Updates an instance of the Model class with the given id by assigning the attribute value attr_value to its attribute named attr_name. Attributes having the names __class__, id, created_at, and updated_at are silently ignored.
update Model id dict_repr	Updates an instance of Model having the given id by storing the key, value pairs in the given dict_repr dictionary as its attributes. The keys __class__, id, created_at, and updated_at are silently ignored.

run ./console.py to use commands

