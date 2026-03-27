# AirBnB Clone Project
This project is a clone of the AirBnB web application.
It is built incrementally, starting with a command-line
interpreter that manages AirBnB objects such as Users,
States, Cities, and Places. The console allows creating,
updating, destroying, and storing these objects using a
file storage system.
## The Command Interpreter
The command interpreter works like a shell but is limited
to managing AirBnB objects. It supports both interactive
and non-interactive modes.
### How to start it
./console.py
### How to use it
Once started, you can type commands at the (hbnb) prompt.
Type help to see all available commands.
### Examples
Interactive mode:
$ ./console.py
(hbnb) help
Documented commands (type help <topic>):
EOF  help  quit
(hbnb) quit
$
Non-interactive mode:
$ echo "help" | ./console.py
(hbnb)
Documented commands (type help <topic>):
EOF  help  quit
(hbnb)
$
