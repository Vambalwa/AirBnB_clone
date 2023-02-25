# AirBnB_clone
AirBnB_clone, The console project

Description
AirBnB is a complete web application, integrating database storage, a back-end API, and front-end interfacing in a clone of AirBnB.

The project currently only implements the back-end console.

Classes cl
AlxBnB utilizes the following classes:

BaseModel	FileStorage	User	State	City	Amenity	Place	Review
PUBLIC INSTANCE ATTRIBUTES	id
created_at
updated_at		Inherits from BaseModel	Inherits from BaseModel	Inherits from BaseModel	Inherits from BaseModel	Inherits from BaseModel	Inherits from BaseModel
PUBLIC INSTANCE METHODS	save
to_dict	all
new
save
reload	""	""	""	""	""	""
PUBLIC CLASS ATTRIBUTES			email
password
first_name
last_name	name	state_id
name	name	city_id
user_id
name
description
number_rooms
number_bathrooms
max_guest
price_by_night
latitude
longitude
amenity_ids	place_id
user_id
text
PRIVATE CLASS ATTRIBUTES		file_path
objects
Storage baggage_claim
The above classes are handled by the abstracted storage engine defined in the FileStorage class.

Every time the backend is initialized, AlxBnB instantiates an instance of FileStorage called storage. The storage object is loaded/re-loaded from any class instances stored in the JSON file file.json. As class instances are created, updated, or deleted, the storage object is used to register corresponding changes in the file.json.

Console computer
The console is a command line interpreter that permits management of the backend of AlxBnB. It can be used to handle and manipulate all classes utilized by the application (achieved by calls on the storage object defined above).

Using the Console
The AlxBnB console can be run both interactively and non-interactively. To run the console in non-interactive mode, pipe any command(s) into an execution of the file console.py at the command line.

$ echo "help" | ./console.py
(abnb)
Documented commands (type help <topic>):
========================================
EOF  all  count  create  destroy  help  quit  show  update

(abnb)
$
Alternatively, to use the HolbertonBnB console in interactive mode, run the file console.py by itself:

$ ./console.py
While running in interactive mode, the console displays a prompt for input:

$ ./console.py
(abnb)
To quit the console, enter the command quit, or input an EOF signal (ctrl-D).

$ ./console.py
(abnb) quit
$
$ ./console.py
(abnb) EOF
$

