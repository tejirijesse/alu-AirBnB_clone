Description
The ALU-AirBnB Console project is a simplified version of the AirBnB website, integrating essential components such as database storage, a back-end API, and front-end interfacing. It represents the first step towards building a full-scale web application, enabling data management through a custom command-line interface (CLI) and establishing the base classes for storing this data.

Command Interpreter
The Command Interpreter acts like a shell, tailored for specific use cases, allowing you to manage objects in the project. It facilitates the following capabilities:

Creating new objects Retrieving existing objects Updating object attributes Deleting objects

Steps for Developing the Command Interpreter
Set up the console for object creation, serialization/deserialization, and storage. Build HTML/CSS files for enhancing the user interface. Implement MySQL for managing database storage. Deploy the application on servers using Fabric. Integrate Flask to serve stored models and HTML. Establish RestAPI to handle objects in JSON format. Connect the JSON API dynamically with HTML for sharing the web application.

Running the Console
The console can be utilized in both interactive and non-interactive modes:

Interactive mode: Execute ./console.py and enter help to access available commands.
Non-interactive mode: Execute commands directly or via a file using echo or cat.
Supported Commands
Create: Create an object
Show: Display an object based on its ID
Destroy: Delete an object
All: Show all objects, either of one specific type or all types
Update: Modify an instance based on the class name and ID
Quit/EOF: Exit the console
Help: Obtain descriptions of available commands
How to Use
Initiate the console using ./console.py, followed by entering commands as per the supported formats.

Create
To create an object: create <class_name>

Show
To display an instance: show <class_name> <object_id>

Destroy
To delete an instance: destroy <class_name> <object_id>

All
To list all objects: all or all <class_name>

Update
To update an instance: update <class_name> <object_id> <attribute_name> "<new_value>"

Quit
To exit the console: quit or EOF (End of File) command

Help
For command information: help <command>

Supported Classes
BaseModel
User
State
City
Amenity
Place
Review

Authors
Oghenetejiri Jesse - o.jesse1@alustudent.com
Makuochi Prince Okoye - Makuochiokoye@gmail.com
