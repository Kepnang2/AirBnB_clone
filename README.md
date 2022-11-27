https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2018/6/65f4a1dd9c51265f49d0.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20221127%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20221127T174123Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=9a0b135ddc06f8dd139b2f620bf7609f100eb29c87cb0ae104a8ed19c6d0561d
0x00. AirBnB clone - The console
Description of the project.
The Airbnb Clone: The console. This repository holds a command interpreter and classes (such as; BaseModel classand other classes that inherit from BaseModel: Amenity, City, State, Place, Review), and a command interpreterlike a shell
https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2018/6/815046647d23428a14ca.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20221127%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20221127T174123Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=23f068b878a09bd717a6e8c450d89b3c34004bce19f1469352ee74777f8cca4d
Command interpreter functionalities.
Create a new object (ex: a new User or a new Place)
Retrieve an object from a file, a database etc…
Do operations on objects (count, compute stats, etc…)
Update attributes of an object
Destroy an object
File Storage Engine:
/models/engine/file_storage.py
Execution
Your shell should work like this in interactive mode:

$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$
But also in non-interactive mode: (like the Shell project in C)

$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
All tests should also pass in non-interactive mode: ``$ echo "python3 -m unittest discover tests" | bash```
Author
1. Kepnang Pebeu Maxime Fabrice
2. Olumide Ayeromara
