# modelagemSupermercado

<h1>Basic Overview</h1>
This project consists of a study about classes, inheritance (subclass), and objects in Swift 5.

<h1>Project's Particularities</h1>
The main idea about this project is to apply the OPP pattern using a supermarket as a model with a few classes to represent it.<br />
<br />

Consisting in four classes, (```class Person```, ```class Employee```, ```class Client```, and ```class Product```), each class has at least six attributes and five methods. 
Employee class and Client class inherent from Person class, which also has the same amount of attributes and methods.

Due to this inheritance of methods and attributes, ```class Employee``` and ```class Client``` can use Person's attributes and methods like: check if it's birthday, calculate age, etc.

<h1>Classes Overview</h1>

<h2>class Person</h2>

<img src="https://github.com/rafaelnunesr/Img/blob/master/classStudy/class%20Person.JPG" />

Ps. ```getPhoneCityCode()```` only uses Brazilian cites as reference.

<h2>class Employee</h2>

<img src="https://github.com/rafaelnunesr/Img/blob/master/classStudy/class%20Employee.JPG" />

<h2>class Client</h2>
<img src="https://github.com/rafaelnunesr/Img/blob/master/classStudy/class%20Client.JPG" />

<h2>Relationship</h2>
<img src="https://github.com/rafaelnunesr/Img/blob/master/classStudy/relationship.JPG" />

Due to inheritance of ```class Person```, ```class Employee``` and ```class Client``` has the same attributes and methods from ```class Person```.
