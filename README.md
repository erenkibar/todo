# todo

This is a very simple command-line tool for creating and managing a to-do list written in Python.
## To Do

*   Ability to sort the list based on priority.
*   Pushing notifications when a deadline approaches


## Getting Started
Just clone the repository to get started.
````

git clone http://github.com/erenkibar/todo.git

````
````
### Dependencies
	Python 3
````
## Usage
You can start the program with:

````
./todo.py
````
Make sure the program has the necessary permissions to write to the directory it is in.
````
usage: todo.py [-h] {add,list,remove} ...

An easy to use cli to-do list program.

positional arguments:
  {add,list,remove}  Commands you can use with the program
    add              Add a new item to the list.
    list             Show the contents of the list.
    remove           Remove an item from the list.

optional arguments:
  -h, --help         show this help message and exit


````
````
./todo.py add "Do this" -p h -d 2017.07.13

output:
No:   	 Task:                	 Deadline:
1     	 Do this              	 2017.07.13
2     	 Do that              	 2017.07.13

./todo.py remove 1
 
output:
No:   	 Task:                	 Deadline:
1     	 Do that              	 2017.07.13

````
Color of the item changes depending on the priority.

## Authors

* **Eren Kibar** - *Initial work* - [erenkibar](https://github.com/erenkibar)


## License

This project is licensed under GPLv3 - see the [LICENSE](LICENSE) file for details

